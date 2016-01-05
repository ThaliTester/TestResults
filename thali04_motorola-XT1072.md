#### Test 54970261aa56788_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 6555): 
D/AndroidRuntime( 6555): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6555): CheckJNI is OFF
D/AndroidRuntime( 6555): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6574 uid=10414 gids={50414, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6555): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6574): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6574): Time to load native libraries: 6 ms (timestamps 7465-7471)
,I/LibraryLoader( 6574): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6574): Binding Chromium to main looper Looper (main, tid 1) {25efec49}
,I/LibraryLoader( 6574): Expected native library version number "",actual native library version number ""
I/chromium( 6574): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6574): Initializing chromium process, singleProcess=true
,W/art     ( 6574): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6574): ApplicationContext is null in ApplicationStatus
,W/chromium( 6574): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6574): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6574): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6574): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6574): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6574): Local Branch: 
I/Adreno-EGL( 6574): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6574): Local Patches: NONE
I/Adreno-EGL( 6574): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{3e24c4d1 u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12e8eb3c:true
,W/art     ( 6574): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6574): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6574): CordovaWebView is running on device made by: motorola
I/art     (  880): Explicit concurrent mark sweep GC freed 41746(1980KB) AllocSpace objects, 2(215KB) LOS objects, 33% free, 20MB/30MB, paused 1.465ms total 131.292ms
W/art     ( 6574): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6574): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6574): Render dirty regions requested: true
D/Atlas   ( 6574): Validating map...
W/chromium( 6574): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6574): Initialized EGL, version 1.4
D/OpenGLRenderer( 6574): Enabling debug mode 0
I/Keyboard.Facilitator( 1413): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1192
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s119ms (total +1s192ms)
W/IInputConnectionWrapper( 6574): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6574): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6574): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6574): Cannot call determinedVisibility() - never saw a connection for the pid: 6574
D/JsMessageQueue( 6574): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6574): JniHelper::setJavaVM(0xb8630310), pthread_self() = -1197738104
,D/JX-Cordova( 6574): jxcore cordova android initializing
,W/jxcore-log( 6574): Initializing JXcore engine
W/jxcore-log( 6574): JXcore engine is ready
,W/jxcore-log( 6574): Starting JXcore engine
,W/.test.thalitest( 6574): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10414 path="socket:[9549]" dev="sockfs" ino=9549 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6574): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10414 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6574): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10414 path="socket:[7536]" dev="sockfs" ino=7536 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6574): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10414 path="socket:[27878]" dev="sockfs" ino=27878 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6574): Platform android
W/jxcore-log( 6574): 
,W/jxcore-log( 6574): Process ARCH arm
W/jxcore-log( 6574): 
,I/jxcore-log( 6574): JXcore Cordova bridge is ready!
I/jxcore-log( 6574): 
W/jxcore-log( 6574): JXcore engine is started
,I/chromium( 6574): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6574): Toggling radios to true
I/jxcore-log( 6574): 
,D/BluetoothAdapter( 6574): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6574, uid=10414
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6574): Radios toggled
I/jxcore-log( 6574): 
,I/wpa_supplicant( 1422): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  295): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  880): InitialState.processMessage what=4,
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1422): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1422): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  880):  0
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1422): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
D/TCMD    (  483): Listening for incoming client connection request
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,V/NativeCrypto( 1709): Read error: ssl=0xb89146d0: I/O error during system call, Connection timed out
V/NativeCrypto( 1709): SSL shutdown failed: ssl=0xb89146d0: I/O error during system call, Broken pipe
D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6637 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 122603
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1422): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1422): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1422): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6637): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  292): Clearing all IP addresses on wlan0
D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6637): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6637): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6637): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6637): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6637): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6637): MmsConfig.loadFromResources
E/Babel_SMS( 6637): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6637): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6637): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6637): startup - clean
,I/Babel   ( 6637): deleted: false for 0
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  880): [1,452,019,333,602 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1422): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1422): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b4c83ed sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6674 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6674): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
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
I/wpa_supplicant( 1422): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
,D/Tethering(  880):  7
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1422): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1422): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
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
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  295): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  295): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): get_property_value, Enter
I/MDMCTBK (  295): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  295): get_property_value, Exit
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1213367008
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 6637): Unrecognized profile 2130706433 for video/avc
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  292): Setting iface cfg
E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 1422): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1422): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ec3e0bb target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ec3e0bb target=com.android.internal.util.StateMachine$SmHandler }
,W/AudioCapabilities( 6637): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6637): Unsupported mime video/mpeg2
,I/ActivityManager(  880): Killing 6321:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/VideoCapabilities( 6637): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6637): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6637): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6637): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6637): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6696): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6696): version 5.5.6 starting
E/DHCPCD  ( 6696): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6696): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6696): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6321/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 6366:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6696): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6696): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6696): wlan0: sending REQUEST (xid 0x16d662ee), next in 3.19 seconds
,I/DHCPCD  ( 6696): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6366/cgroup.procs: No such file or directory
,I/vclib   ( 6637): onServiceConnected
W/Babel   ( 6637): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6696): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6696): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6696): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/DHCPCD  ( 6696): wlan0: adding default route via 192.168.1.1
D/TCMD    (  483): Listening for incoming client connection request
D/DHCPCD  ( 6696): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6696): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/global frequency( 2788): no tags to log
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin ( 2788): publish the event [tag = MOT_CHECKIN event name = LOG]
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 18:42:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452019334830], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452019334810]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 2788): Explicit concurrent mark sweep GC freed 17579(916KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.236ms total 81.901ms
,D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 55291(3MB) AllocSpace objects, 36(1235KB) LOS objects, 39% free, 7MB/12MB, paused 763us total 44.763ms
,I/BSUtils ( 2788): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2788): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  880): Explicit concurrent mark sweep GC freed 41941(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.611ms total 125.199ms
,D/BSUtils ( 2788): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2788): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2788): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2788): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2788): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2788): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2788): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2788): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2788): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2788): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1463): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6751 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1463): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1463): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2788): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2788): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2788): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2788): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2788): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2788): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2788): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2788): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2788): [debug] > CusSM.onRadioDown
,I/MusicStore( 6751): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6751): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6751): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6751): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6751): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6751): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6751): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {283da01, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [29ms]
,W/ActivityThread( 6751): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6751): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2342a235: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6751): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6751): GMSCore installation verified
,I/ConfigStore( 6751): Config Database version: 1
,I/MediaRouter( 6751): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6751): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6751): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6793 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6751): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6751): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6151:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6151/cgroup.procs: No such file or directory
,V/Mms     ( 6793): mnc/mcc: 
V/Mms     ( 6793): tag: int value: recipientLimit - 20
V/Mms     ( 6793): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6793): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6793): tag: int value: maxSubjectLength - 80
V/Mms     ( 6793): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6793): tag: bool value: enableGroupMms - false
V/Mms     ( 6793):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6793): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6820 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6229:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6229/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,D/PhoneMonitor( 6820): Register our PhoneStateListener
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1463): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2788): now: 196633 ,futureTime: 9223372036854775807
D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2788): now: 196633 ,futureTime: 9223372036854775807
D/PollingManager( 2788): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2788): now: 196633 ,futureTime: 9223372036854775807
D/OtaApp  ( 2788): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1463): now: 196635 ,futureTime: 86473529
D/Central_PollingManager( 1463): Polling alarm set to expire at: 86473529 Current Time: 196635
,D/OtaApp  ( 2788): [debug] > PollingManagerService, now: 196640 ,futureTime: 77523951
D/OtaApp  ( 2788): [debug] > Polling alarm set to expire at: 77523951 Current Time: 196641
,I/NetworkMonitor( 6751): type=WIFI subType= reason=null isConnected=true
I/art     ( 1463): Explicit concurrent mark sweep GC freed 4900(218KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 768us total 30.126ms
,D/MMApiProvisionService( 2788): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2788): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2788): createDeviceIdOrLogin update_device
,D/Checkin ( 2788): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2788): Not proxy app, so login/provision not allowed
,D/MobileConnectivityChangeReceiver( 6820): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6820): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MMApiProvisionService( 2788): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2788): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2788): createDeviceIdOrLogin update_device
,D/Checkin ( 2788): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2788): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2788): set mOutstandingReq to true.
I/ Nonce  ( 2788):  Nonce getNonce 
I/ Nonce  ( 2788):  Nonce Request 
I/ Nonce  ( 2788):  Nonce execute Request 
,D/MMApiWebService( 2788): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/ActivityManager(  880): Killing 6637:com.google.android.talk/u0a70 (adj 15): empty #7
,D/MMApiProvisionService( 2788): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2788): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2788): createDeviceIdOrLogin update_device
,D/Checkin ( 2788): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2788): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2788): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2788): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2788): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2788): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2788): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2788): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2788): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2788): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2788): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/MMApiWebService( 2788): generating token using payload instead of using session token
,I/art     ( 2788): Explicit concurrent mark sweep GC freed 11435(659KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/18MB, paused 1.210ms total 57.251ms
,D/ Nonce  ( 2788):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2788): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2788): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6637/cgroup.procs: No such file or directory
,D/OtaApp  ( 2788): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     (  880): Explicit concurrent mark sweep GC freed 11473(520KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.564ms total 113.117ms
,I/CheckinService( 6440): Checkin interval check for package: unspecified last checkin: 1452019254123 min interval config: 0 actual interval: 84089
,I/CheckinService( 6440): Disabling old GoogleServicesFramework version
,I/CheckinService( 6440): Checking schedule, now: 1452019338244 next: 1452019284096
I/CheckinService( 6440): active receiver: enabled
,I/iu.SyncManager( 6440): SYNC; picasa accounts
,D/NetworkLogImpl( 6440): Loaded NetworkSpeedPredictor
,I/CheckinService( 6440): Preparing to send checkin request
,I/iu.Environment( 6440): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6440): Accumulating logs since 1452019250817
,I/iu.UploadsManager( 6440): num queued entries: 0
I/iu.UploadsManager( 6440): num updated entries: 0
I/iu.SyncManager( 6440): NEXT; no task
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6865 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6440): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6440): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6892 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 22.819ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 18.911ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.758ms
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6909 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6892): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6892): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6909): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ Nonce  ( 2788):  Nonce Reponse 
D/        ( 2788): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"091f4257-d02e-46da-85a1-ca3a2eeb95e6"}
D/MMApiWSBase( 2788): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/MultiDex( 6892): VM with version 2.1.0 has multidex support
I/MultiDex( 6892): install
I/MultiDex( 6892): VM has multidex support, MultiDex support library is disabled.
I/ Nonce  ( 2788):  Nonce Handle Reponse 
D/MMApiProvisionService( 2788): mOutstandingReq set to false
,V/JNIHelp ( 6892): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6892): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6892): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@390eec12: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6892): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6892): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6892): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 6909): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6909): MmsConfig.loadMmsSettings
,D/MMApiProvisionService( 2788):  pTime 1451923699777 sExp 172742 cTime 1452019339152 tTime 1452096441777
D/MMApiProvisionService( 2788):  No login Required 
,I/Babel_SMS( 6909): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6909): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6909): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6909): MmsConfig.loadFromResources
,E/Babel_SMS( 6909): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6909): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6892): Install completed successfully. count=14 extracted=0
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
,W/Settings( 6909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6909): startup - clean
,I/Babel   ( 6909): deleted: false for 0
,D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/art     ( 6909): Suspending all threads took: 16.065ms
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
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e77000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e77000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb0d81960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb81e3bd0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb820b4e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8328d28, idLength=0xb55b0730
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
D/WVCdm   (  297): PrepareKeyRequest: nonce=1842178584
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb824d930
D/DrmWidevineDash(  297): message_length=1591, signature=0xb824adf8, signature_length=3042641684
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6949 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2788): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2788): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6909): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6909): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities( 6909): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6909): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6909): onServiceConnected
W/Babel   ( 6909): Attempted to change video mute state without an active call.
,I/dex2oat ( 6967): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/Babel   ( 6909): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6674:com.motorola.context/u0a8 (adj 15): empty #7
,I/dex2oat ( 6967): dex2oat took 129.312ms (threads: 4)
,I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6674/cgroup.procs: No such file or directory
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e77000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e77000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbee4d4e0
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb82dd608, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb824f090, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8328d68, idLength=0xb0d81730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=719868156
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb824a7b8
D/DrmWidevineDash(  297): message_length=1626, signature=0xb820d190, signature_length=2966951700
W/ContextImpl( 6949): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6949): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6949): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6949):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6949):   adb logcat -s GAv4
,W/GAv4    ( 6949): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6949): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6949): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6949): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6949): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6949): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6949): Time to load native libraries: 2 ms (timestamps 9465-9467)
,I/LibraryLoader( 6949): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6949): Binding Chromium to main looper Looper (main, tid 1) {1be67dc2}
,I/LibraryLoader( 6949): Expected native library version number "",actual native library version number ""
,I/chromium( 6949): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6949): Initializing chromium process, singleProcess=true
W/art     ( 6949): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6949): ApplicationContext is null in ApplicationStatus
,W/chromium( 6949): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6949): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6949): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6949): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6949): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6949): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6949): Local Branch: 
I/Adreno-EGL( 6949): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6949): Local Patches: NONE
I/Adreno-EGL( 6949): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6949): Requires BLUETOOTH permission
,I/NSApplication( 6949): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7029 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6751:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6751/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6892): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6892): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6892): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6892): Local Branch: 
I/Adreno-EGL( 6892): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6892): Local Patches: NONE
I/Adreno-EGL( 6892): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7052 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6793:com.android.mms/u0a23 (adj 15): empty #7
,I/CheckinRequestBuilder( 6440): Classify the device as Phone.
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6793/cgroup.procs: No such file or directory
,W/ResourcesManager( 7052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6440): Sending checkin request (9512 bytes)
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7076 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7101 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6865:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7076): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 6820:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/CheckinRequestBuilder( 6440): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6865/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6820/cgroup.procs: No such file or directory
,E/ActivityThread( 6440): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  880): Explicit concurrent mark sweep GC freed 13065(658KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.713ms total 114.694ms
,I/MusicStore( 7101): Database version: 120
,I/art     ( 6398): Explicit concurrent mark sweep GC freed 1576(68KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 409us total 27.642ms
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7101): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6440): Classify the device as Phone.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7101): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7101): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 6440): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6440): Checking schedule, now: 1452019342719 next: 1452620479711
I/CheckinService( 6440): active receiver: disabled
,D/CheckinService( 6440): Recording last checkin time for package unspecified as 1452019342731
,I/ActivityManager(  880): Killing 6909:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 7101): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6909/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {2d6d3efb, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/JNIHelp ( 7101): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7101): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7101): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2342a235: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7101): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7101): GMSCore installation verified
,I/ConfigStore( 7101): Config Database version: 1
,I/MediaRouter( 7101): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7101): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7101): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Killing 6949:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_6949/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7157 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NetworkMonitor( 7101): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 7101): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7101): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7157): mnc/mcc: 
,V/Mms     ( 7157): tag: int value: recipientLimit - 20
V/Mms     ( 7157): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7157): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7157): tag: int value: maxSubjectLength - 80
V/Mms     ( 7157): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7157): tag: bool value: enableGroupMms - false
,V/Mms     ( 7157):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  880): Killing 7029:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7029/cgroup.procs: No such file or directory
,W/ResourcesManager( 7157): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7193 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7076:android.process.acore/u0a7 (adj 13): empty #7
,D/PhoneMonitor( 7193): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7076/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7193): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7193): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7052:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309088, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14222, POWER_SUPPLY_CHARGE_COUNTER=-702, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7052/cgroup.procs: No such file or directory
,I/CheckinService( 6440): Checkin interval check for package: unspecified last checkin: 1452019342731 min interval config: 0 actual interval: 1630
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7218 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/CheckinService( 6440): Checking schedule, now: 1452019344486 next: 1452019372711
I/CheckinService( 6440): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7243 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7101:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7101/cgroup.procs: No such file or directory
,W/ResourcesManager( 7243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7243): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7243): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7243): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7243): MmsConfig.loadFromDatabase
,I/jxcore-log( 6574): Test app app.js loaded
I/jxcore-log( 6574): 
,I/chromium( 6574): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Babel_SMS( 7243): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7243): MmsConfig.loadFromResources
,E/Babel_SMS( 7243): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7243): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7243): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7243): startup - clean
,I/Babel   ( 7243): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7285 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.053ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.960ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.476ms
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7243): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7243): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7243): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7243): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7285): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7243): onServiceConnected
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/Babel   ( 7243): Attempted to change video mute state without an active call.
W/ContextImpl( 7285): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7285): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7285): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7285):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7285):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7285): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7285): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7285): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7285): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7243): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7157:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7157/cgroup.procs: No such file or directory
,I/WebViewFactory( 7285): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7285): Time to load native libraries: 2 ms (timestamps 4690-4692)
,I/LibraryLoader( 7285): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7285): Binding Chromium to main looper Looper (main, tid 1) {1be67dc2}
I/LibraryLoader( 7285): Expected native library version number "",actual native library version number ""
,I/chromium( 7285): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7285): Initializing chromium process, singleProcess=true
W/art     ( 7285): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7285): ApplicationContext is null in ApplicationStatus
,W/chromium( 7285): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7285): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7285): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7285): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7285): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7285): Local Branch: 
I/Adreno-EGL( 7285): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7285): Local Patches: NONE
I/Adreno-EGL( 7285): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7285): Requires BLUETOOTH permission
,I/NSApplication( 7285): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7354 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7193:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7193/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7373 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7218:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7218/cgroup.procs: No such file or directory
,W/ResourcesManager( 7373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7393 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7285:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7393): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7243:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2788): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7285/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7243/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 12236(635KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.521ms total 116.385ms
,D/GetNotificationsWS( 2788): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2788): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2788): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2788): onServiceConnected()
,D/GetNotificationsWS( 2788): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2788): unbindWebServices(): un-registering our AIDL callback...
V/AlarmManager(  880): done {283da01, *walarm*:com.google.android.intent.action.SEND_IDLE} [10137ms]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7425 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2788): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7425): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7425): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7425): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7425): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7425): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7425): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7425): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7425): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7425): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2342a235: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7425): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7425): GMSCore installation verified
,I/ConfigStore( 7425): Config Database version: 1
,I/MediaRouter( 7425): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7425): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7425): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7425): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7456 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7425): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7425): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6892:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7456): mnc/mcc: 
V/Mms     ( 7456): tag: int value: recipientLimit - 20
,V/Mms     ( 7456): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7456): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7456): tag: int value: maxSubjectLength - 80
V/Mms     ( 7456): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7456): tag: bool value: enableGroupMms - false
V/Mms     ( 7456):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6892/cgroup.procs: No such file or directory
,W/ResourcesManager( 7456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7482 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7354:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7482): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7354/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7482): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7482): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7373:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7373/cgroup.procs: No such file or directory
,I/CheckinService( 6440): Checkin interval check for package: unspecified last checkin: 1452019342731 min interval config: 0 actual interval: 4939
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7501 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6440): Checking schedule, now: 1452019347717 next: 1452019372711
,I/CheckinService( 6440): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7518 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7393:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7393/cgroup.procs: No such file or directory
,W/ResourcesManager( 7518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7518): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7518): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7518): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7518): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7518): MmsConfig.loadFromResources
,E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7518): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7518): startup - clean
,I/Babel   ( 7518): deleted: false for 0
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7554 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@12521f47
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7518): Unsupported mime audio/amr-wb-plus
,I/Launcher( 1570): Deferring update until onResume
W/VideoCapabilities( 7518): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7518): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7518): onServiceConnected
,W/Babel   ( 7518): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7554): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7554): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7554):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7554):   adb logcat -s GAv4
,W/ContextImpl( 7554): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7554): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7554): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7554): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7518): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7425:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7554): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7554): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7425/cgroup.procs: No such file or directory
,I/WebViewFactory( 7554): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7554): Time to load native libraries: 2 ms (timestamps 7971-7973)
,I/LibraryLoader( 7554): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7554): Binding Chromium to main looper Looper (main, tid 1) {1be67dc2}
,I/LibraryLoader( 7554): Expected native library version number "",actual native library version number ""
I/chromium( 7554): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7554): Initializing chromium process, singleProcess=true
,W/art     ( 7554): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7554): ApplicationContext is null in ApplicationStatus
,W/chromium( 7554): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7554): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7554): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7554): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7554): Local Branch: 
I/Adreno-EGL( 7554): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7554): Local Patches: NONE
I/Adreno-EGL( 7554): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7554): Requires BLUETOOTH permission
,I/NSApplication( 7554): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7622 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7456:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7456/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 17380(875KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.657ms total 113.225ms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7641 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7482:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  321): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 24.758ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.618ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.358ms
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7482/cgroup.procs: No such file or directory
,W/ResourcesManager( 7641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7661 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7518:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7661): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7501:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7518/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2788): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7501/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2788): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2788): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2788): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2788): onServiceConnected()
D/GetNotificationsWS( 2788): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2788): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2788): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2788): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2788): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2788): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7695 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2788): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2788): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2788): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2788): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2788): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2788): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2788): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2788): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2788): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2788): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2788): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2788): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
,W/IInputConnectionWrapper( 6574): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,193
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6440): Restart initialization of location
D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1709): No location to return for getLastLocation()
W/FusedLocationProvider( 1709): location=null
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7723 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7723): Register our PhoneStateListener
,V/SetupWizard( 7723): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 7554:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7554/cgroup.procs: No such file or directory
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/AlarmManager(  880): done {2d6d3efb, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [7805ms]
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7748 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7775 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7792 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7622:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7641:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7622/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7641/cgroup.procs: No such file or directory
,W/ResourcesManager( 7792): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7792): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7792): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7792): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7792): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7792): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7792): MmsConfig.loadFromResources
,E/Babel_SMS( 7792): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7792): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7792): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7792): startup - clean
,I/Babel   ( 7792): deleted: false for 0
,W/VideoCapabilities( 7792): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7829 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7792): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7792): Unsupported mime video/mpeg2
,W/asset   ( 7829): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7829): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7829): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7829): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7792): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7792): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6440): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7748): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b84be8b new=com.google.android.velvet.VelvetApplication@2b84be8b
,I/PackageBroadcastService( 6440): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7857 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6440): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 7792): onServiceConnected
W/Babel   ( 7792): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7748): UpdateCorporaTask done [took 166 ms] updated apps [took 165 ms] 
I/ActivityManager(  880): Killing 7723:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7792): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7792): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7792): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7723/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7894 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7695:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 13475(654KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.821ms total 127.624ms
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7695/cgroup.procs: No such file or directory
,D/Finsky  ( 7894): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7894): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7894): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7894): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7894): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7894): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7894): Skipping gmscore version check
,D/Finsky  ( 7894): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7894): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7775:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7775/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6440): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6440): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6440): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7829:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7829/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7748:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7748/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/CheckinService( 6440): Done disabling old GoogleServicesFramework version
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
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309604, SEQNUM=4548, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-794, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
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
,I/ClearcutLoggerApiImpl( 1709): disconnect managed GoogleApiClient
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {21f13006, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {179f8c16, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {21f13006, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [21ms]
,V/AlarmManager(  880): done {179f8c16, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [30ms]
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/CheckinService( 6440): Checkin interval check for package: unspecified last checkin: 1452019342731 min interval config: 0 actual interval: 45453
,I/CheckinService( 6440): Checking schedule, now: 1452019388194 next: 1452019372711
I/CheckinService( 6440): active receiver: enabled
,I/CheckinService( 6440): Preparing to send checkin request
I/EventLogService( 6440): Accumulating logs since 1452019338477
,I/CheckinRequestBuilder( 6440): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6440): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7965 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7965): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7965): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7965): VM with version 2.1.0 has multidex support
,I/MultiDex( 7965): install
I/MultiDex( 7965): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7965): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7965): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@390eec12: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7965): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1709): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6440): Restart initialization of location
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7965): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7965): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7965): Install completed successfully. count=14 extracted=0
,I/art     ( 1709): Explicit concurrent mark sweep GC freed 105902(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 15MB/25MB, paused 1.286ms total 127.151ms
,W/GCoreFlp( 1709): No location to return for getLastLocation()
,W/FusedLocationProvider( 1709): location=null
,D/WVCdm   (  297): Instantiating CDM.
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
,E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bf43a74)
,E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a846b9d)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b99d812)
E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42abe3)
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e75000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e75000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb0d81960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb81e3ba0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb824f090, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8328d48, idLength=0xb55b0730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=2960933607
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb824d930
D/DrmWidevineDash(  297): message_length=1591, signature=0xb81fbe20, signature_length=3042641684
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8001): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8001): dex2oat took 68.760ms (threads: 4)
,I/Adreno-EGL( 7965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7965): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7965): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7965): Local Branch: 
I/Adreno-EGL( 7965): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7965): Local Patches: NONE
I/Adreno-EGL( 7965): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7965): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7965): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7965): Local Branch: 
I/Adreno-EGL( 7965): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7965): Local Patches: NONE
I/Adreno-EGL( 7965): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e75000
,E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e75000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb500a960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb82dd670, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb820ac10, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8328d68, idLength=0xb55b0730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  297): PrepareKeyRequest: nonce=1535458256
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81fb7e0
D/DrmWidevineDash(  297): message_length=1626, signature=0xb820d190, signature_length=3042641684
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7965): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7965): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7965): Local Branch: 
I/Adreno-EGL( 7965): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7965): Local Patches: NONE
I/Adreno-EGL( 7965): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7965): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7965): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7965): Local Branch: 
I/Adreno-EGL( 7965): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7965): Local Patches: NONE
I/Adreno-EGL( 7965): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6440): Classify the device as Phone.
,I/CheckinTask( 6440): Sending checkin request (9512 bytes)
,I/CheckinRequestBuilder( 6440): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6440): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6440): Classify the device as Phone.
,I/CheckinTask( 6440): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6440): Checking schedule, now: 1452019391219 next: 1452620528208
I/CheckinService( 6440): active receiver: disabled
,D/CheckinService( 6440): Recording last checkin time for package unspecified as 1452019391234
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8029 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  321): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 24.703ms
,I/art     (  321): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.529ms
,D/PhoneMonitor( 8029): Register our PhoneStateListener
,I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 19.863ms
,V/SetupWizard( 8029): Connected to Gservices successfully
,D/GCM     ( 1709): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 7857:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7661:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7857/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7661/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8059 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@194e387b
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8092 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8111 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7894:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7894/cgroup.procs: No such file or directory
,W/ResourcesManager( 7792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8111): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  880): Explicit concurrent mark sweep GC freed 18481(954KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.737ms total 124.218ms
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8141 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8029:com.google.android.setupwizard/u0a35 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8029/cgroup.procs: No such file or directory
,W/asset   ( 8141): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8141): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8141): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8141): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6440): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6440): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b84be8b new=com.google.android.velvet.VelvetApplication@2b84be8b
,I/Icing   ( 6440): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 8059): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8168 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8168): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8059): UpdateCorporaTask done [took 190 ms] updated apps [took 190 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8197 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7965:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7965/cgroup.procs: No such file or directory
,D/Finsky  ( 8197): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8197): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8197): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8197): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8197): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8197): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8197): Skipping gmscore version check
,D/Finsky  ( 8197): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8197): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8092:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8092/cgroup.procs: No such file or directory
,I/Icing   ( 6440): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6440): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8141:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8141/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 7792:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7792/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309891, SEQNUM=4570, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-838, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1709): onCreate
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
,I/ConfigService( 1709): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
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
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
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
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 4
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309449, SEQNUM=4572, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-1003, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
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
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
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
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {18aef4be, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8265 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [84ms]
,I/GAv4    ( 8265): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8265):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8265):   adb logcat -s GAv4
,W/GAv4    ( 8265): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8265): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8265): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {18aef4be, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [300ms]
,I/ActivityManager(  880): Killing 8059:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8059/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): TAP version 13
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # multiplex can send data
I/jxcore-log( 6574): 
,V/AlarmManager(  880): send {1a04491f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {1a04491f, *walarm*:android.content.syncmanager.SYNC_ALARM} [7ms]
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): ok 1 String should be length:200
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # basic
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 2 sane
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # another
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 3 sane
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 4 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 5 null
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 6 (unnamed assert)
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 7 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 8 should not throw
I/jxcore-log( 6574): 
I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 9 (unnamed assert)
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 10 (unnamed assert)
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 11 should not throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 12 should be equal
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 13 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 14 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # failed to get mobile documents path
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 15 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 16 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 17 should be equal
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 18 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #init should register the networkChanged event
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): ok 19 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should throw on null device name
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 20 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 21 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): ok 22 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): ok 23 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should throw on negative port
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 24 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # #startBroadcasting should throw on too large port
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 25 should throw
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 26 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 27 should be equal
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 28 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 29 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 30 should be equal
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 31 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 32 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 33 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 34 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 35 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 36 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 37 should be equal
I/jxcore-log( 6574): 
I/jxcore-log( 6574): ok 38 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 39 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 40 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 41 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 42 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6574): ok 43 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): ok 44 should be equal
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # teardown
I/jxcore-log( 6574): 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019698876.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019698876.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019698876.6574
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019698876.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019698876.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019698876.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae4ded92 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ae4ded92 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
,D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
,I/wpa_supplicant( 1422): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
,I/jxcore-log( 6574): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
,I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
,D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
,D/WifiP2pService(  880): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
,D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  880): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699066.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699066.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699066.6574
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699066.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699066.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699066.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@97970ca2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@97970ca2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  880): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
,I/jxcore-log( 6574): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): remove client information from framework
,D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  880): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699104.6574
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699104.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699104.6574
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699104.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699104.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699104.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@888e49f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@888e49f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6574): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/WifiP2pService(  880): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699137.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699137.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699137.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699137.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699137.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699137.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4ecffae4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4ecffae4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
I/jxcore-log( 6574): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699181.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699181.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699181.6574
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699181.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699181.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699181.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6480fc26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6480fc26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
I/jxcore-log( 6574): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/WifiP2pService(  880): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
D/WifiP2pService(  880): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
I/jxcore-log( 6574): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699209.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699209.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699209.6574
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699209.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699209.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699209.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8eb53264 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8eb53264 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
I/jxcore-log( 6574): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
D/WifiP2pService(  880): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6574): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699235.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699235.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699235.6574
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699235.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699235.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699235.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9840e2a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9840e2a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6574): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
D/WifiP2pService(  880): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6574): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 657,4): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699259.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699259.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699259.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699259.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699259.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699259.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d86feb1a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d86feb1a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6574): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
D/WifiP2pService(  880): remove client information from framework
D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
,D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,I/jxcore-log( 6574): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699296.6574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699296.6574","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
,I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699296.6574
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699296.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699296.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699296.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7966d658 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7966d658 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
,I/wpa_supplicant( 1422): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  295): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  880): discovery change broadcast true
,I/jxcore-log( 6574): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
,I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/WifiP2pService(  880): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
D/WifiP2pService(  880): remove client information from framework
,D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699326.6574
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): bind: Binding a new listener
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699326.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6574): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): start: OK
I/io.jxcore.node.ConnectionHelper( 6574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452019699326.6574
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6574): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699326.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452019699326.6574","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452019699326.6574","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): start: OK
I/jxcore-log( 6574): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6574): 
I/io.jxcore.node.ConnectionHelper( 6574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6574): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6574): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6574): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6574): setState: NOT_STARTED
I/jxcore-log( 6574): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6574): 
,I/jxcore-log( 6574): # setup
I/jxcore-log( 6574): 
,I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6574): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6574): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService(  880): InactiveState{ when=-52ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-52ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=-52ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-52ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6cf7b464 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6cf7b464 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
D/WifiP2pService(  880): add a new client
D/WifiP2pService(  880): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local service added successfully
I/wpa_supplicant( 1422): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): setState: STARTED
D/WifiP2pService(  880): discovery change broadcast true
D/WifiP2pService(  880): InactiveState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service
,D/WifiP2pService(  880): remove client information from framework
,D/WifiP2pService(  880): InactiveState{ when=-6ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6574): Local services cleared successfully
I/wpa_supplicant( 1422): P2P-FIND-STOPPED 
D/MDMCTBK (  295): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  295): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  880): InactiveState{ when=-7ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-8ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState clear service request
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6574): Service requests cleared successfully
,D/TCMD    (  483): NL - Read 56 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=239, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310212, SEQNUM=4588, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1798, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {30d589f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {4f99551, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): done {30d589f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [27ms]
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [54ms]
,V/AlarmManager(  880): done {4f99551, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [57ms]
,I/EventLogService( 6440): Aggregate from 1452019388217 (log), 1452017884776 (data)
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {1a04491f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {1a04491f, *walarm*:android.content.syncmanager.SYNC_ALARM} [13ms]
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3212f342, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  880): done {3212f342, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [91ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=234, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310164, SEQNUM=4600, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=234, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309862, SEQNUM=4604, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=234, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310441, SEQNUM=4605, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3f3bdf53, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  880): done {3f3bdf53, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [22ms]
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310130, SEQNUM=4606, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-92, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309840, SEQNUM=4608, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3227, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {30d589f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): send {16fecf5a, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  880): done {30d589f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [27ms]
,I/ProcessStatsService(  880): Prepared write state in 24ms
,V/AlarmManager(  880): done {16fecf5a, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [76ms]
,I/ProcessStatsService(  880): Prepared write state in 6ms
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [104ms]
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2016-01-05-05-53-29.bin
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=231, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310117, SEQNUM=4613, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=271, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
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
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=231, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310130, SEQNUM=4615, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2634): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  880): send {126b747f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {489d89, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {1fe1018e, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {231b1daf, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {19f125bc, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  880): done {126b747f, *alarm*:android.intent.action.TIME_TICK} [46ms]
,V/AlarmManager(  880): done {489d89, *walarm*:com.motorola.ccc.cce.alarmintent} [107ms]
,V/AlarmManager(  880): done {1fe1018e, *walarm*:com.motorola.ccc.cce.alarmintent} [123ms]
,V/AlarmManager(  880): done {231b1daf, *walarm*:com.motorola.ccc.cce.alarmintent} [138ms]
,V/AlarmManager(  880): done {19f125bc, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [146ms]
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:26000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8458): 
D/AndroidRuntime( 8458): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8458): CheckJNI is OFF
D/AndroidRuntime( 8458): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10414 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6574:com.test.thalitest/u0a414 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{246a2046 com.example.hello/10406} due to missing metadata
I/WindowState(  880): WIN DEATH: Window{14db9b6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{3e24c4d1 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{3854d09f 6574:com.test.thalitest/u0a414}, curProc for 6574: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10414 user=0: pkg removed
I/art     ( 3211): Explicit concurrent mark sweep GC freed 11687(2MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 7MB/12MB, paused 919us total 46.945ms
W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 8111): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
I/art     ( 1570): Explicit concurrent mark sweep GC freed 5113(315KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 504us total 100.986ms
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8488 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Decoder ( 1413): createOrResetDecoder
I/ConfigService( 1709): onCreate
I/art     (  880): Explicit concurrent mark sweep GC freed 38846(2MB) AllocSpace objects, 11(262KB) LOS objects, 33% free, 20MB/30MB, paused 1.874ms total 183.697ms
I/art     (  880): WaitForGcToComplete blocked for 56.440ms for cause Explicit
W/asset   ( 8488): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8488): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8488): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8488): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8510 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  880): Killing 8168:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 6249(335KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.755ms total 177.408ms
D/AndroidRuntime( 8458): Shutting down VM
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8168/cgroup.procs: No such file or directory
I/Launcher( 1570): Deferring update until onResume
W/ContextImpl( 8510): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6440): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6440): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6440): Reading stored module config
D/ChimeraCfgMgr( 6440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6440): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6440): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6440): App measurement is starting up, version: 8489
I/GMPM-SVC( 6440): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1709): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1709): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6440): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6440): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8543 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/ChimeraCfgMgr( 6440): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6440): Module APK com.google.android.play.games already loaded
W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b84be8b new=com.google.android.velvet.VelvetApplication@2b84be8b
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8571 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 6440): doRemovePackageData com.test.thalitest
I/art     (  321): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.926ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.921ms
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.881ms
D/ConnectivityService(  880): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  880): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6440): CM callback handler got msg 524290
E/BaseAppContext( 6440): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/BaseAppContext( 6440): Using Auth Proxy for data requests.
W/DriveInitializer( 6440): Awaiting to be initialized
W/DriveInitializer( 6440): Background init thread started
I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8608 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8543): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/DocListDatabase( 6440): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 6440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 6440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 6440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 6440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 6440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 6440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 6440): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 6440): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 6440): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 6440): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 6440): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 6440): Process: com.google.android.gms, PID: 6440
E/AndroidRuntime( 6440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6440): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 6440): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 6440): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 6440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 6440): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 6440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 6440): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 6440): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 6440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6440): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DriveAsyncService( 6440): disk I/O error (code 3850)
E/DriveAsyncService( 6440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 6440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 6440): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6440): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6440): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6440): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6440): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6440): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6440): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 6440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 6440): Sending signal. PID: 6440 SIG: 9
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a703f7d)
D/WifiService(  880): Client connection lost with reason: 4
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/SQLiteLog( 8543): (778) statement aborts at 16: [DELETE FROM applications WHERE uri=?] 
E/SQLiteLog( 8543): (1) statement aborts at 2: [ROLLBACK;] cannot rollback - no transaction is active
I/ActivityManager(  880): Process com.google.android.gms (pid 6440) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1750ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11750ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21750ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21750ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21750ms
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=8629 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SharedPreferencesImpl( 8543): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
E/AndroidRuntime( 8543): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 8543): Process: com.google.android.googlequicksearchbox:search, PID: 8543
E/AndroidRuntime( 8543): android.database.sqlite.SQLiteException: cannot rollback - no transaction is active (code 1)
E/AndroidRuntime( 8543): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 8543): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 8543): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:439)
E/AndroidRuntime( 8543): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 8543): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/AndroidRuntime( 8543): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:91)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 8543): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 8543): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 8543): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 8543): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8543): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8543): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8543): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
