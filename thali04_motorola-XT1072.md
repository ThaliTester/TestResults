#### Test 54970261ac9928f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/AndroidRuntime( 6756): 
D/AndroidRuntime( 6756): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6756): CheckJNI is OFF
D/AndroidRuntime( 6756): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6775 uid=10423 gids={50423, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6756): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6775): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6775): Time to load native libraries: 4 ms (timestamps 8043-8047)
,I/LibraryLoader( 6775): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6775): Binding Chromium to main looper Looper (main, tid 1) {1b30758c}
,I/LibraryLoader( 6775): Expected native library version number "",actual native library version number ""
,I/chromium( 6775): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6775): Initializing chromium process, singleProcess=true
,W/art     ( 6775): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6775): ApplicationContext is null in ApplicationStatus
,W/chromium( 6775): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6775): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6775): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6775): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6775): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6775): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6775): Local Branch: 
I/Adreno-EGL( 6775): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6775): Local Patches: NONE
I/Adreno-EGL( 6775): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c72a75d:true
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{384a7f6e u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6775): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6775): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6775): CordovaWebView is running on device made by: motorola
,W/art     ( 6775): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6775): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6775): Render dirty regions requested: true
,D/Atlas   ( 6775): Validating map...
,W/chromium( 6775): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6775): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6775): Enabling debug mode 0
,I/Keyboard.Facilitator( 1415): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,975
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +906ms (total +975ms)
,W/IInputConnectionWrapper( 6775): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6775): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6775): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6775): Cannot call determinedVisibility() - never saw a connection for the pid: 6775
,D/JsMessageQueue( 6775): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6775): JniHelper::setJavaVM(0xb7a97310), pthread_self() = -1209895600
D/JX-Cordova( 6775): jxcore cordova android initializing
,W/jxcore-log( 6775): Initializing JXcore engine
W/jxcore-log( 6775): JXcore engine is ready
,W/jxcore-log( 6775): Starting JXcore engine
,W/.test.thalitest( 6775): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10423 path="socket:[5846]" dev="sockfs" ino=5846 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6775): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10423 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6775): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10423 path="socket:[9548]" dev="sockfs" ino=9548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6775): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10423 path="socket:[28190]" dev="sockfs" ino=28190 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6775): Platform android
W/jxcore-log( 6775): 
W/jxcore-log( 6775): Process ARCH arm
W/jxcore-log( 6775): 
,I/jxcore-log( 6775): JXcore Cordova bridge is ready!
I/jxcore-log( 6775): 
W/jxcore-log( 6775): JXcore engine is started
,I/Choreographer( 6775): Skipped 175 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6775): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6775): Toggling radios to true
I/jxcore-log( 6775): 
,D/BluetoothAdapter( 6775): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6775, uid=10423
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6775): Radios toggled
I/jxcore-log( 6775): 
,I/wpa_supplicant( 1436): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
,D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1436): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1436): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  880): InitialState.processMessage what=4
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
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
E/wpa_supplicant( 1436): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/TCMD    (  489): NL - Read 60 bytes from update socket.
D/TCMD    (  489): NL - ignore NL message, type = 21
D/TCMD    (  489): Listening for incoming client connection request
,V/NativeCrypto( 1745): Read error: ssl=0xb7da1f20: I/O error during system call, Connection timed out
,V/NativeCrypto( 1745): SSL shutdown failed: ssl=0xb7da1f20: I/O error during system call, Broken pipe
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-8ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-8ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiMetrics(  880): connected time updated 123390
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6855 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1436): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1436): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1436): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6855): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
V/AlarmManager(  880): send {3ca982fc, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6882 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6527:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 8
D/TCMD    (  489): NL - Read 56 bytes from update socket.
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/TCMD    (  489): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1436): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  880): [1,452,269,633,337 ms] noteScanEnd no scan source
E/wpa_supplicant( 1436): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@49c3380 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6527/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6882): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1745): Scheduling Phenotype for one-off execution 4707 seconds from now (1452269633410)
,D/GetConfigurationSnapshotOperation( 1745): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TCMD    (  489): NL - Read 312 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 192 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
,I/wpa_supplicant( 1436): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  489): NL - Read 80 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 80 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/TCMD    (  489): NL - Read 68 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1436): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1436): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  489): NL - Read 1004 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1204634328
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
,E/MDMCTBK (  294): MdmCutbackHndler, resp=OK,
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/PhenotypeFlagCommitter( 1745): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  292): Setting iface cfg
E/WifiStateMachine(  880): Start Dhcp Watchdog 2
I/GoogleURLConnFactory( 1745): Using platform SSLCertificateSocketFactory
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 1436): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1436): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@313db29d target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@313db29d target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6882): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6882): MmsConfig.loadMmsSettings
I/Babel_SMS( 6882): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6882): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6882): MmsConfig.loadFromResources
,E/Babel_SMS( 6882): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6882): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/Uploader( 1745): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/DHCPCD  ( 6917): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6917): version 5.5.6 starting
E/DHCPCD  ( 6917): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6917): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6917): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/Settings( 6882): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6882): startup - clean
,I/Babel   ( 6882): deleted: false for 0
,D/DHCPCD  ( 6917): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6917): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6917): wlan0: sending REQUEST (xid 0xb9746ff4), next in 4.46 seconds
,V/AlarmManager(  880): done {3ca982fc, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [843ms]
,I/DHCPCD  ( 6917): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6882): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6882): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6882): Unsupported profile 4 for video/mp4v-es
,I/DHCPCD  ( 6917): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6917): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6917): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6917): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6917): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  489): NL - Read 60 bytes from update socket.
D/TCMD    (  489): NL - ignore NL message, type = 20
D/TCMD    (  489): Listening for incoming client connection request
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/DHCPCD  ( 6917): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6882): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6882): onServiceConnected
W/Babel   ( 6882): Attempted to change video mute state without an active call.
,I/ActivityManager(  880): Killing 6572:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6572/cgroup.procs: No such file or directory
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 16:13:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452269634524], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452269634494]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/global frequency( 2684): no tags to log
,D/Checkin ( 2684): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 71220(3MB) AllocSpace objects, 4(248KB) LOS objects, 33% free, 20MB/30MB, paused 1.980ms total 161.759ms
,V/AlarmManager(  880): send {2dca8cb7, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {2dca8cb7, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 56152(3MB) AllocSpace objects, 36(1240KB) LOS objects, 39% free, 7MB/12MB, paused 791us total 45.106ms
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2684): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2684): Explicit concurrent mark sweep GC freed 59961(3MB) AllocSpace objects, 17(284KB) LOS objects, 39% free, 11MB/19MB, paused 1.350ms total 91.165ms
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6988 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1472): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/BSUtils ( 2684): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 4263(187KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.209ms total 29.058ms
,D/BSUtils ( 2684): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2684): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2684): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2684): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin ( 2684): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2684): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2684): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin ( 2684): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2684): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2684): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2684): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2684): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2684): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2684): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2684): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2684): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2684): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2684): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2684): [debug] > CusSM.onRadioDown
,I/MusicStore( 6988): Database version: 120
,I/global frequency( 2684): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2684): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6988): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6988): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6988): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6988): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6988): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6988): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6988): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6988): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@850ea68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6988): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6988): GMSCore installation verified
,I/ConfigStore( 6988): Config Database version: 1
,I/MediaRouter( 6988): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6988): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7018 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6988): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6988): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/art     (  880): Explicit concurrent mark sweep GC freed 11278(569KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.688ms total 114.655ms
,I/ActivityManager(  880): Killing 6332:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 7018): mnc/mcc: 
V/Mms     ( 7018): tag: int value: recipientLimit - 20
V/Mms     ( 7018): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7018): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7018): tag: int value: maxSubjectLength - 80
V/Mms     ( 7018): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7018): tag: bool value: enableGroupMms - false
V/Mms     ( 7018):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6332/cgroup.procs: No such file or directory
,W/ResourcesManager( 7018): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7045 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2684): now: 197150 ,futureTime: 9223372036854775807
D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2684): now: 197150 ,futureTime: 9223372036854775807
D/PollingManager( 2684): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2684): now: 197151 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1472): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2684): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1472): now: 197154 ,futureTime: 86475028
D/Central_PollingManager( 1472): Polling alarm set to expire at: 86475028 Current Time: 197154
,D/OtaApp  ( 2684): [debug] > PollingManagerService, now: 197156 ,futureTime: 86520162
D/OtaApp  ( 2684): [debug] > Polling alarm set to expire at: 86520162 Current Time: 197157
,I/NetworkMonitor( 6988): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2684): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2684): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2684): createDeviceIdOrLogin update_device
,D/Checkin ( 2684): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2684): Not proxy app, so login/provision not allowed
,I/ActivityManager(  880): Killing 6418:com.android.vending/u0a32 (adj 15): empty #7
,D/MMApiProvisionService( 2684): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2684): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2684): createDeviceIdOrLogin update_device
D/Checkin ( 2684): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2684): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2684): set mOutstandingReq to true.
I/ Nonce  ( 2684):  Nonce getNonce 
I/ Nonce  ( 2684):  Nonce Request 
I/ Nonce  ( 2684):  Nonce execute Request 
,D/MMApiWebService( 2684): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/PhoneMonitor( 7045): Register our PhoneStateListener
,D/MMApiProvisionService( 2684): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2684): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2684): createDeviceIdOrLogin update_device
,D/Checkin ( 2684): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2684): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2684): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2684): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2684): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2684): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2684): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2684): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2684): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2684): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/MMApiWebService( 2684): generating token using payload instead of using session token
D/OtaApp  ( 2684): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/ Nonce  ( 2684):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2684): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2684): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6418/cgroup.procs: No such file or directory
,D/OtaApp  ( 2684): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MobileConnectivityChangeReceiver( 7045): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7045): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6882:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6882/cgroup.procs: No such file or directory
,I/CheckinService( 6634): Checkin interval check for package: unspecified last checkin: 1452269553686 min interval config: 0 actual interval: 84410
,I/CheckinService( 6634): Disabling old GoogleServicesFramework version
,I/CheckinService( 6634): Checking schedule, now: 1452269638125 next: 1452269583164
I/CheckinService( 6634): active receiver: enabled
,I/iu.SyncManager( 6634): SYNC; picasa accounts
,D/NetworkLogImpl( 6634): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 6634): Preparing to send checkin request
,I/EventLogService( 6634): Accumulating logs since 1452269550066
,I/iu.UploadsManager( 6634): num queued entries: 0
I/iu.UploadsManager( 6634): num updated entries: 0
I/iu.SyncManager( 6634): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7086 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6634): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6634): Failed to find provider info for com.google.android.wearable.settings
,I/ Nonce  ( 2684):  Nonce Reponse 
D/        ( 2684): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"4250986f-7761-4a80-af92-97ec01459ef9"}
D/MMApiWSBase( 2684): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2684):  Nonce Handle Reponse 
D/MMApiProvisionService( 2684): mOutstandingReq set to false
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7116 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/MMApiProvisionService( 2684):  pTime 1452107623780 sExp 172742 cTime 1452269638717 tTime 1452280365780
,D/MMApiProvisionService( 2684):  No login Required 
,W/ResourcesManager( 7116): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7116): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7116): VM with version 2.1.0 has multidex support
I/MultiDex( 7116): install
I/MultiDex( 7116): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7134 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/JNIHelp ( 7116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7134): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityThread( 7116): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7116): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4727869: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7116): Installed default security provider GmsCore_OpenSSL
,I/art     (  880): Explicit concurrent mark sweep GC freed 8905(421KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.022ms total 110.802ms
,W/DataUsage( 2684): invalid counter update blocked: 'err' by 0
D/Checkin ( 2684): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 7116): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7116): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 7134): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7134): MmsConfig.loadMmsSettings
I/Babel_SMS( 7134): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7134): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7134): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7134): MmsConfig.loadFromResources
,E/Babel_SMS( 7134): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7134): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 7116): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     ( 6604): Explicit concurrent mark sweep GC freed 1991(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 391us total 25.066ms
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f82000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f82000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb126a960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb760f058, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75aa7a0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb766cc78, idLength=0xb136a730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=328490293
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb757baf0
D/DrmWidevineDash(  296): message_length=1591, signature=0xb75589a0, signature_length=2973148948
,W/Settings( 7134): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7134): startup - clean
,I/Babel   ( 7134): deleted: false for 0
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7174 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 24.875ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 18.928ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 19.584ms
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 7134): Unrecognized profile 2130706433 for video/avc
D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,W/AudioCapabilities( 7134): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7134): Unsupported mime video/mpeg2
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f66000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f66000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5454960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb760f5d8, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75aa7a0, wrapped_rsa_key_length=1280
I/VideoCapabilities( 7134): Unsupported profile 4 for video/mp4v-es
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb766ccb8, idLength=0xb5454730
,W/VideoCapabilities( 7134): Unrecognized profile 2130706433 for video/avc
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=1333987220
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb753eb30
D/DrmWidevineDash(  296): message_length=1626, signature=0xb7558c60, signature_length=3041216276
W/VideoCapabilities( 7134): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7134): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7134): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7134): onServiceConnected
W/Babel   ( 7134): Attempted to change video mute state without an active call.
,I/Babel   ( 7134): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6855:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6855/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7174): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7174): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7174):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7174):   adb logcat -s GAv4
,W/GAv4    ( 7174): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7174): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7174): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 7174): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7174): Time to load native libraries: 2 ms (timestamps 341-343)
I/LibraryLoader( 7174): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7174): Binding Chromium to main looper Looper (main, tid 1) {2ddd4dd9}
I/LibraryLoader( 7174): Expected native library version number "",actual native library version number ""
I/chromium( 7174): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7174): Initializing chromium process, singleProcess=true
W/art     ( 7174): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7174): ApplicationContext is null in ApplicationStatus
,W/chromium( 7174): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7174): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7174): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7174): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7174): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7174): Local Branch: 
I/Adreno-EGL( 7174): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7174): Local Patches: NONE
I/Adreno-EGL( 7174): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7174): Requires BLUETOOTH permission
,I/dex2oat ( 7227): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/NSApplication( 7174): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7248 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6988:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 7227): dex2oat took 85.229ms (threads: 4)
,I/Adreno-EGL( 7116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7116): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7116): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7116): Local Branch: 
I/Adreno-EGL( 7116): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7116): Local Patches: NONE
I/Adreno-EGL( 7116): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7116): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7116): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7116): Local Branch: 
I/Adreno-EGL( 7116): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7116): Local Patches: NONE
I/Adreno-EGL( 7116): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6988/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7273 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7018:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 7116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7116): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7116): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7116): Local Branch: 
I/Adreno-EGL( 7116): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7116): Local Patches: NONE
I/Adreno-EGL( 7116): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7018/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7116): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7116): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7116): Local Branch: 
I/Adreno-EGL( 7116): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7116): Local Patches: NONE
I/Adreno-EGL( 7116): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6634): Classify the device as Phone.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7301 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinTask( 6634): Sending checkin request (9527 bytes)
,I/ContactLocale( 7301): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7322 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7086:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7045:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/CheckinRequestBuilder( 6634): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7086/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7045/cgroup.procs: No such file or directory
,E/ActivityThread( 6634): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 7322): Database version: 120
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311929, SEQNUM=4459, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-329, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7322): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6634): Classify the device as Phone.
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7322): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7322): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6634): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6634): Checking schedule, now: 1452269642703 next: 1452870779694
I/CheckinService( 6634): active receiver: disabled
,D/CheckinService( 6634): Recording last checkin time for package unspecified as 1452269642715
,I/ActivityManager(  880): Killing 7134:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 7322): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7322): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7134/cgroup.procs: No such file or directory
,V/JNIHelp ( 7322): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7322): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7322): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@850ea68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7322): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7322): GMSCore installation verified
,I/ConfigStore( 7322): Config Database version: 1
,I/MediaRouter( 7322): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7322): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7322): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Killing 7174:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7174/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7322): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7377 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7322): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7322): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7116:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7377): mnc/mcc: 
,V/Mms     ( 7377): tag: int value: recipientLimit - 20
V/Mms     ( 7377): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7377): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7377): tag: int value: maxSubjectLength - 80
V/Mms     ( 7377): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7377): tag: bool value: enableGroupMms - false
,V/Mms     ( 7377):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7116/cgroup.procs: No such file or directory
,W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 13730(710KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.887ms total 111.864ms
,W/ResourcesManager( 7377): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7413 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7248:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7248/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7413): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7413): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7413): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7301:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7301/cgroup.procs: No such file or directory
,I/CheckinService( 6634): Checkin interval check for package: unspecified last checkin: 1452269642715 min interval config: 0 actual interval: 1947
,I/CheckinService( 6634): Checking schedule, now: 1452269644673 next: 1452269672694
I/CheckinService( 6634): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7438 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7459 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7459): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7459): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7459): VM with version 2.1.0 has multidex support
I/MultiDex( 7459): install
I/MultiDex( 7459): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7478 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7273:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7273/cgroup.procs: No such file or directory
,I/jxcore-log( 6775): Test app app.js loaded
I/jxcore-log( 6775): 
,I/Choreographer( 6775): Skipped 756 frames!  The application may be doing too much work on its main thread.
,W/ResourcesManager( 7478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/chromium( 6775): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/JNIHelp ( 7459): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7459): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7459): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4727869: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7459): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7459): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7459): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  880): Killing 7322:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/NativeLibraryUtils( 7459): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7322/cgroup.procs: No such file or directory
,I/Babel_SMS( 7478): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7478): MmsConfig.loadMmsSettings
I/Babel_SMS( 7478): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7478): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7478): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7478): MmsConfig.loadFromResources
E/Babel_SMS( 7478): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7478): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7478): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7478): startup - clean
,I/Babel   ( 7478): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7512 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7478): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7478): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7478): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7478): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7478): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7478): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7478): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7478): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7478): onServiceConnected
W/Babel   ( 7478): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7512): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7512):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7512):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7512): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7512): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7478): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7377:com.android.mms/u0a23 (adj 15): empty #7
,W/GAv4    ( 7512): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7512): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7377/cgroup.procs: No such file or directory
,I/WebViewFactory( 7512): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7512): Time to load native libraries: 2 ms (timestamps 5863-5865)
I/LibraryLoader( 7512): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7512): Binding Chromium to main looper Looper (main, tid 1) {2ddd4dd9}
,I/LibraryLoader( 7512): Expected native library version number "",actual native library version number ""
,I/chromium( 7512): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7512): Initializing chromium process, singleProcess=true
,W/art     ( 7512): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7512): ApplicationContext is null in ApplicationStatus
,W/chromium( 7512): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7512): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7512): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7512): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7512): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7512): Local Branch: 
I/Adreno-EGL( 7512): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7512): Local Patches: NONE
I/Adreno-EGL( 7512): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7512): Requires BLUETOOTH permission
,I/NSApplication( 7512): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7586 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7413:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.935ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 21.582ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.562ms
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7413/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7605 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7438:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7438/cgroup.procs: No such file or directory
,W/ResourcesManager( 7605): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7625 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7478:com.google.android.talk/u0a70 (adj 15): empty #7
,D/EmailService.MarketingOptInSetter( 2684): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  880): Killing 7512:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7478/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7512/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2684): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2684): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2684): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2684): onServiceConnected()
,D/GetNotificationsWS( 2684): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2684): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7648 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2684): started with background data enabled, making sure notification mechanism is enabled
,I/ContactLocale( 7625): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/MusicStore( 7648): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7648): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7648): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7648): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7648): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7648): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7648): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@850ea68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7648): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7648): GMSCore installation verified
,I/ConfigStore( 7648): Config Database version: 1
,I/MediaRouter( 7648): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7648): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7648): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7648): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7686 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7648): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7648): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7459:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7686): mnc/mcc: 
V/Mms     ( 7686): tag: int value: recipientLimit - 20
,V/Mms     ( 7686): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7686): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7686): tag: int value: maxSubjectLength - 80
V/Mms     ( 7686): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7686): tag: bool value: enableGroupMms - false
V/Mms     ( 7686):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7459/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 11267(548KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.460ms total 110.122ms
,W/ResourcesManager( 7686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7716 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7586:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7716): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7586/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7716): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7716): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7605:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7605/cgroup.procs: No such file or directory
,I/CheckinService( 6634): Checkin interval check for package: unspecified last checkin: 1452269642715 min interval config: 0 actual interval: 5327
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7739 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6634): Checking schedule, now: 1452269648092 next: 1452269672694
I/CheckinService( 6634): active receiver: disabled
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1546): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@21e59e09
,I/GCoreNlp( 1745): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7762 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7625:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7625/cgroup.procs: No such file or directory
,W/ResourcesManager( 7762): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7762): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7762): MmsConfig.loadMmsSettings
I/Babel_SMS( 7762): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7762): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7762): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7762): MmsConfig.loadFromResources
E/Babel_SMS( 7762): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7762): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7762): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7762): startup - clean
,I/Babel   ( 7762): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7796 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7762): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7762): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7762): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7762): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7762): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7762): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7762): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7762): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7762): onServiceConnected
W/Babel   ( 7762): Attempted to change video mute state without an active call.
,I/GAv4    ( 7796): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7796):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7796):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7796): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7796): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7762): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  880): Killing 7648:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7796): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7796): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7648/cgroup.procs: No such file or directory
,I/WebViewFactory( 7796): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7796): Time to load native libraries: 2 ms (timestamps 9169-9171)
,I/LibraryLoader( 7796): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7796): Binding Chromium to main looper Looper (main, tid 1) {2ddd4dd9}
,I/LibraryLoader( 7796): Expected native library version number "",actual native library version number ""
I/chromium( 7796): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7796): Initializing chromium process, singleProcess=true
,W/art     ( 7796): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7796): ApplicationContext is null in ApplicationStatus
,W/chromium( 7796): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7796): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7796): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7796): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7796): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7796): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7796): Local Branch: 
I/Adreno-EGL( 7796): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7796): Local Patches: NONE
I/Adreno-EGL( 7796): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7796): Requires BLUETOOTH permission
,I/NSApplication( 7796): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7868 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7686:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7686/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7887 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7716:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7716/cgroup.procs: No such file or directory
,W/ResourcesManager( 7887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7907 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 23.626ms
,I/ActivityManager(  880): Killing 7739:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 22.588ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.231ms
,D/EmailService.MarketingOptInSetter( 2684): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  880): Killing 7762:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7739/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7762/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2684): bindWebServices(): registering our AIDL callback...
I/SundryService( 2684): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2684): onServiceConnected()
D/GetNotificationsWS( 2684): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2684): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2684): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2684): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2684): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2684): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2684): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7937 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2684): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2684): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2684): publish the event [tag = MOT_OTA event name = LOG]
,I/ContactLocale( 7907): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/OtaApp  ( 2684): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2684): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2684): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2684): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2684): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2684): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2684): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2684): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2684): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1415): onFinishInput()
,W/IInputConnectionWrapper( 6775): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,204
,D/WearableService( 1745): callingUid 10016, callindPid: 1745
,E/MDM     ( 1745): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1745): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6634): Restart initialization of location
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1745): No location to return for getLastLocation()
W/FusedLocationProvider( 1745): location=null
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7962 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7962): Register our PhoneStateListener
,V/SetupWizard( 7962): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7796:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7796/cgroup.procs: No such file or directory
,D/GCM     ( 1745): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1745): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  880): Explicit concurrent mark sweep GC freed 19436(965KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.571ms total 119.104ms
,E/MDM     ( 1745): [214] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6634): Restart initialization of location
D/AuthorizationBluetoothService( 1745): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1745): No location to return for getLastLocation()
W/FusedLocationProvider( 1745): location=null
,D/GCM     ( 1745): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7991 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8016 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8033 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7868:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7887:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7868/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7887/cgroup.procs: No such file or directory
,W/ResourcesManager( 8033): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 6604): Explicit concurrent mark sweep GC freed 1835(70KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 340us total 25.995ms
,I/Babel_SMS( 8033): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8033): MmsConfig.loadMmsSettings
I/Babel_SMS( 8033): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8033): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8033): MmsConfig.loadFromResources
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8033): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8033): startup - clean
,I/Babel   ( 8033): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8067 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 8067): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8067): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8067): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8033): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8033): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8033): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
D/PackageBroadcastService( 6634): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7991): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@148405b6 new=com.google.android.velvet.VelvetApplication@148405b6
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,I/PackageBroadcastService( 6634): Null package name or gms related package.  Ignoreing.
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8097 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6634): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8097): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 8033): onServiceConnected
W/Babel   ( 8033): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7991): UpdateCorporaTask done [took 169 ms] updated apps [took 169 ms] 
,I/ActivityManager(  880): Killing 7937:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 8033): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8033): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7937/cgroup.procs: No such file or directory
,V/JNIHelp ( 8033): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8033): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8033): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1745): Explicit concurrent mark sweep GC freed 97948(5MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 15MB/25MB, paused 1.314ms total 124.820ms
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f00db5)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19612c4a)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@351a97bb)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c2fc4d8)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1560d031)
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8133 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 8133): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8133): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8133): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8133): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8133): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8133): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8133): Skipping gmscore version check
,D/Finsky  ( 8133): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  880): Killing 7962:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7962/cgroup.procs: No such file or directory
,D/Finsky  ( 8133): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8182 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8016:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8016/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  880): Killing 8067:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8067/cgroup.procs: No such file or directory
,I/Icing   ( 6634): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6634): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6634): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7991:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7991/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  880): Killing 7907:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7907/cgroup.procs: No such file or directory
,I/CheckinService( 6634): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311818, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-387, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1745): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1ede07fa, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): send {3053c1ab, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): send {1aabd77b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {1ede07fa, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [22ms]
,V/AlarmManager(  880): done {3053c1ab, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [38ms]
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  880): done {1aabd77b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [62ms]
,I/CheckinService( 6634): Checkin interval check for package: unspecified last checkin: 1452269642715 min interval config: 0 actual interval: 44939
,I/EventLogService( 6634): Aggregate from 1452269638371 (log), 1452267831911 (data)
,I/CheckinService( 6634): Checking schedule, now: 1452269687679 next: 1452269672694
I/CheckinService( 6634): active receiver: enabled
,I/CheckinService( 6634): Preparing to send checkin request
,I/EventLogService( 6634): Accumulating logs since 1452269687668
,I/CheckinRequestBuilder( 6634): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6634): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  880): Explicit concurrent mark sweep GC freed 14712(765KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.385ms total 114.795ms
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8224 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8224): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8224): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8224): VM with version 2.1.0 has multidex support
I/MultiDex( 8224): install
I/MultiDex( 8224): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8224): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8224): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8224): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4727869: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8224): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1745): callingUid 10016, callindPid: 1745
,E/MDM     ( 1745): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1745): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6634): Restart initialization of location
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1745): No location to return for getLastLocation()
W/FusedLocationProvider( 1745): location=null
,I/art     ( 8224): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8224): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8224): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f81000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f81000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
,D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5554960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7553478, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb75aa7a0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb766cc98, idLength=0xb136a730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=4077440225
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb757baf0
D/DrmWidevineDash(  296): message_length=1591, signature=0xb75589a0, signature_length=2973148948
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f81000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f81000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbe9434e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb75a7f98, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76129c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb766ccb8, idLength=0xb136a730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  296): PrepareKeyRequest: nonce=3456156502
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb753eb30
D/DrmWidevineDash(  296): message_length=1626, signature=0xb7558c60, signature_length=2973148948
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8277): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8277): dex2oat took 68.721ms (threads: 4)
,I/Adreno-EGL( 8224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8224): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8224): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8224): Local Branch: 
I/Adreno-EGL( 8224): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8224): Local Patches: NONE
I/Adreno-EGL( 8224): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8224): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8224): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8224): Local Branch: 
I/Adreno-EGL( 8224): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8224): Local Patches: NONE
I/Adreno-EGL( 8224): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8224): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8224): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8224): Local Branch: 
I/Adreno-EGL( 8224): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8224): Local Patches: NONE
I/Adreno-EGL( 8224): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8224): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8224): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8224): Local Branch: 
I/Adreno-EGL( 8224): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8224): Local Patches: NONE
I/Adreno-EGL( 8224): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6634): Classify the device as Phone.
,I/CheckinTask( 6634): Sending checkin request (9520 bytes)
,I/CheckinRequestBuilder( 6634): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6634): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6634): Classify the device as Phone.
,I/CheckinTask( 6634): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6634): Checking schedule, now: 1452269690704 next: 1452870827697
I/CheckinService( 6634): active receiver: disabled
,D/CheckinService( 6634): Recording last checkin time for package unspecified as 1452269690724
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8295 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 26.299ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.356ms
,D/PhoneMonitor( 8295): Register our PhoneStateListener
,V/SetupWizard( 8295): Connected to Gservices successfully
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 24.311ms
,D/GCM     ( 1745): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 8133:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  880): Killing 8097:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8133/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8097/cgroup.procs: No such file or directory
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8333 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@bf4abbe
,I/GCoreNlp( 1745): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8363 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8385 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8182:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_8182/cgroup.procs: No such file or directory
,W/ResourcesManager( 8033): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8033): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8385): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8419 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8295:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8295/cgroup.procs: No such file or directory
,W/asset   ( 8419): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8419): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8419): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8419): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6634): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6634): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6634): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@148405b6 new=com.google.android.velvet.VelvetApplication@148405b6
I/UpdateIcingCorporaServi( 8333): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8447 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8333): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,I/art     (  880): Explicit concurrent mark sweep GC freed 18294(959KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.295ms total 122.843ms
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8475 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8224:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_8224/cgroup.procs: No such file or directory
,D/Finsky  ( 8475): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8475): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8475): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8475): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8475): Skipping gmscore version check
D/Finsky  ( 8475): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8475): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  880): Killing 8363:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8363/cgroup.procs: No such file or directory
,D/Finsky  ( 8475): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8475): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6634): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6634): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8419:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8419/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {3dadc8a6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8523 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [94ms]
,I/GAv4    ( 8523): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8523):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8523):   adb logcat -s GAv4
,W/GAv4    ( 8523): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8523): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8523): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {3dadc8a6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [245ms]
,I/ActivityManager(  880): Killing 8333:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8333/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 8033:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8033/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1415): run()
,I/Keyboard.Facilitator( 1415): flushDynamicLanguageModels()
,I/ConfigService( 1745): onCreate
,I/ConfigService( 1745): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311450, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-445, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 4
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): TAP version 13
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # multiplex can send data
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 1 String should be length:200
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # basic
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): ok 2 sane
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # another
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2d5dc932, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {2d5dc932, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/jxcore-log( 6775): ok 3 sane
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 4 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 5 null
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 6 (unnamed assert)
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 7 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 8 should not throw
I/jxcore-log( 6775): 
I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): ok 9 (unnamed assert)
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 10 (unnamed assert)
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 11 should not throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 12 should be equal
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 13 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 14 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # failed to get mobile documents path
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 15 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 16 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 17 should be equal
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 18 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #init should register the networkChanged event
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 19 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on null device name
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 20 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 21 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 22 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 23 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on negative port
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 24 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should throw on too large port
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): ok 25 should throw
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 26 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 27 should be equal
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 28 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6775): 
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311334, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2724, POWER_SUPPLY_CHARGE_COUNTER=-477, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 29 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 30 should be equal
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 31 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 32 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 33 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 34 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 35 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 36 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 37 should be equal
I/jxcore-log( 6775): 
I/jxcore-log( 6775): ok 38 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 39 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 40 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): ok 41 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 42 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 43 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): ok 44 should be equal
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
,I/jxcore-log( 6775): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6775): 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6775): # teardown
I/jxcore-log( 6775): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963150.6775
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963150.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963150.6775
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963150.6775","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963150.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963150.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@87f4b726 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@87f4b726 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
,D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6775): start: OK
I/wpa_supplicant( 1436): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): discovery change broadcast true
,I/jxcore-log( 6775): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
,D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
,D/WifiP2pService(  880): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
,D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
,I/jxcore-log( 6775): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963279.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963279.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963279.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963279.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963279.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963279.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ce4aa80e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ce4aa80e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 6775): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  880): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
D/WifiP2pService(  880): remove client information from framework
I/jxcore-log( 6775): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963329.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963329.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963329.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963329.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963329.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963329.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df596996 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@df596996 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/WifiP2pService(  880): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
I/jxcore-log( 6775): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
I/jxcore-log( 6775): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963362.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963362.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963362.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963362.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963362.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963362.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5d9f2fdc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5d9f2fdc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
I/jxcore-log( 6775): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/WifiP2pService(  880): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  880): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
I/jxcore-log( 6775): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963398.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963398.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963398.6775
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963398.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963398.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963398.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bde5bc8a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bde5bc8a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
I/jxcore-log( 6775): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  880): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
D/WifiP2pService(  880): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,I/jxcore-log( 6775): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963429.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963429.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963429.6775
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963429.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963429.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963429.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a22e3d4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3a22e3d4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  880): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
,I/jxcore-log( 6775): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
,I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
,D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
I/jxcore-log( 6775): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963464.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963464.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963464.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963464.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963464.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963464.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9c13c96 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9c13c96 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
D/WifiP2pService(  880): discovery change broadcast true
I/jxcore-log( 6775): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/WifiP2pService(  880): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6775): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963494.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963494.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963494.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963494.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963494.6775","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963494.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f5fe11d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f5fe11d0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6775): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
D/WifiP2pService(  880): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
,D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
I/jxcore-log( 6775): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963523.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963523.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
,I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
,D/TCMD    (  489): NL - Read 56 bytes from update socket.
D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-ADDED 1 9e
I/wpa_supplicant( 1436): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-80
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963523.6775
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963523.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: 3-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 128
D/WifiP2pService(  880):  grpcapab: 9
D/WifiP2pService(  880):  devcapab: 4
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: 3-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 128
D/WifiP2pService(  880):  grpcapab: 9
D/WifiP2pService(  880):  devcapab: 4
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963523.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963523.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@60e2a69e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@60e2a69e target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
I/jxcore-log( 6775): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
I/wpa_supplicant( 1436): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  880): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
,D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6775): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
I/wpa_supplicant( 1436): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Failed to set discovery mode to BLE
D/WifiP2pService(  880): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setDiscoveryMode: Mode set to WIFI
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963555.6775
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963555.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6775): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): start: OK
I/io.jxcore.node.ConnectionHelper( 6775): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452269963555.6775
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6775): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963555.6775","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452269963555.6775","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452269963555.6775","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9e780e54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9e780e54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): start: OK
I/jxcore-log( 6775): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6775): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6775): onServerStopped
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6775): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6775): stop: Stopping services
I/wpa_supplicant( 1436): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  294): Event received = P2P: Reject scan trigger 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: NOT_INITIALIZED
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  880): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6775): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6775): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6775): setState: NOT_STARTED
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1436): P2P-FIND-STOPPED 
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  294): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6775): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6775): 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,I/jxcore-log( 6775): # setup
I/jxcore-log( 6775): 
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.,thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6775): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6775): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6775): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6775): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6775): Service requests cleared successfully
,I/wpa_supplicant( 1436): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-80
D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  294): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/TCMD    (  489): NL - Read 56 bytes from update socket.
,D/TCMD    (  489): NL - message type is RTM_NEWLINK
D/TCMD    (  489): Listening for incoming client connection request
D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: 3-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 128
D/WifiP2pService(  880):  grpcapab: 9
D/WifiP2pService(  880):  devcapab: 4
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: 3-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 128
D/WifiP2pService(  880):  grpcapab: 9
D/WifiP2pService(  880):  devcapab: 4
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=253, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311831, SEQNUM=4535, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-468, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/wpa_supplicant( 1436): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  294): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/MDMCTBK (  294): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310889, SEQNUM=4537, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4338, POWER_SUPPLY_CHARGE_COUNTER=-63, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {152cdf67, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {152cdf67, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312048, SEQNUM=4542, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-66, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=247, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312052, SEQNUM=4543, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-106, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1d5be94c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  880): done {1d5be94c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [82ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3dffad95, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {3dffad95, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [18ms]
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [103ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=243, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311694, SEQNUM=4546, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-867, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=242, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311395, SEQNUM=4547, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-42, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=242, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311694, SEQNUM=4548, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-71, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=242, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312264, SEQNUM=4549, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-35, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=241, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311672, SEQNUM=4550, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {152cdf67, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): send {25a827ea, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,I/ProcessStatsService(  880): Prepared write state in 11ms
,V/AlarmManager(  880): done {152cdf67, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [58ms]
,V/AlarmManager(  880): done {25a827ea, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [70ms]
,V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [87ms]
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-17-03.bin
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=240, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311378, SEQNUM=4553, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2511): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8665): 
D/AndroidRuntime( 8665): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8665): CheckJNI is OFF
D/AndroidRuntime( 8665): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10423 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6775:com.test.thalitest/u0a423 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{3a2d842d com.example.hello/10420} due to missing metadata
W/InputDispatcher(  880): channel '105121cd com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  880): channel '105121cd com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  880): WIN DEATH: Window{105121cd u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  880): Attempted to unregister already unregistered input channel '105121cd com.test.thalitest/com.test.thalitest.MainActivity (server)'
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{384a7f6e u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{126fea9b 6775:com.test.thalitest/u0a423}, curProc for 6775: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10423 user=0: pkg removed
I/art     ( 3313): Explicit concurrent mark sweep GC freed 11721(2MB) AllocSpace objects, 33(528KB) LOS objects, 39% free, 7MB/12MB, paused 2.161ms total 44.409ms
W/GeofencerStateMachine( 1745): Ignoring removeGeofence because network location is disabled.
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1415): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1415): run()
I/Decoder ( 1415): createOrResetDecoder
D/VoicemailCleanupService( 8385): Cleaning up data for package: com.test.thalitest
I/art     ( 1572): Explicit concurrent mark sweep GC freed 5063(312KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 469us total 120.523ms
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8697 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  880): Explicit concurrent mark sweep GC freed 28804(2MB) AllocSpace objects, 11(264KB) LOS objects, 33% free, 20MB/30MB, paused 1.868ms total 162.718ms
I/art     (  880): WaitForGcToComplete blocked for 111.293ms for cause Explicit
I/ConfigService( 1745): onCreate
W/asset   ( 8697): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8697): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8697): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8697): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1415): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1415): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1415): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1415): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1415): run()
I/StatsUtilsManager( 1415): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1415): shouldRecordStats() = Too Soon
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8725 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  880): Killing 8447:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 7913(426KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.194ms total 197.609ms
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8447/cgroup.procs: No such file or directory
I/Launcher( 1572): Deferring update until onResume
W/ContextImpl( 8725): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6634): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6634): Reading stored module config
D/AccountUtils( 6634): Clearing selected account for com.test.thalitest
D/AndroidRuntime( 8665): Shutting down VM
D/ChimeraCfgMgr( 6634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6634): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6634): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6634): App measurement is starting up, version: 8489
I/GMPM-SVC( 6634): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6634): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8752 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  880): send {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {2fca7717, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {3c47e704, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {418c4ed, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {6da3f22, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  880): done {2f2d4f2a, *alarm*:android.intent.action.TIME_TICK} [37ms]
I/Icing   ( 6634): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 6634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6634): Module APK com.google.android.play.games already loaded
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@148405b6 new=com.google.android.velvet.VelvetApplication@148405b6
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8778 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.915ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.197ms
W/BaseAppContext( 6634): Using Auth Proxy for data requests.
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.391ms
E/BaseAppContext( 6634): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/ConnectivityService(  880): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  880): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6634): CM callback handler got msg 524290
W/BaseAppContext( 6634): Using Auth Proxy for data requests.
W/BaseAppContext( 6634): Using Auth Proxy for data requests.
W/BaseAppContext( 6634): Using Auth Proxy for data requests.
E/SQLiteLog( 6634): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6634): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6634): Process: com.google.android.gms, PID: 6634
E/AndroidRuntime( 6634): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6634): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6634): 	at com.google.android.gms.people.c.f.b(SourceFile:3345)
E/AndroidRuntime( 6634): 	at com.google.android.gms.people.c.f.g(SourceFile:3316)
E/AndroidRuntime( 6634): 	at com.google.android.gms.people.service.bg.f.a(SourceFile:273)
E/AndroidRuntime( 6634): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6634): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6634): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6634): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6634): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6634): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 6634): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6634): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6634): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6634): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/SQLiteDatabase( 6634): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 6634): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 6634): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 6634): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 6634): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 6634): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6634): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6634): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 6634): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 6634): Runtime exception while performing operation
E/ClearPendingStateOp( 6634): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 6634): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearPendingStateOp( 6634): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/ClearPendingStateOp( 6634): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 6634): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 6634): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6634): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6634): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6634): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6634): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 6634): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6634): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 6634): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
F/ClearPendingStateOp( 6634): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 6634): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
F/ClearPendingStateOp( 6634): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 6634): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 6634): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6634): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6634): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6634): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6634): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6634): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 6634): Sending signal. PID: 6634 SIG: 9
E/DropBoxManagerService(  880): Can't write: system_app_wtf
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
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
E/native  ( 1415): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1415): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
D/WifiService(  880): Client connection lost with reason: 4
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@be6bcff)
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Icing   ( 1745): Error while brokering service: android.os.DeadObjectException
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8818 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  880): Process com.google.android.gms (pid 6634) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms

```
