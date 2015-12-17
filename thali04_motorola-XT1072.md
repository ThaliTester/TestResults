#### Test 539786639813e59_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6346): 
D/AndroidRuntime( 6346): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6346): CheckJNI is OFF
D/AndroidRuntime( 6346): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6365 uid=10387 gids={50387, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6346): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6365): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6365): Time to load native libraries: 3 ms (timestamps 7449-7452)
I/LibraryLoader( 6365): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6365): Binding Chromium to main looper Looper (main, tid 1) {371e49f3}
,I/LibraryLoader( 6365): Expected native library version number "",actual native library version number ""
,I/chromium( 6365): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6365): Initializing chromium process, singleProcess=true
,W/art     ( 6365): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6365): ApplicationContext is null in ApplicationStatus
,W/chromium( 6365): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6365): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6365): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6365): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6365): Local Branch: 
I/Adreno-EGL( 6365): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6365): Local Patches: NONE
I/Adreno-EGL( 6365): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d527af:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{27f1cc78 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6365): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6365): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6365): CordovaWebView is running on device made by: motorola
,W/art     ( 6365): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6365): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6365): Render dirty regions requested: true
,D/Atlas   ( 6365): Validating map...
,W/chromium( 6365): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6365): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6365): Enabling debug mode 0
,I/Keyboard.Facilitator( 1423): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,1030
,I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +951ms (total +1s30ms)
,W/IInputConnectionWrapper( 6365): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6365): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6365): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6365): Cannot call determinedVisibility() - never saw a connection for the pid: 6365
,D/JsMessageQueue( 6365): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6365): JniHelper::setJavaVM(0xb70a8310), pthread_self() = -1220306584
,D/JX-Cordova( 6365): jxcore cordova android initializing
,I/art     ( 6365): Background sticky concurrent mark sweep GC freed 20565(1606KB) AllocSpace objects, 3(44KB) LOS objects, 8% free, 10MB/11MB, paused 5.970ms total 42.442ms
,W/jxcore-log( 6365): Initializing JXcore engine
W/jxcore-log( 6365): JXcore engine is ready
,W/jxcore-log( 6365): Starting JXcore engine
,W/.test.thalitest( 6365): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10387 path="socket:[9263]" dev="sockfs" ino=9263 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6365): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10387 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6365): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10387 path="socket:[7527]" dev="sockfs" ino=7527 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6365): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10387 path="socket:[27737]" dev="sockfs" ino=27737 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6365): Platform android
W/jxcore-log( 6365): 
,W/jxcore-log( 6365): Process ARCH arm
W/jxcore-log( 6365): 
,I/jxcore-log( 6365): JXcore Cordova bridge is ready!
I/jxcore-log( 6365): 
W/jxcore-log( 6365): JXcore engine is started
I/chromium( 6365): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6365): Toggling radios to true
I/jxcore-log( 6365): 
D/BluetoothAdapter( 6365): enable(): BT is already enabled..!
D/WifiService(  885): New client listening to asynchronous messages
D/WifiService(  885): setWifiEnabled: true pid=6365, uid=10387
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 6365): Radios toggled
I/jxcore-log( 6365): 
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 1453): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  310):  STA Disconnected !!
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): get_property_value, Enter
I/MDMCTBK (  310): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  310): get_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  310): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1453): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  310): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
D/Tethering(  885): InitialState.processMessage what=4
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 1453): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  310): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
D/WifiP2pService(  885): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/wpa_supplicant( 1453): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  308): Clearing all IP addresses on wlan0
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1736): Read error: ssl=0xb73bce98: I/O error during system call, Connection timed out
V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xb73bce98: I/O error during system call, Broken pipe
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/WifiMetrics(  885): connected time updated 271655
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6435 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1453): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1453): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524292
,E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1972): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1453): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  308): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6435): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6461 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6023:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6023/cgroup.procs: No such file or directory
,W/ResourcesManager( 6461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  310): Event received = WPS-AP-AVAILABLE 
E/WifiStateMachine(  885): [1,450,361,685,913 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1453): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  310): Event received = Trying to associate with
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1453): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e1f445c sup_state=SCANNING debouncing=false
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 192 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  310): Event received = Associated with c0:ff:d4
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1453): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  310): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1453): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  310): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  310):  STA Connected !!
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/MDMCTBK (  310): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  310): get_freq !!, resp=2412
I/MDMCTBK (  310): get_freq !!, Strip data
I/MDMCTBK (  310): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): get_property_value, Enter
I/MDMCTBK (  310): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  310): get_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  310): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  310): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
,I/MDMCTBK (  310): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): get_property_value, Enter
I/MDMCTBK (  310): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  310): get_property_value, Exit
I/MDMCTBK (  310): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223795232
I/MDMCTBK (  310): return from set_get_from_wpa_supplicant
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  310): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  310): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  310): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  310): , reply_len: 3, ret: 0
E/MDMCTBK (  310): MdmCutbackHndler, resp=OK
E/MDMCTBK (  310): 
,D/MDMCTBK (  310): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
,D/Tethering(  885):  5
D/Tethering(  885):  7
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1453): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1453): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0225a2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0225a2 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6461): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6461): MmsConfig.loadMmsSettings
I/Babel_SMS( 6461): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6461): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6461): MmsConfig.loadFromResources
E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6461): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/DHCPCD  ( 6505): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,W/Settings( 6461): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DHCPCD  ( 6505): version 5.5.6 starting
E/DHCPCD  ( 6505): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6505): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6505): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/Babel_Crash( 6461): startup - clean
,I/Babel   ( 6461): deleted: false for 0
,D/DHCPCD  ( 6505): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6505): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6505): wlan0: sending REQUEST (xid 0xdfcd70ab), next in 3.98 seconds
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6461): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6461): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6461): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6066:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6066/cgroup.procs: No such file or directory
,I/vclib   ( 6461): onServiceConnected
,W/Babel   ( 6461): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6505): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6505): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6505): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6505): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6505): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6505): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
,D/DHCPCD  ( 6505): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1972): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:14:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361688203], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361688184]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1972): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1303): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6571 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1475): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2938): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2938): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2938): [debug] > CusSM.onRadioDown
,I/MusicStore( 6571): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6571): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6571): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6571): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6365): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): my name is : motorola-XT1072_PT4451
I/jxcore-log( 6365): 
,V/JNIHelp ( 6571): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6571): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6571): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6571): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6571): GMSCore installation verified
,I/jxcore-log( 6365): attempting to connect to test coordinator
I/jxcore-log( 6365): 
I/ConfigStore( 6571): Config Database version: 1
I/jxcore-log( 6365): check test folder
I/jxcore-log( 6365): 
I/jxcore-log( 6365): found test : ./testFindPeers.js
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): found test : ./testReConnect.js
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): found test : ./testSendData.js
I/jxcore-log( 6365): 
,I/MediaRouter( 6571): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/jxcore-log( 6365): Test app app.js loaded
I/jxcore-log( 6365): 
,V/MusicLeanback( 6571): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/chromium( 6365): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NetworkMonitor( 6571): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6571): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 6365): DBG, CoordinatorConnector connect called
I/jxcore-log( 6365): 
I/jxcore-log( 6365): Coordinator is now connected to the server!
I/jxcore-log( 6365): 
I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6622 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/chromium( 6365): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     (  327): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 24.987ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.288ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 24.572ms
,I/GHttpClientFactory( 6571): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6571): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 6098:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6098/cgroup.procs: No such file or directory
,V/Mms     ( 6622): mnc/mcc: 
,V/Mms     ( 6622): tag: int value: recipientLimit - 20
,V/Mms     ( 6622): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6622): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6622): tag: int value: maxSubjectLength - 80
V/Mms     ( 6622): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6622): tag: bool value: enableGroupMms - false
,V/Mms     ( 6622):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  885): Explicit concurrent mark sweep GC freed 49955(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.445ms total 134.845ms
,W/ResourcesManager( 6622): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6659 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6221:com.google.android.youtube/u0a101 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10101/pid_6221/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6659): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6659): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6659): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 6461:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6461/cgroup.procs: No such file or directory
,I/CheckinService( 1972): Checkin interval check for package: unspecified last checkin: 1450361424402 min interval config: 0 actual interval: 265504
,I/CheckinService( 1972): Checking schedule, now: 1450361689913 next: 1450361454373
I/CheckinService( 1972): active receiver: enabled
,I/CheckinService( 1972): Preparing to send checkin request
I/EventLogService( 1972): Accumulating logs since 1450361418550
,I/CheckinRequestBuilder( 1972): Checkin reason type: 8 attempt count: 1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6679 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 1972): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6696 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524295
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1972): CM callback handler got msg 524295
,W/ResourcesManager( 6696): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6696): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6696): VM with version 2.1.0 has multidex support
I/MultiDex( 6696): install
I/MultiDex( 6696): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6696): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6715 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityThread( 6696): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6696): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19ea84d4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6696): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 6715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 6696): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6696): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6696): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  312): Instantiating CDM.
,I/WVCdm   (  312): CdmEngine::OpenSession
I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/Babel_SMS( 6715): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6715): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6715): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6715): MmsConfig.loadFromDatabase
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  312): Service_Initialize: starts!
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
,D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
,D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6715): MmsConfig.loadFromResources
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xb5569960
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb742dd78, dataLength=8
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb742d458, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb75405a8, idLength=0xb5469730
,E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6715): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  312): PrepareKeyRequest: nonce=3547138680
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb742a150
D/DrmWidevineDash(  312): message_length=1591, signature=0xb742f240, signature_length=3041302292
,W/Settings( 6715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6715): startup - clean
,I/Babel   ( 6715): deleted: false for 0
,D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  312): CdmEngine::CloseSession
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  312): L3 Terminate.
D/DrmWidevineDash(  312): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  312): Service_Uninitialize: starts!
D/QSEECOMAPI: (  312): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  312): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  312): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6750 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): now: 347760 ,futureTime: 9223372036854775807
D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): now: 347760 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): now: 347762 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2938): [debug] > PollingManagerService, now: 347764 ,futureTime: 75697361
,D/OtaApp  ( 2938): [debug] > Polling alarm set to expire at: 75697361 Current Time: 347765
,D/Central_PollingManager( 1475): now: 347767 ,futureTime: 86478058
D/Central_PollingManager( 1475): Polling alarm set to expire at: 86478058 Current Time: 347767
D/OtaApp  ( 2938): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2938): [debug] > CusSM.onRadioUp
,I/NetworkMonitor( 6571): type=WIFI subType= reason=null isConnected=true
,W/AudioCapabilities( 6715): Unsupported mime audio/amr-wb-plus
,D/OtaApp  ( 2938): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/VideoCapabilities( 6715): Unsupported mime video/mpeg2
,D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2938): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,I/dex2oat ( 6767): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2938): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/VideoCapabilities( 6715): Unsupported profile 4 for video/mp4v-es
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2938): Not proxy app, so login/provision not allowed
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2938): set mOutstandingReq to true.
I/ Nonce  ( 2938):  Nonce getNonce 
I/ Nonce  ( 2938):  Nonce Request 
I/ Nonce  ( 2938):  Nonce execute Request 
,D/MMApiWebService( 2938): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/vclib   ( 6715): onServiceConnected
,W/Babel   ( 6715): Attempted to change video mute state without an active call.
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2938): Not proxy app, so login/provision not allowed
,I/Babel   ( 6715): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 6435:com.motorola.context/u0a8 (adj 15): empty #7
,D/MMApiWebService( 2938): generating token using payload instead of using session token
,D/ Nonce  ( 2938):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2938): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_6435/cgroup.procs: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6750): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6750): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6750): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6750): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6750): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6750):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6750):   adb logcat -s GAv4
,I/dex2oat ( 6767): dex2oat took 379.909ms (threads: 4)
,W/GAv4    ( 6750): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6696): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6696): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6696): Local Branch: 
I/Adreno-EGL( 6696): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6696): Local Patches: NONE
I/Adreno-EGL( 6696): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 6750): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6750): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6696): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6696): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6696): Local Branch: 
I/Adreno-EGL( 6696): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6696): Local Patches: NONE
I/Adreno-EGL( 6696): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6750): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6750): Time to load native libraries: 2 ms (timestamps 8514-8516)
I/LibraryLoader( 6750): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6750): Binding Chromium to main looper Looper (main, tid 1) {2d22cb04}
,I/LibraryLoader( 6750): Expected native library version number "",actual native library version number ""
,I/chromium( 6750): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6750): Initializing chromium process, singleProcess=true
W/art     ( 6750): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6750): ApplicationContext is null in ApplicationStatus
,W/chromium( 6750): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6750): Local Branch: 
I/Adreno-EGL( 6750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6750): Local Patches: NONE
I/Adreno-EGL( 6750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6750): Requires BLUETOOTH permission
,I/art     (  885): Explicit concurrent mark sweep GC freed 14931(730KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.497ms total 116.815ms
,I/NSApplication( 6750): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6822 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6571:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6571/cgroup.procs: No such file or directory
,I/WVCdm   (  312): CdmEngine::OpenSession
I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  312): Service_Initialize: starts!
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
E/QSEECOMAPI: (  312): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  312): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  312): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  312): App is not loaded in QSEE
,D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xbef8a4e0
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb742f5d0, dataLength=8
,D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74e7538, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb75405c8, idLength=0xbef8a2b0
,D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  312): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  312): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  312): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  312): PrepareKeyRequest: nonce=624608856
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb742a150
D/DrmWidevineDash(  312): message_length=1626, signature=0xb7440170, signature_length=3203965588
,I/ Nonce  ( 2938):  Nonce Reponse 
D/        ( 2938): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"311a2030-7c3a-4836-9ba3-4f9ac0bfaccc"}
,D/MMApiWSBase( 2938): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2938):  Nonce Handle Reponse 
D/MMApiProvisionService( 2938): mOutstandingReq set to false
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 4541(215KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 722us total 30.190ms
,D/MMApiProvisionService( 2938):  pTime 1450280700010 sExp 172742 cTime 1450361692455 tTime 1450453442010
D/MMApiProvisionService( 2938):  No login Required 
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6843 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6622:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  312): CdmEngine::CloseSession
D/DrmWidevineDash(  312): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  312): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  312): L3 Terminate.
D/DrmWidevineDash(  312): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  312): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  312): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  312): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  312): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  312): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 6696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6696): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6696): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6696): Local Branch: 
I/Adreno-EGL( 6696): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6696): Local Patches: NONE
I/Adreno-EGL( 6696): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6622/cgroup.procs: No such file or directory
,W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6696): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6696): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6696): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6696): Local Branch: 
I/Adreno-EGL( 6696): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6696): Local Patches: NONE
I/Adreno-EGL( 6696): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1972): Classify the device as Phone.
,I/CheckinTask( 1972): Sending checkin request (9521 bytes)
,W/DataUsage( 2938): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6870 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6659:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6659/cgroup.procs: No such file or directory
,I/MusicStore( 6870): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6870): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6870): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6870): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6870): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6870): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6870): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6870): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6870): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6870): GMSCore installation verified
,I/ConfigStore( 6870): Config Database version: 1
,I/CheckinRequestBuilder( 1972): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1972): Failed to find provider info for com.google.android.wearable.settings
,I/MediaRouter( 6870): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6870): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6870): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6870): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6908 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6870): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6870): Using platform SSLCertificateSocketFactory
,I/CheckinRequestBuilder( 1972): Classify the device as Phone.
,I/CheckinTask( 1972): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 1584(57KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 396us total 29.818ms
,V/Mms     ( 6908): mnc/mcc: 
,V/Mms     ( 6908): tag: int value: recipientLimit - 20
,V/Mms     ( 6908): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6908): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6908): tag: int value: maxSubjectLength - 80
V/Mms     ( 6908): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6908): tag: bool value: enableGroupMms - false
V/Mms     ( 6908):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  885): Killing 6679:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6679/cgroup.procs: No such file or directory
I/CheckinService( 1972): Checking schedule, now: 1450361693561 next: 1450962830512
I/CheckinService( 1972): active receiver: disabled
,D/CheckinService( 1972): Recording last checkin time for package unspecified as 1450361693580
,I/ActivityManager(  885): Killing 6750:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ActivityManager(  885): Killing 6715:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_6750/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6715/cgroup.procs: No such file or directory
,W/ResourcesManager( 6908): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6942 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6822:com.android.chrome/u0a52 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_6822/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6942): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6942): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6942): onReceive CONNECTIVITY_CHANGE networkType=1
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6365): BLE supported!!
I/jxcore-log( 6365): 
,I/ActivityManager(  885): Killing 6843:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_6843/cgroup.procs: No such file or directory
,I/CheckinService( 1972): Checkin interval check for package: unspecified last checkin: 1450361693580 min interval config: 0 actual interval: 428
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6964 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1972): Checking schedule, now: 1450361694061 next: 1450361723512
I/CheckinService( 1972): active receiver: disabled
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 24.710ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.101ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.014ms
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6981 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6870:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6870/cgroup.procs: No such file or directory
,I/art     (  885): Explicit concurrent mark sweep GC freed 8577(429KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.356ms total 121.545ms
I/art     (  885): WaitForGcToComplete blocked for 18.552ms for cause HeapTrim
,W/ResourcesManager( 6981): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6981): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6981): MmsConfig.loadMmsSettings
I/Babel_SMS( 6981): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6981): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6981): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6981): MmsConfig.loadFromResources
,E/Babel_SMS( 6981): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6981): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6981): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6981): startup - clean
,I/Babel   ( 6981): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7015 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6981): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6981): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6981): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6981): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6981): onServiceConnected
,W/Babel   ( 6981): Attempted to change video mute state without an active call.
,I/GAv4    ( 7015): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7015):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7015):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7015): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7015): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7015): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7015): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6981): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 6908:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_6908/cgroup.procs: No such file or directory
,I/WebViewFactory( 7015): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7015): Time to load native libraries: 2 ms (timestamps 2221-2223)
,I/LibraryLoader( 7015): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7015): Binding Chromium to main looper Looper (main, tid 1) {2d22cb04}
,I/LibraryLoader( 7015): Expected native library version number "",actual native library version number ""
,I/chromium( 7015): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7015): Initializing chromium process, singleProcess=true
,W/art     ( 7015): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7015): ApplicationContext is null in ApplicationStatus
,W/chromium( 7015): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7015): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7015): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7015): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7015): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7015): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7015): Local Branch: 
I/Adreno-EGL( 7015): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7015): Local Patches: NONE
I/Adreno-EGL( 7015): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7015): Starting up...
,W/AudioManagerAndroid( 7015): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7087 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6942:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_6942/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7106 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6964:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_6964/cgroup.procs: No such file or directory
,W/ResourcesManager( 7106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 6981:com.google.android.talk/u0a70 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_6981/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2938): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2938): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2938): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2938): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2938): onServiceConnected()
D/GetNotificationsWS( 2938): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2938): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2938): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7132 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,E/MDM     ( 1736): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1972): Restart initialization of location
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7160 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
,I/MusicStore( 7160): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7160): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7160): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7160): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7160): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7160): GMSCore installation verified
,I/ConfigStore( 7160): Config Database version: 1
,I/MediaRouter( 7160): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7160): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7160): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7160): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7194 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7160): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7160): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7194): mnc/mcc: 
,V/Mms     ( 7194): tag: int value: recipientLimit - 20
,V/Mms     ( 7194): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7194): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7194): tag: int value: maxSubjectLength - 80
V/Mms     ( 7194): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7194): tag: bool value: enableGroupMms - false
V/Mms     ( 7194):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7224 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7015:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7015/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7224): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7224): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7224): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7087:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7087/cgroup.procs: No such file or directory
,I/CheckinService( 1972): Checkin interval check for package: unspecified last checkin: 1450361693580 min interval config: 0 actual interval: 3887
,I/CheckinService( 1972): Checkin interval check for package: unspecified last checkin: 1450361693580 min interval config: 0 actual interval: 3889
,I/CheckinService( 1972): Checking schedule, now: 1450361697477 next: 1450361723512
,I/CheckinService( 1972): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7245 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1972): Checking schedule, now: 1450361697532 next: 1450361723512
,I/CheckinService( 1972): active receiver: disabled
,I/art     (  885): Explicit concurrent mark sweep GC freed 11736(564KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.479ms total 115.342ms
,I/ActivityManager(  885): Killing 7106:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ResourcesManager( 7245): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7106/cgroup.procs: No such file or directory
,I/Babel_SMS( 7245): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7245): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7245): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7245): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7245): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7245): MmsConfig.loadFromResources
,E/Babel_SMS( 7245): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7245): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7245): startup - clean
,I/Babel   ( 7245): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7272 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7245): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7245): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7245): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7245): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7245): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7245): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7245): onServiceConnected
,W/Babel   ( 7245): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7272): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7272): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7272):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7272):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7272): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7245): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7160:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7272): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7272): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7160/cgroup.procs: No such file or directory
,W/GAv4    ( 7272): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7272): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7272): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7272): Time to load native libraries: 2 ms (timestamps 5305-5307)
I/LibraryLoader( 7272): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7272): Binding Chromium to main looper Looper (main, tid 1) {2d22cb04}
,I/LibraryLoader( 7272): Expected native library version number "",actual native library version number ""
,I/chromium( 7272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7272): Initializing chromium process, singleProcess=true
,W/art     ( 7272): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7272): ApplicationContext is null in ApplicationStatus
,W/chromium( 7272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7272): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7272): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7272): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7272): Local Branch: 
I/Adreno-EGL( 7272): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7272): Local Patches: NONE
I/Adreno-EGL( 7272): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7272): Starting up...
,W/AudioManagerAndroid( 7272): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7343 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7194:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 25.538ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.223ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.737ms
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7194/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7370 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7224:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7224/cgroup.procs: No such file or directory
,W/ResourcesManager( 7370): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Killing 7132:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7132/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2938): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2938): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2938): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2938): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2938): onServiceConnected()
D/GetNotificationsWS( 2938): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2938): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2938): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2938): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2938): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2938): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2938): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2938): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7405 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2938): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2938): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2938): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2938): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6365): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1423): onFinishInput()
,D/PhoneMonitor( 7405): Register our PhoneStateListener
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,183
,V/SetupWizard( 7405): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 6696:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6696/cgroup.procs: No such file or directory
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7432 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7459 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  885): Killing 7245:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7245/cgroup.procs: No such file or directory
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@315fdc97
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1583): Deferring update until onResume
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7486 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7506 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7272:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7343:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7272/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7343/cgroup.procs: No such file or directory
,W/ResourcesManager( 7506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7506): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7506): MmsConfig.loadMmsSettings
I/Babel_SMS( 7506): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7506): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7506): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7506): MmsConfig.loadFromResources
,E/Babel_SMS( 7506): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7506): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7506): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7506): startup - clean
,I/Babel   ( 7506): deleted: false for 0
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {25827a02, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7543 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [107ms]
,W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7506): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7506): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7506): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
,I/art     (  885): Explicit concurrent mark sweep GC freed 18395(946KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.416ms total 117.535ms
,W/asset   ( 7543): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7543): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7543): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1972): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1972): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f8a9ee5 new=com.google.android.velvet.VelvetApplication@3f8a9ee5
,I/UpdateIcingCorporaServi( 7459): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1972): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7576 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7506): onServiceConnected
W/Babel   ( 7506): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7506): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7506): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7459): UpdateCorporaTask done [took 172 ms] updated apps [took 172 ms] 
,V/JNIHelp ( 7506): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 7576): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System  ( 7506): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7506): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 7576): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7576): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7576): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7576): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7576): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  885): Killing 7432:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/Ads     ( 7576): Skipping gmscore version check
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7432/cgroup.procs: No such file or directory
,D/Finsky  ( 7576): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7576): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7625 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7405:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7405/cgroup.procs: No such file or directory
,I/GAv4    ( 7625): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7625):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7625):   adb logcat -s GAv4
,W/GAv4    ( 7625): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7625): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7625): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  885): Killing 7486:com.google.android.partnersetup/u0a19 (adj 15): empty #7
V/AlarmManager(  885): done {25827a02, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [1245ms]
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_7486/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1972): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1972): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 7543:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_7543/cgroup.procs: No such file or directory
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=290, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310826, SEQNUM=4581, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-1090, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ActivityManager(  885): Killing 7459:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_7459/cgroup.procs: No such file or directory
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {258aef44, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  885): done {258aef44, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310342, SEQNUM=4585, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1113, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310278, SEQNUM=4587, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1144, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1423): run()
I/Keyboard.Facilitator( 1423): flushDynamicLanguageModels()
,I/ConfigService( 1736): onCreate
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1736): onDestroy
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6365): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): DBG, CoordinatorConnector command called
I/jxcore-log( 6365): 
I/jxcore-log( 6365): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":14,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0}]}
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): Start now : testSendData.js
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 14
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): check server
I/jxcore-log( 6365): 
I/jxcore-log( 6365): serverPort is 41100
I/jxcore-log( 6365): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Mode set to WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Failed to set discovery mode to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4451
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6365): bind: Binding a new listener
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6365): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6365): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4451","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): start: OK
I/io.jxcore.node.ConnectionHelper( 6365): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4451
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6365): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4451","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6365): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4451","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6365): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4451","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  885): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f7cfedc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2f7cfedc target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service
,D/WifiP2pService(  885): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): start: Starting P2P device discovery...
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6365): start: OK
,I/jxcore-log( 6365): StartBroadcasting started ok
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): do fake peer & start
I/jxcore-log( 6365): 
I/jxcore-log( 6365): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:16:44.043Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:44.045Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:44.045Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
,I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 6365): 2015-12-17T14:16:44.053Z SendDataTCPServer.js: TCP/IP server is bound to port: 41100
I/jxcore-log( 6365): 
I/chromium( 6365): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6365): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6365): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6365): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 665)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1453): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  310): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4673","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4673","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4673","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673] is available
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] is available
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 665)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 665)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 665)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 665)
,I/jxcore-log( 6365): 2015-12-17T14:16:49.422Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:49.422Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:49.423Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 1453): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] is available
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] is available
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/jxcore-log( 6365): 2015-12-17T14:16:54.424Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:16:54.424Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] is available
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:16:59.427Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:59.428Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:59.428Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:16:59.429Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
,I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 667)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6365): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-REQ 2462 fa
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 6
,W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 667)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 667)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 667)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/jxcore-log( 6365): 2015-12-17T14:17:09.784Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:09.785Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:09.785Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 667)
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=7711 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21aab174:true
,W/ResourcesManager( 7711): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@506a712:true
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=7742 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.658ms
,I/ActivityManager(  885): Killing 7370:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.375ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.368ms
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7370/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b337f99:true
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7768 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 7742): Bluetooth Device Name: Note4-1
,I/ActivityManager(  885): Killing 7506:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  885): Killing 7576:com.android.vending/u0a32 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7506/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_7576/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2789): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2789): Entering PendingCommandState State
,I/ActivityManager(  885): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=7805 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 7805): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2789): Removing bonded device:E0:DB:10:14:E2:C0
,D/BluetoothManagerService(  885): Message: 20
,D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37dc1f36:true
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,D/BluetoothAdapterService( 2789): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@371e49f3
,D/BluetoothMetrics( 2789): btclass5a020c
,D/Checkin ( 2789): publish the event [tag = MOT_BT event name = PAIRING]
,I/ActivityManager(  885): Killing 1972:com.google.android.gms/u0a16 (adj 15): empty #7
,I/BluetoothBondStateMachine( 2789): StableState(): Entering Off State
,D/WifiService(  885): Client connection lost with reason: 4
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@33ffee37)
,D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_1972/cgroup.procs: No such file or directory
,I/jxcore-log( 6365): 2015-12-17T14:17:14.785Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:14.786Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Incoming connection initialized (thread ID: 669)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Entering thread (ID: 669)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): onBytesRead: Read 82 bytes successfully (thread ID: 669)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): onBytesWritten: 81 bytes successfully written (thread ID: 669)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): removeThreadFromList: Removing thread with ID 669
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Handshake thread disposed (thread ID: 669)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Exiting thread (ID: 669)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], created successfully
D/io.jxcore.node.ConnectionHelper( 6365): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6365): Entering thread (ID: 670)
,I/jxcore-log( 6365): 2015-12-17T14:17:15.358Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6365): 
,I/io.jxcore.node.IncomingSocketThread( 6365): Local host address: localhost/127.0.0.1, port: 41100
D/io.jxcore.node.IncomingSocketThread( 6365): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6365): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6365): Exiting thread (ID: 670)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 671, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 672, name: Receiver)
,I/jxcore-log( 6365): 2015-12-17T14:17:16.129Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.240Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.309Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.377Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.437Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.490Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.553Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:16.644Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.016Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.359Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.362Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.414Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.450Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.518Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.633Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.650Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.703Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.740Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:17.770Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6365): 
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6365): 2015-12-17T14:17:18.094Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:18.100Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:18.151Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:18.519Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:18.524Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:18.845Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:19.015Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:19.087Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:19.334Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:19.507Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:19.619Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6365): 
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:17:19.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:19.788Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:19.788Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:19.789Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
,I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 673)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6365): 2015-12-17T14:17:19.882Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6365): 
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c51c rs_disc_pending=1
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6365): 2015-12-17T14:17:21.836Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:21.870Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:21.908Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.263Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.456Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.526Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.744Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.751Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.757Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.931Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:22.937Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.047Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.190Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.289Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.356Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.363Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.400Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.444Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.449Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:23.452Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6365): 
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c51c rs_disc_pending=1
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c89c rs_disc_pending=1
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2789): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 672, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6365): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 670
D/io.jxcore.node.IncomingSocketThread( 6365): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 672
D/io.jxcore.node.IncomingSocketThread( 6365): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 671
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6365): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 672, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 671, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 671, name: Sender)
,I/jxcore-log( 6365): 2015-12-17T14:17:23.920Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6365): 
,W/bt-sdp  ( 2789): process_service_search_attr_rsp
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c51c rs_disc_pending=1
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2789): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2789): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2789): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2789): StableState(): Entering Off State
,D/BluetoothMetrics( 2789): btclass5a020c
,W/bt-rfcomm( 2789): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2789): RFCOMM_DisconnectInd LCID:0x44
D/Checkin ( 2789): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:1
W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 673)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Entering thread (ID: 674)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): onBytesWritten: 81 bytes successfully written (thread ID: 674)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Outgoing connection initialized (*handshake* thread ID: 674)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 673)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): onBytesRead: Read 83 bytes successfully (thread ID: 674)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Exiting thread (ID: 674)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6365): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6365): Entering thread (ID: 675)
,D/io.jxcore.node.OutgoingSocketThread( 6365): Server socket local port: 33098
,I/io.jxcore.node.OutgoingSocketThread( 6365): Now accepting connections...
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c51c rs_disc_pending=1
,W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 6365): onListeningForIncomingConnections: Outgoing connection is using port 33098 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 6365): 2015-12-17T14:17:25.546Z SendDataConnector.js: CLIENT connected to 33098, error: null
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:25.546Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6365): 
,I/io.jxcore.node.OutgoingSocketThread( 6365): Incoming data from address: /127.0.0.1, port: 33098
D/io.jxcore.node.OutgoingSocketThread( 6365): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6365): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6365): Exiting thread (ID: 675)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 677, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 676, name: Sender)
,I/jxcore-log( 6365): 2015-12-17T14:17:25.568Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6365): 2015-12-17T14:17:26.424Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:26.459Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6365): 2015-12-17T14:17:26.523Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:26.644Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6365): 2015-12-17T14:17:26.877Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:27.258Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:27.302Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:27.422Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6365): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: RESTARTING
,D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1453): P2P-FIND-STOPPED 
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  310): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1453): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1453): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1453): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1453): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 1453): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  310): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  310): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  310): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  310): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  310): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/WifiP2pService(  885): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): discovery change broadcast false
,D/WifiP2pService(  885): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: null
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 0
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 0
D/WifiP2pService(  885):  status: 4
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 6365): 2015-12-17T14:17:27.514Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6365): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 6365): 2015-12-17T14:17:27.608Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:27.613Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:27.622Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:27.623Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6365): 
D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 6365): close
D/io.jxcore.node.OutgoingSocketThread( 6365): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 677
D/io.jxcore.node.OutgoingSocketThread( 6365): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 676
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 676, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6365): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 677, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 677, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 676, name: Sender)
I/jxcore-log( 6365): 2015-12-17T14:17:27.641Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6365): 
I/jxcore-log( 6365): ---- round done--------
I/jxcore-log( 6365): 
I/jxcore-log( 6365): do fake peer & start
I/jxcore-log( 6365): 
I/jxcore-log( 6365): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:27.642Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:27.642Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:27.642Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/chromium( 6365): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 678)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0c51c rs_disc_pending=1
,W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2789): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): Start timer timeout, starting now...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  885): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1453): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  310): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionTimeout: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/jxcore-log( 6365): 2015-12-17T14:17:42.654Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67] timed out
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:42.655Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67] timed out
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:42.658Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] already in the list, will not add again
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{38db36d3 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/jxcore-log( 6365): 2015-12-17T14:17:47.659Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:47.660Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:17:52.664Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:52.664Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:52.665Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:52.665Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 680)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 0 
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 678)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 678)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 678)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 678)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/jxcore-log( 6365): 2015-12-17T14:17:59.443Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:17:59.443Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67] failed
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:17:59.444Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2789): process_service_search_attr_rsp
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 2789): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2789): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2789): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2789): StableState(): Entering Off State
,D/BluetoothMetrics( 2789): btclass5a020c
,D/Checkin ( 2789): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onSocketConnected: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 680)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 680)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): onBytesWritten: 81 bytes successfully written (thread ID: 682)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Entering thread (ID: 682)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Exiting thread (ID: 682)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 680)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,W/bt-btif ( 2789): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 6365): 2015-12-17T14:18:04.445Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:04.445Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] is available
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-REQ 2462 92
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-52
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 9e
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 2 9e
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  885):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] already in the list, will not add again
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:AE:67), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:18:09.448Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:09.448Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:09.448Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:09.448Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
,I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: Nexus 5 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 683)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2789): process_service_search_attr_rsp
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:1
W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onSocketConnected: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 683)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): onBytesWritten: 81 bytes successfully written (thread ID: 684)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Outgoing connection initialized (*handshake* thread ID: 684)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 683)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Entering thread (ID: 684)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): onBytesRead: Read 77 bytes successfully (thread ID: 684)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Exiting thread (ID: 684)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166]
I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166]
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166] is available
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6365): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6365): Entering thread (ID: 685)
D/io.jxcore.node.OutgoingSocketThread( 6365): Server socket local port: 58863
I/io.jxcore.node.OutgoingSocketThread( 6365): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6365): onListeningForIncomingConnections: Outgoing connection is using port 58863 (peer ID: 34:FC:EF:11:AE:67)
I/jxcore-log( 6365): 2015-12-17T14:18:11.941Z SendDataConnector.js: CLIENT connected to 58863, error: null
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:11.942Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6365): 
,I/io.jxcore.node.OutgoingSocketThread( 6365): Incoming data from address: /127.0.0.1, port: 58863
D/io.jxcore.node.OutgoingSocketThread( 6365): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6365): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6365): Exiting thread (ID: 685)
,I/jxcore-log( 6365): 2015-12-17T14:18:11.955Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6365): 
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 687, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 686, name: Sender)
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-REQ 2462 92
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6365): 2015-12-17T14:18:12.887Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 6365): 2015-12-17T14:18:13.049Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 6365): 2015-12-17T14:18:13.236Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6365): 
,D/        ( 2789): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6365): 2015-12-17T14:18:13.264Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6365): 
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.340Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.357Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.403Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.408Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.443Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.443Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.451Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:13.452Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6365): 
D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 6365): close
D/io.jxcore.node.OutgoingSocketThread( 6365): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 687
D/io.jxcore.node.OutgoingSocketThread( 6365): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 686
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 686, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6365): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6365): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 687, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT7166] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 686, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 687, name: Receiver)
,I/jxcore-log( 6365): 2015-12-17T14:18:13.470Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6365): 
I/jxcore-log( 6365): ---- round done--------
I/jxcore-log( 6365): 
I/jxcore-log( 6365): do fake peer & start
I/jxcore-log( 6365): 
I/jxcore-log( 6365): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:13.471Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:13.471Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:13.471Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/chromium( 6365): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 688)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  885):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0ca5c rs_disc_pending=1
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2789): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2789): process_service_search_attr_rsp
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 688)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 688)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 688)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 6365): 2015-12-17T14:18:14.656Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:14.656Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:14.656Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 688)
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/bt-btm  ( 2789): tBTM_SEC_DEV:0xa6f0ca5c rs_disc_pending=0
W/bt-btif ( 2789): bta_dm_check_av:0
,W/bt-btif ( 2789): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  885):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-REQ 2462 92
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] removed
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] not available
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-89
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 4 9e
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=-4ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -89 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-5ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -89 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=33 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  885): Waited long enough for: ServiceRecord{1c468109 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2789): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2789): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2789): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2789): StableState(): Entering Off State
,D/BluetoothMetrics( 2789): btclass5a020c
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
,D/Checkin ( 2789): publish the event [tag = MOT_BT event name = PAIRING]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Incoming connection initialized (thread ID: 690)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Waiting for incoming connections...
,I/jxcore-log( 6365): 2015-12-17T14:18:19.685Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:19.685Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Entering thread (ID: 690)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): onBytesRead: Read 77 bytes successfully (thread ID: 690)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): onBytesWritten: 81 bytes successfully written (thread ID: 690)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): removeThreadFromList: Removing thread with ID 690
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Handshake thread disposed (thread ID: 690)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6365): Exiting thread (ID: 690)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] is available
,I/io.jxcore.node.ConnectionHelper( 6365): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], created successfully
D/io.jxcore.node.ConnectionHelper( 6365): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6365): Entering thread (ID: 691)
,I/io.jxcore.node.IncomingSocketThread( 6365): Local host address: localhost/127.0.0.1, port: 41100
D/io.jxcore.node.IncomingSocketThread( 6365): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6365): 2015-12-17T14:18:19.703Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6365): 
,I/io.jxcore.node.StreamCopyingThread( 6365): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6365): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6365): Exiting thread (ID: 691)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 692, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6365): Entering thread (ID: 693, name: Receiver)
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1453): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  310): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  885):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/jxcore-log( 6365): 2015-12-17T14:18:20.560Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.564Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.568Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.573Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.579Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.583Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.592Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.620Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.630Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6365): 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/jxcore-log( 6365): 2015-12-17T14:18:20.670Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6365): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/jxcore-log( 6365): 2015-12-17T14:18:20.682Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.721Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.729Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.761Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.773Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.778Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.811Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.894Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.901Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:20.930Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6365): 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6365): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793] is available
,W/bt-btif ( 2789): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 693, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6365): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 691
D/io.jxcore.node.IncomingSocketThread( 6365): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 693
D/io.jxcore.node.IncomingSocketThread( 6365): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6365): doStop: Thread ID: 692
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6365): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6365): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6365): Either failed to read from the output stream or write to the input stream (thread ID: 692, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6365): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6365): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 693, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6365): Exiting thread (ID: 692, name: Sender)
,I/jxcore-log( 6365): 2015-12-17T14:18:20.991Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6365): 
,W/bt-rfcomm( 2789): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 2789): RFCOMM_DisconnectInd LCID:0x4e
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9551","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7778","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 3 
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 7742): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 7742): Bluetooth Device Name: G3s-1
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:18:24.724Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:24.724Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:24.724Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:24.725Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 694)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6365): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  885): Explicit concurrent mark sweep GC freed 28393(1687KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.494ms total 133.697ms
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
,D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 15
,W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 4 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  885): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=139301 arg2=38 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,I/wpa_supplicant( 1453): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  310): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service discovery started successfully
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-88
I/wpa_supplicant( 1453): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 9e
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 7 9e
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  885):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  885):  primary type: 3-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 128
D/WifiP2pService(  885):  grpcapab: 9
D/WifiP2pService(  885):  devcapab: 4
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -88 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  885):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 4488
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 16
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 694)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 694)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 694)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 6365): 2015-12-17T14:18:35.685Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:35.685Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:35.685Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 694)
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT793","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  310): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  885): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 6365): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 6365): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/jxcore-log( 6365): 2015-12-17T14:18:40.685Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:40.686Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-REMOVED 6 
,I/wpa_supplicant( 1453): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  310): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1453): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  310): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  310): Event received = CTRL-EVENT-BSS-ADDED 8 c0
D/MDMCTBK (  310): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  310): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  885):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  885):  primary type: 10-0050F204-5
D/WifiP2pService(  885):  secondary type: null
D/WifiP2pService(  885):  wps: 392
D/WifiP2pService(  885):  grpcapab: 0
D/WifiP2pService(  885):  devcapab: 37
D/WifiP2pService(  885):  status: 3
D/WifiP2pService(  885):  wfdInfo: null
D/WifiP2pService(  885):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): restart: Restarting...
,D/WifiP2pService(  885): InactiveState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState clear service request
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,--------- beginning of crash
F/libc    ( 1453): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1453 (wpa_supplicant)
I/libc    ( 1453): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  885): InactiveState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139301 arg2=44 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState add service request
,D/WifiP2pManager( 6365): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Service request added successfully
,E/QC-QMI  (  429): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  429): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 6365): 2015-12-17T14:18:45.692Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:45.695Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:45.695Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:45.695Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
,I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 696)
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/WifiP2pService(  885): InactiveState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=139310 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6365): Failed to start the service discovery, got error code: 3
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 17
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 696)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 696)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 696)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 6365): 2015-12-17T14:18:50.874Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:50.875Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:18:50.875Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 696)
,I/jxcore-log( 6365): 2015-12-17T14:18:55.876Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:18:55.876Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,D/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6365): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 6365): 2015-12-17T14:19:00.878Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:19:00.878Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:19:00.879Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:19:00.879Z SendDataConnector.js: do connect now
I/jxcore-log( 6365): 
I/io.jxcore.node.ConnectionHelper( 6365): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6365): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6365): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): connect: [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6365): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 698)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6365): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 18
,W/BluetoothAdapter( 6365): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2789): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,W/bt-sdp  ( 2789): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 2789): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2789): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 698)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Maximum number of allowed retries (0) reached, giving up... (thread ID: 698)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): Exiting thread (thread ID: 698)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 6365): 2015-12-17T14:19:11.224Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
,I/jxcore-log( 6365): 2015-12-17T14:19:11.225Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed
I/jxcore-log( 6365): 
I/jxcore-log( 6365): 2015-12-17T14:19:11.225Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6365): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6365): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6365): shutdown (thread ID: 698)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: RESTARTING
,D/WifiP2pService(  885): InactiveState{ when=0 what=139268 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): Connection lost, restart supplicant
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  885): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  885): failed to set BSSID: any
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/WifiP2pService(  885): InactiveState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  308): Clearing all IP addresses on wlan0
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
,D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,V/NativeCrypto( 1736): Read error: ssl=0xb73868a8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xb73868a8: I/O error during system call, Broken pipe
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/jxcore-log( 6365): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6365): 
I/jxcore-log( 6365): The Coordinator has disconnected!
I/jxcore-log( 6365): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
W/Settings( 1736): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7978 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMetrics(  885): connected time updated 539263
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiScanningService(  885): SCAN_AVAILABLE : 1
D/RttService(  885): SCAN_AVAILABLE : 1
,D/WifiScanningService(  885): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  885): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  885): [1,450,361,955,649 ms] noteScanEnd no scan source
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService(  885): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): discovery change broadcast false
D/WifiP2pService(  885): P2pDisablingState
D/WifiP2pService(  885): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): p2p socket connection lost
D/WifiP2pService(  885): P2pDisabledState
D/WifiP2pService(  885): P2pDisabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): stop: Stopping services
,D/WifiP2pService(  885): P2pDisabledState{ when=0 what=139298 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): DefaultState{ when=0 what=139298 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): stop: Stopping P2P device discovery...
D/WifiP2pService(  885): P2pDisabledState{ when=0 what=139268 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): DefaultState{ when=0 what=139268 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6365): setState: NOT_INITIALIZED
,D/WifiP2pService(  885): P2pDisabledState{ when=0 what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): DefaultState{ when=0 what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6365): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6365): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 6365): Shutting down VM
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524292
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 7978): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 7978): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7978): MmsConfig.loadMmsSettings
I/Babel_SMS( 7978): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7978): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7978): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7978): MmsConfig.loadFromResources
E/Babel_SMS( 7978): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7978): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/Tethering(  885): InitialState.processMessage what=4
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  480): NL - Read 68 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/Settings( 7978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7978): startup - clean
,I/Babel   ( 7978): deleted: false for 0
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7978): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7978): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7978): Unsupported profile 4 for video/mp4v-es
,D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7978): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7978): onServiceConnected
,W/Babel   ( 7978): Attempted to change video mute state without an active call.
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
,I/MDMCTBK (  310): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  310): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2789): aclStateChangeCallback: Device is NULL
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {1ef427be, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  885): done {1ef427be, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [16ms]
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [45ms]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8027 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1475): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2938): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2938): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2938): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2938): [debug] > CusSM.onRadioDown
,I/MusicStore( 8027): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8027): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2789): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2789): Entering PendingCommandState State
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8027): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8027): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8027): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8027): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8027): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8027): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8027): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8027): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8027): GMSCore installation verified
,I/ConfigStore( 8027): Config Database version: 1
,I/MediaRouter( 8027): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8027): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8068 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8027): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/ActivityManager(  885): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8086 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GoogleURLConnFactory( 8027): Using platform SSLCertificateSocketFactory
,I/BluetoothBondStateMachine( 2789): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2789): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2789): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2789): StableState(): Entering Off State
D/BluetoothMetrics( 2789): btclass5a020c
,D/Checkin ( 2789): publish the event [tag = MOT_BT event name = PAIRING]
,I/ActivityManager(  885): Killing 7625:com.google.android.deskclock/u0a55 (adj 15): empty #7
V/Mms     ( 8068): mnc/mcc: 
V/Mms     ( 8068): tag: int value: recipientLimit - 20
V/Mms     ( 8068): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8068): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8068): tag: int value: maxSubjectLength - 80
V/Mms     ( 8068): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8068): tag: bool value: enableGroupMms - false
V/Mms     ( 8068):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8086): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8086): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8086): VM with version 2.1.0 has multidex support
I/MultiDex( 8086): install
I/MultiDex( 8086): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  885): failed to open /acct/uid_10055/pid_7625/cgroup.procs: No such file or directory
,W/ResourcesManager( 8068): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8116 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7768:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/bt-btif ( 2789): new conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2789): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6365): Incoming connection accepted
,W/google-breakpad( 8135): -----BEGIN BREAKPAD MICRODUMP-----
,W/google-breakpad( 8135): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad( 8135): S 0 A39FFFF0 A39FF000 00008000
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_7768/cgroup.procs: No such file or directory
,V/JNIHelp ( 8086): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/google-breakpad( 8135): S A39FF000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8135): S A39FF180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8135): S A39FF300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
D/PhoneMonitor( 8116): Register our PhoneStateListener
W/google-breakpad( 8135): S A39FF480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad( 8135): S A39FF600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad( 8135): S A39FF780 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F0732CB700000000C71F0000E0732CB7F0732CB700000000001000000090A2B40000000000000000DD180000F0732CB7E0732CB7C0F89FA37003000000000000C0F89FA3E40DF3B6E0732CB780FC9FA300FD9FA3A8747BA99B582AA90B0000000000000002000000F0DF9FA3000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8135): S A39FF900 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000031E00000000000000000000000000000070D8B000000000002000000E00000017000000041200006871406FE0A5E76F007B2923C0493E23C40000006871406FE0A5E76FC0493E2338A6E76F90AB5EB9007B292370F8AFA3F0DF9FA3F0FF9FA36D2AB2713C2AB27130000FA0F0DF9FA30412000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000004FF2000000000000D0FFFFFF00001582983A0000000000000A510600000010820000000000000000
W/google-breakpad( 8135): S A39FFA80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8135): S A39FFC00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000007F1570B3000000000B00000080FC9FA300FD9FA30000000053592AA9085B4CA00000000004000040C8685EB76871406FC40000006871406FE0A5E76FC0493E2338A6E76F90AB5EB91416F4B60B0000000000000002000000F0DF9FA30000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000070D8B000000000002000000E00000017000000041200006871406FE0A5E76F007B2923C0493E23C40000006871406FE0A5E76FC0493E2338A6E76F90AB5EB9007B292370F8AFA3F0DF9FA3F0FF9FA36D2AB2713C2AB27130000FA0F0DF9FA3041200000000000000000000000000000000000000000000
,W/google-breakpad( 8135): S A39FFD80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000015046562001000000000000000000000000000000000000000000000000000000000000000000004FF2000000000000D0FFFFFF00001582983A0000000000000A51060000001082000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC0
W/google-breakpad( 8135): S A39FFF00 3465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
D/MobileConnectivityChangeReceiver( 8116): onReceive Intent {, act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
W/google-breakpad( 8135): S A3A00500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
D/MobileConnectivityChangeReceiver( 8116): onReceive CONNECTIVITY_CHANGE networkType=1
W/google-breakpad( 8135): S A3A00680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F0000000000,0000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A00F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A01E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A02F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A03F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
,W/google-breakpad( 8135): S A3A04400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A04E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A05C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/ActivityThread( 8086): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/google-breakpad( 8135): S A3A05D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/System  ( 8086): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f74947a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8086): Installed default security provider GmsCore_OpenSSL
W/google-breakpad( 8135): S A3A05F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB271
W/google-breakpad( 8135): S A3A06F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC0493E2338A6E76F007B29236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0493E23E0A5E76F007B2923B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad( 8135): C 060000406871406FE0A5E76F007B2923C0493E23C40000006871406FE0A5E76FC0493E2338A6E76F90AB5EB9007B292370F8AFA3F0DF9FA3F0FF9FA36D2AB2713C2AB27130000FA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8135): M B6F52000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad( 8135): M A015F000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad( 8135): M A46AD000 00000000 00005000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
W/google-breakpad( 8135): M A5A74000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad( 8135): M A5ED6000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad( 8135): M A5EE0000 00000000 00007000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad( 8135): M A7238000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad( 8135): M A723D000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
W/google-breakpad( 8135): M A7B5D000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad( 8135): M ADF5D000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad( 8135): M ADF60000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
W/google-breakpad( 8135): M ADF70000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
W/google-breakpad( 8135): M AE0AB000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad( 8135): M AE0DF000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad( 8135): M AE107000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad( 8135): M AE6CE000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad( 8135): M AE6E6000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad( 8135): M AE6EF000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad( 8135): M AE6F5000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad( 8135): M AE6F9000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
,W/google-breakpad( 8135): M AE707000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
,W/google-breakpad( 8135): M AE722000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
,W/google-breakpad( 8135): M AE726000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
,W/google-breakpad( 8135): M AE745000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
,W/google-breakpad( 8135): M AE748000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
,W/google-breakpad( 8135): M AE74F000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
,W/google-breakpad( 8135): M AE754000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
W/google-breakpad( 8135): M AE790000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
,W/google-breakpad( 8135): M AE7AB000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
,W/google-breakpad( 8135): M AE8D2000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
,W/google-breakpad( 8135): M AE8E9000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad( 8135): M AE915000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad( 8135): M B0D77000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
,W/google-breakpad( 8135): M B247D000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad( 8135): M B24F2000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad( 8135): M B2513000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
,W/google-breakpad( 8135): M B2516000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
,W/google-breakpad( 8135): M B251E000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
W/google-breakpad( 8135): M B440E000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad( 8135): M B4E19000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad( 8135): M B4E23000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
,W/google-breakpad( 8135): M B5155000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad( 8135): M B5159000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
W/google-breakpad( 8135): M B519A000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
W/google-breakpad( 8135): M B5299000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
W/google-breakpad( 8135): M B52A8000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
,W/google-breakpad( 8135): M B52B7000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,W/google-breakpad( 8135): M B52BB000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
W/google-breakpad( 8135): M B571B000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
W/google-breakpad( 8135): M B571F000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad( 8135): M B5726000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
,W/google-breakpad( 8135): M B572A000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
,W/google-breakpad( 8135): M B5736000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
W/google-breakpad( 8135): M B5739000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad( 8135): M B574E000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad( 8135): M B57A4000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad( 8135): M B57B3000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad( 8135): M B57BD000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad( 8135): M B5858000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad( 8135): M B5895000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
W/google-breakpad( 8135): M B58B0000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad( 8135): M B58BD000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad( 8135): M B58F0000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
,W/google-breakpad( 8135): M B5B26000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
W/google-breakpad( 8135): M B5B43000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad( 8135): M B5B6B000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
,W/google-breakpad( 8135): M B5BC5000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
W/google-breakpad( 8135): M B5C02000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad( 8135): M B5C45000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
W/google-breakpad( 8135): M B5CDB000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
W/google-breakpad( 8135): M B661A000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad( 8135): M B6654000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
,W/google-breakpad( 8135): M B66A0000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
,W/google-breakpad( 8135): M B67B4000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/google-breakpad( 8135): M B67BA000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
,W/google-breakpad( 8135): M B6921000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad( 8135): M B6969000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
W/google-breakpad( 8135): M B696E000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
,W/google-breakpad( 8135): M B6975000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad( 8135): M B697D000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
W/google-breakpad( 8135): M B6994000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
,W/google-breakpad( 8135): M B6AF5000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
,W/google-breakpad( 8135): M B6AF8000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
,W/google-breakpad( 8135): M B6B04000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
,W/google-breakpad( 8135): M B6B07000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
,W/google-breakpad( 8135): M B6B56000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad( 8135): M B6B5E000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
,W/google-breakpad( 8135): M B6B98000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
,W/google-breakpad( 8135): M B6B9E000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad( 8135): M B6BA4000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
I/ActivityManager(  885): Killing 7805:com.android.settings/1000 (adj 15): empty #7
,W/google-breakpad( 8135): M B6BBE000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
W/google-breakpad( 8135): M B6BEE000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
W/google-breakpad( 8135): M B6C16000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
W/google-breakpad( 8135): M B6C21000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
,W/google-breakpad( 8135): M B6C28000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
,W/google-breakpad( 8135): M B6C2C000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
,W/google-breakpad( 8135): M B6C30000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad( 8135): M B6C84000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
W/google-breakpad( 8135): M B6C8D000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad( 8135): M B6C96000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad( 8135): M B6CAE000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
W/google-breakpad( 8135): M B6CE9000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad( 8135): M B6CF7000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad( 8135): M B6D68000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad( 8135): M B6DD3000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
W/google-breakpad( 8135): M B6EB0000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
,W/google-breakpad( 8135): M B6EB4000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
W/google-breakpad( 8135): M B6ECE000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
W/google-breakpad( 8135): M B6ED6000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
W/google-breakpad( 8135): M B6F3A000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad( 8135): M B6F42000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
W/google-breakpad( 8135): -----END BREAKPAD MICRODUMP-----
,W/google-breakpad( 6365): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 6365): Chrome build fingerprint:
W/google-breakpad( 6365): 0.0.1
W/google-breakpad( 6365): 18
W/google-breakpad( 6365): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6365): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 6365): ### WebView Version 44.0.2403.90 (code 240309000)
F/libc    ( 6365): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa39fdff0 in tid 7683 (Thread-664)
,D/NativeLibraryUtils( 8086): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_7805/cgroup.procs: No such file or directory
,I/iu.SyncManager( 8086): SYNC; picasa accounts
,D/NetworkLogImpl( 8086): Loaded NetworkSpeedPredictor
,I/ActivityManager(  885): Killing 7742:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/DEBUG   (  309): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   (  309): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
I/DEBUG   (  309): Revision: 'p300'
,I/DEBUG   (  309): ABI: 'arm'
I/DEBUG   (  309): pid: 6365, tid: 7683, name: Thread-664  >>> com.test.thalitest <<<
I/DEBUG   (  309): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa39fdff0
,I/DEBUG   (  309):     r0 6f407168  r1 6fe7a5e0  r2 23297b00  r3 233e49c0
,I/DEBUG   (  309):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 233e49c0
I/DEBUG   (  309):     r8 6fe7a638  r9 b95eab90  sl 23297b00  fp a3aff870
I/DEBUG   (  309):     ip a39fdff0  sp a39ffff0  lr 71b22a6d  pc 71b22a3c  cpsr a00f0030
I/DEBUG   (  309): 
I/DEBUG   (  309): backtrace:
I/DEBUG   (  309):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   (  309):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_7742/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8160 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WifiP2pService(  885): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8178 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiP2pService(  885): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel   ( 7978): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  885): Killing 8027:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_8027/cgroup.procs: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8178): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
,D/Tethering(  885):  1
D/Tethering(  885):  5
,D/Tethering(  885):  7
D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,I/GAv4    ( 8178): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8178):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8178):   adb logcat -s GAv4
,D/Tethering(  885): InitialState.processMessage what=4
,D/TCMD    (  480): NL - Read 1008 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
,D/Tethering(  885):  upstream interface types: 
,D/Tethering(  885):  0
D/Tethering(  885):  1
,D/Tethering(  885):  5
D/Tethering(  885):  7
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
W/ContextImpl( 8178): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/TCMD    (  480): NL - Read 1008 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/QsoftapCmd(  308): Got softap fwreload command we are passing on
,D/SoftapController(  308): Softap fwReload - Ok
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring down wlan0
,D/CommandListener(  308): Clearing all IP addresses on wlan0
,W/GAv4    ( 8178): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8178): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/WifiStateMachine(  885): setWifiState: enabling
E/WifiStateMachine(  885): Supplicant start successful
D/WifiMonitor(  885): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  885): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8178): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8178): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8178): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant( 8221): Successfully initialized wpa_supplicant
E/wpa_supplicant( 8221): Line 13: unknown global field 's'.
E/wpa_supplicant( 8221): Line 13: Invalid configuration line 's'.
,I/wpa_supplicant( 8221): rfkill: Cannot open RFKILL control device
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,I/libmdmdetect( 8221): ESOC framework not supported
E/Diag_Lib( 8221):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 8221): baseband property is set to [msm]
I/libmdmdetect( 8221): ESOC framework not supported
,E/wpa_supplicant( 8221):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8221): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8221): card_info[i].card_state: 0x0
,E/wpa_supplicant( 8221): card_info[i].error_code: 0x0
E/wpa_supplicant( 8221): SIM/USIM not ready
E/wpa_supplicant( 8221): Error while reading SIM card status
,E/wpa_supplicant( 8221): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8221): card_info[i].card_state: 0x0
,E/wpa_supplicant( 8221): card_info[i].error_code: 0x0
,E/wpa_supplicant( 8221): SIM/USIM not ready
,I/wpa_supplicant( 8221): eap_proxy: Card not ready
,I/DEBUG   (  309): 
I/DEBUG   (  309): Tombstone written to: /data/tombstones/tombstone_01
,I/BootReceiver(  885): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  885): WIN DEATH: Window{9a55a9f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  885): Client connection lost with reason: 4
,I/WebViewFactory( 8178): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/wpa_supplicant( 8221): Long line in configuration file truncated
,I/wpa_supplicant( 8221): rfkill: Cannot open RFKILL control device
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
,D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,E/wpa_supplicant( 8221): baseband property is set to [msm]
,I/libmdmdetect( 8221): ESOC framework not supported
,E/wpa_supplicant( 8221):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8221): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8221): card_info[i].card_state: 0x0
E/wpa_supplicant( 8221): card_info[i].error_code: 0x0
E/wpa_supplicant( 8221): SIM/USIM not ready
E/wpa_supplicant( 8221): Error while reading SIM card status
,E/wpa_supplicant( 8221): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8221): card_info[i].card_state: 0x0
E/wpa_supplicant( 8221): card_info[i].error_code: 0x0
E/wpa_supplicant( 8221): SIM/USIM not ready
I/wpa_supplicant( 8221): eap_proxy: Card not ready
,I/Zygote  (  327): Process 6365 exited due to signal (11)
,I/ActivityManager(  885): Process com.test.thalitest (pid 6365) has died
,W/bt-btif ( 2789): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
E/bt-btif ( 2789): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/LibraryLoader( 8178): Time to load native libraries: 1 ms (timestamps 8022-8023)
,I/LibraryLoader( 8178): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8178): Binding Chromium to main looper Looper (main, tid 1) {24890396}
,I/LibraryLoader( 8178): Expected native library version number "",actual native library version number ""
I/chromium( 8178): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8178): Initializing chromium process, singleProcess=true
,W/art     ( 8178): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8178): ApplicationContext is null in ApplicationStatus
,W/chromium( 8178): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/wpa_supplicant( 8221): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/Adreno-EGL( 8178): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8178): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8178): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8178): Local Branch: 
I/Adreno-EGL( 8178): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8178): Local Patches: NONE
I/Adreno-EGL( 8178): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/wpa_supplicant( 8221): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,W/AudioManagerAndroid( 8178): Requires BLUETOOTH permission
,I/MDMCTBK (  310): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  310): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): wifi_connect_to_supplicant, current pid is = 310
D/MDMCTBK (  310): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  310): wifi_close_sockets: Exit
E/MDMCTBK (  310): Attach monitor thread
D/MDMCTBK (  310): wifi_ctrl_recv: Exiting
,D/MDMCTBK (  310): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  310): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  310): wifi_close_sockets: Exit
I/MDMCTBK (  310): createWifiMonitorThread: Started the wifi monitor thread -1223773896
D/MDMCTBK (  310): wifi_wait_on_socket: Enter monitor thread
E/MDMCTBK (  310): Error: monitor connection not available
D/MDMCTBK (  310): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  310): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  310): wifi_close_sockets: Exit
,I/art     (  885): Explicit concurrent mark sweep GC freed 31808(1885KB) AllocSpace objects, 8(3MB) LOS objects, 33% free, 20MB/30MB, paused 1.621ms total 127.180ms
,I/NSApplication( 8178): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8267 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8068:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_8068/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8286 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8116:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 485us total 23.923ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.304ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.150ms
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8116/cgroup.procs: No such file or directory
,W/ResourcesManager( 8286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiStateMachine(  885): Supplicant connection established
E/WifiStateMachine(  885): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  885): Loading config and enabling all networks 
,E/WifiConfigStore(  885):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  885):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  885): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 7978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  885): Setting external_sim to 1
,D/WifiStateMachine(  885): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  885): startHal
E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa1b0f89c
,D/wifi    (  885): halHandle = 0x0, mVM = 0xb70a8310, mCls = 0x18d6
I/WifiNative-HAL(  885): Could not start hal
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 8221): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/wpa_supplicant( 8221): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_310-4\x00 that cannot receive messages
,E/native  (  885): do suspend true
,D/WifiP2pService(  885): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  308): Setting iface cfg
,D/CommandListener(  308): Trying to bring up p2p0
D/WifiMonitor(  885): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  885): P2pEnablingState
D/WifiP2pService(  885): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2p socket connection successful
D/WifiP2pService(  885): P2pEnabledState
D/WifiP2pService(  885): sending p2p connection changed broadcast
,D/WifiScanningService(  885): SCAN_AVAILABLE : 3
D/RttService(  885): SCAN_AVAILABLE : 3
,D/WifiScanningService(  885): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL(  885): startHal
E/wifi    (  885): getStaticLongField sWifiHalHandle 0xa48859cc
D/wifi    (  885): halHandle = 0x0, mVM = 0xb70a8310, mCls = 0x1018b6
I/WifiNative-HAL(  885): Could not start hal
E/WifiScanningService(  885): could not start HAL
,D/RttService(  885): DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  885): p2pGetDeviceAddress
,D/WifiNative-HAL(  885): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  885): DeviceAddress: 44:80:eb:7b:5a:07
,E/WifiStateMachine(  885): set country code US
E/WifiStateMachine(  885): set frequency band 2
,I/wpa_supplicant( 8221): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 8221): wlan0: Failed to initiate AP scan
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/WifiP2pService(  885): MCC mode enabled 0
,D/WifiP2pService(  885): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  885): sending p2p persistent groups changed broadcast
D/WifiP2pService(  885): InactiveState
D/WifiP2pService(  885): InactiveState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  885): InactiveState{ when=-12ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-12ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8312 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8160:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8160/cgroup.procs: No such file or directory
,I/MusicStore( 8312): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8312): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8312): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8312): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8312): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8312): GMSCore installation verified
,I/ConfigStore( 8312): Config Database version: 1
,I/MediaRouter( 8312): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8312): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8340 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8312): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8312): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  885): Killing 7978:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7978/cgroup.procs: No such file or directory
,V/Mms     ( 8340): mnc/mcc: 
,V/Mms     ( 8340): tag: int value: recipientLimit - 20
,V/Mms     ( 8340): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8340): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8340): tag: int value: maxSubjectLength - 80
V/Mms     ( 8340): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8340): tag: bool value: enableGroupMms - false
V/Mms     ( 8340):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8340): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8366 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8178:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 8366): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_8178/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8366): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 8366): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 8267:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_8267/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8385 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 8221): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 8221): wlan0: Failed to initiate AP scan
,D/WifiP2pService(  885): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledStateupdate channel list
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8402 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8286:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8286/cgroup.procs: No such file or directory
,W/ResourcesManager( 8402): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8402): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8402): MmsConfig.loadMmsSettings
I/Babel_SMS( 8402): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8402): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8402): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8402): MmsConfig.loadFromResources
,E/Babel_SMS( 8402): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8402): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8402): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8402): startup - clean
,I/Babel   ( 8402): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8429 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8402): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8402): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8402): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8402): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8402): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8402): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8402): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8402): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8402): onServiceConnected
W/Babel   ( 8402): Attempted to change video mute state without an active call.
,I/Babel   ( 8402): connection state changed from UNKNOWN to DISCONNECTED
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 8429): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8429):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8429):   adb logcat -s GAv4
,W/ContextImpl( 8429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  885): Killing 8312:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine(  885): [1,450,361,964,021 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e1f445c sup_state=SCANNING debouncing=false
E/WifiStateMachine(  885): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  885):  rewrite network history for "NG700"WPA_PSK
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_8312/cgroup.procs: No such file or directory
,E/WifiStateMachine(  885): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  885): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,W/GAv4    ( 8429): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8429): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8429): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiConfigStore(  885): will read network variables netId=0
,E/WifiStateMachine(  885): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  885): will read network variables netId=0
,I/wpa_supplicant( 8221): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 8221): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  885): setLastSelectedConfiguration -1
,E/wpa_supplicant( 8221): PNO: In assoc process
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/WebViewFactory( 8429): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8429): Time to load native libraries: 3 ms (timestamps 979-982)
,I/LibraryLoader( 8429): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8429): Binding Chromium to main looper Looper (main, tid 1) {24890396}
,I/LibraryLoader( 8429): Expected native library version number "",actual native library version number ""
I/chromium( 8429): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BrowserStartupController( 8429): Initializing chromium process, singleProcess=true
W/art     ( 8429): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8429): ApplicationContext is null in ApplicationStatus
,W/chromium( 8429): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8429): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8429): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8429): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8429): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8429): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8429): Local Branch: 
I/Adreno-EGL( 8429): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8429): Local Patches: NONE
I/Adreno-EGL( 8429): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 192 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 8221): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
D/Tethering(  885):  1
,D/Tethering(  885):  5
D/Tethering(  885):  7
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/AudioManagerAndroid( 8429): Requires BLUETOOTH permission
,I/NSApplication( 8429): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8499 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8340:com.android.mms/u0a23 (adj 15): empty #7
,I/wpa_supplicant( 8221): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 8221): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_8340/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine(  885): Start Dhcp Watchdog 3
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  885): do suspend false
,E/wpa_supplicant( 8221): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
E/wpa_supplicant( 8221): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0225a2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0225a2 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8519 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8366:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8366/cgroup.procs: No such file or directory
,D/BluetoothMapService( 2789): onReceive
,W/ResourcesManager( 8519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/DHCPCD  ( 8536): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 8536): version 5.5.6 starting
E/DHCPCD  ( 8536): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 8536): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 8536): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 8536): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 8536): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 8536): wlan0: sending REQUEST (xid 0x5db54a4), next in 4.48 seconds
,I/art     (  885): Explicit concurrent mark sweep GC freed 32444(1592KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.522ms total 120.774ms
,I/DHCPCD  ( 8536): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 8536): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 8536): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 8536): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 8536): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 8536): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
D/TCMD    (  480): Listening for incoming client connection request
,D/DHCPCD  ( 8536): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager(  885): Killing 8385:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8385/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2938): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2938): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2938): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2938): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2938): onServiceConnected()
D/GetNotificationsWS( 2938): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2938): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  885): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8580 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8402:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8402/cgroup.procs: No such file or directory
,W/ResourcesManager( 8580): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9407579:true
,I/ActivityManager(  885): Killing 8429:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_8429/cgroup.procs: No such file or directory
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/LocationInitializer( 8086): Restart initialization of location
,E/MDM     ( 1736): [174] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  885): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 102
D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  885): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  885):    accepting network in place of null
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8621 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 8086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8086): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:19:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361965579], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361965560]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
,D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
,W/IcingInternalCorpora( 8086): getNumBytesRead when not calculated.
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 73123(4MB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 14MB/24MB, paused 1.087ms total 122.064ms
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19a27e26)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24037a67)
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3770b014)
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@341940bd)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fa856b2)
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14c35603)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24b2b980)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d9e2bb9)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7c12bfe)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d1b4f5f)
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8662 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.710ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 357us total 19.498ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.784ms
,D/BluetoothManagerService(  885): Message: 20
,D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18fc88ff:true
,I/BTConnectionReceiver( 8662): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8692 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8662): Bluetooth Device Name: G4-1
,I/ActivityManager(  885): Killing 8499:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_8499/cgroup.procs: No such file or directory
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524295
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310817, SEQNUM=4701, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15725, POWER_SUPPLY_CHARGE_COUNTER=-1649, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/MDMCTBK (  310): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  310): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
,I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  310): set_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter,
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
,E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): now: 625148 ,futureTime: 9223372036854775807
D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2938): now: 625149 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2938): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2938): now: 625161 ,futureTime: 9223372036854775807
D/OtaApp  ( 2938): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8727 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2938): [debug] > PollingManagerService, now: 625209 ,futureTime: 75697361
D/OtaApp  ( 2938): [debug] > Polling alarm set to expire at: 75697361 Current Time: 625210
,D/Central_PollingManager( 1475): now: 625215 ,futureTime: 86478058
D/Central_PollingManager( 1475): Polling alarm set to expire at: 86478058 Current Time: 625215
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2938): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2938): set mOutstandingReq to true.
I/ Nonce  ( 2938):  Nonce getNonce 
I/ Nonce  ( 2938):  Nonce Request 
I/ Nonce  ( 2938):  Nonce execute Request 
,D/MMApiWebService( 2938): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/MusicStore( 8727): Database version: 120
,I/art     ( 2938): Explicit concurrent mark sweep GC freed 42059(2MB) AllocSpace objects, 7(135KB) LOS objects, 40% free, 11MB/19MB, paused 1.102ms total 78.392ms
,D/MMApiProvisionService( 2938): isDeviceProvisioned: deviceId = 2072049230914535424
,I/art     (  885): Explicit concurrent mark sweep GC freed 18160(902KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.570ms total 115.538ms
,D/CCE     ( 2938): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2938): createDeviceIdOrLogin update_device
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2938): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2938): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2938): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2938): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8727): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2938): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2938): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2938): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2938): generating token using payload instead of using session token
,D/ Nonce  ( 2938):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2938): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8727): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8727): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8727): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8727): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8727): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8727): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8727): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@279e30ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8727): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8727): GMSCore installation verified
,I/ConfigStore( 8727): Config Database version: 1
,I/MediaRouter( 8727): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 8727): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 8727): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8778 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8727): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8727): Using platform SSLCertificateSocketFactory
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 1566(54KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 452us total 23.053ms
,V/Mms     ( 8778): mnc/mcc: 
V/Mms     ( 8778): tag: int value: recipientLimit - 20
V/Mms     ( 8778): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8778): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8778): tag: int value: maxSubjectLength - 80
V/Mms     ( 8778): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 8778): tag: bool value: enableGroupMms - false
,I/ActivityManager(  885): Killing 8519:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,V/Mms     ( 8778):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8519/cgroup.procs: No such file or directory
,W/ResourcesManager( 8778): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8813 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8580:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_1000/pid_8580/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8813): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8813): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8813): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 8621:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8621/cgroup.procs: No such file or directory
,I/CheckinService( 8086): Checkin interval check for package: unspecified last checkin: 1450361693580 min interval config: 0 actual interval: 276064
,I/CheckinService( 8086): Disabling old GoogleServicesFramework version
,I/iu.Environment( 8086): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 8086): num queued entries: 0
,I/iu.UploadsManager( 8086): num updated entries: 0
,I/iu.SyncManager( 8086): NEXT; no task
,I/ Nonce  ( 2938):  Nonce Reponse 
D/        ( 2938): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"2767e4d8-8664-4c7f-8d6e-bf339d2f0672"}
D/MMApiWSBase( 2938): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2938):  Nonce Handle Reponse 
D/MMApiProvisionService( 2938): mOutstandingReq set to false
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8841 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 8086): Checking schedule, now: 1450361969717 next: 1450361723512
I/CheckinService( 8086): active receiver: enabled
,I/CheckinService( 8086): Preparing to send checkin request
,I/EventLogService( 8086): Accumulating logs since 1450361689934
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 5421(256KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 683us total 34.909ms
,D/MMApiProvisionService( 2938):  pTime 1450280700010 sExp 172742 cTime 1450361969852 tTime 1450453442010
D/MMApiProvisionService( 2938):  No login Required 
,I/CheckinRequestBuilder( 8086): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
,E/ActivityThread( 8086): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8871 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8662:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8662/cgroup.procs: No such file or directory
,W/ResourcesManager( 8871): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8888 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/DataUsage( 2938): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2938): publish the event [tag = MOT_CCE event name = LOG]
,W/ResourcesManager( 8888): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8888): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8888): VM with version 2.1.0 has multidex support
,I/MultiDex( 8888): install
,I/MultiDex( 8888): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8888): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8888): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8888): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19ea84d4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8888): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 8871): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8871): MmsConfig.loadMmsSettings
I/Babel_SMS( 8871): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8871): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8871): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8871): MmsConfig.loadFromResources
E/Babel_SMS( 8871): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8871): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  885): Explicit concurrent mark sweep GC freed 9880(497KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.928ms total 116.287ms
,I/art     ( 8888): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8888): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 8871): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8871): startup - clean
,I/Babel   ( 8871): deleted: false for 0
,D/NativeLibraryUtils( 8888): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8918 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  312): Instantiating CDM.
I/WVCdm   (  312): CdmEngine::OpenSession
I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xb5569960
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb742ee30, dataLength=8
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74e7538, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb7540588, idLength=0xb5469730
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
D/WVCdm   (  312): PrepareKeyRequest: nonce=1289534954
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb742a150
D/DrmWidevineDash(  312): message_length=1591, signature=0xb742f1c8, signature_length=3041302292
,W/VideoCapabilities( 8871): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8871): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8871): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8871): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8871): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8871): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8871): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8871): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 8918): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8918):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8918):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8918): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8918): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/vclib   ( 8871): onServiceConnected
W/Babel   ( 8871): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 8918): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 8918): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8918): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8918): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 8871): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 8692:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/GAv4    ( 8918): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
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
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8692/cgroup.procs: No such file or directory
,I/dex2oat ( 8951): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8951): dex2oat took 66.087ms (threads: 4)
,I/Adreno-EGL( 8888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8888): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8888): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8888): Local Branch: 
I/Adreno-EGL( 8888): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8888): Local Patches: NONE
I/Adreno-EGL( 8888): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 8918): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8918): Time to load native libraries: 2 ms (timestamps 8008-8010)
I/LibraryLoader( 8918): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8918): Binding Chromium to main looper Looper (main, tid 1) {2d22cb04}
,I/LibraryLoader( 8918): Expected native library version number "",actual native library version number ""
I/chromium( 8918): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 8888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8888): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8888): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8888): Local Branch: 
I/Adreno-EGL( 8888): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8888): Local Patches: NONE
I/Adreno-EGL( 8888): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BrowserStartupController( 8918): Initializing chromium process, singleProcess=true
,W/art     ( 8918): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8918): ApplicationContext is null in ApplicationStatus
,W/chromium( 8918): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 8918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8918): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8918): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8918): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8918): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8918): Local Branch: 
I/Adreno-EGL( 8918): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8918): Local Patches: NONE
I/Adreno-EGL( 8918): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 8918): Starting up...
,W/AudioManagerAndroid( 8918): Requires BLUETOOTH permission
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8992 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8727:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_8727/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9011 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8778:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_8778/cgroup.procs: No such file or directory
,W/ResourcesManager( 9011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  312): CdmEngine::OpenSession
,I/WVCdm   (  312): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  312): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  312): Loaded image: APP id = 3
,D/DrmWidevineDash(  312): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  312): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
E/DrmWidevineDash(  312): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f8e000
,D/DrmWidevineDash(  312): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  312): hlos api version =  9
D/DrmWidevineDash(  312): tz api version =  8
D/DrmWidevineDash(  312): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  312): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  312): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: starts! SID=0xbef8a4e0
D/DrmWidevineDash(  312): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  312): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: starts! randomData=0xb742dd78, dataLength=8
D/DrmWidevineDash(  312): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74e7538, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  312): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  312): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  312): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  312): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  312): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  312): OEMCrypto_GetDeviceID: starts! deviceID=0xb75405c8, idLength=0xbef8a2b0
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
D/WVCdm   (  312): PrepareKeyRequest: nonce=608160282
D/DrmWidevineDash(  312): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb742a150
D/DrmWidevineDash(  312): message_length=1626, signature=0xb742ef40, signature_length=3203965588
,I/ActivityManager(  885): Killing 8813:com.google.android.setupwizard/u0a35 (adj 15): empty #7
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
,I/Adreno-EGL( 8888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8888): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8888): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8888): Local Branch: 
I/Adreno-EGL( 8888): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8888): Local Patches: NONE
I/Adreno-EGL( 8888): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8813/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2938): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2938): bindWebServices(): registering our AIDL callback...
,I/Adreno-EGL( 8888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8888): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8888): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8888): Local Branch: 
I/Adreno-EGL( 8888): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8888): Local Patches: NONE
I/Adreno-EGL( 8888): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SundryService( 2938): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2938): onServiceConnected()
D/GetNotificationsWS( 2938): onServiceConnected(): Registered for remote service callbacks...
D/OtaApp  ( 2938): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
D/WaitableIntentService( 2938): ServiceHandler.handleMessage: mWaitCount=0
D/OtaApp  ( 2938): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2938): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2938): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2938): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2938): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2938): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2938): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2938): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2938): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2938): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2938): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,E/MDM     ( 1736): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/CheckinRequestBuilder( 8086): Classify the device as Phone.
,D/LocationInitializer( 8086): Restart initialization of location
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,I/CheckinTask( 8086): Sending checkin request (9515 bytes)
,I/CheckinRequestBuilder( 8086): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 8086): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 8086): Classify the device as Phone.
,I/CheckinTask( 8086): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 8086): Checking schedule, now: 1450361973915 next: 1450963110906
I/CheckinService( 8086): active receiver: disabled
,D/CheckinService( 8086): Recording last checkin time for package unspecified as 1450361973926
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9078 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 26.036ms
,D/PhoneMonitor( 9078): Register our PhoneStateListener
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.637ms
,V/SetupWizard( 9078): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 8918:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.208ms
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_8918/cgroup.procs: No such file or directory
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ProcessCpuTracker(  885): Skipping unknown process pid 9067
,W/ProcessCpuTracker(  885): Skipping unknown process pid 9068
W/ProcessCpuTracker(  885): Skipping unknown process pid 9077
W/ProcessCpuTracker(  885): Skipping unknown process pid 9101
,I/MDMCTBK (  310): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  310): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
,I/MDMCTBK (  310): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  310): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  310): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  885): Killing 8992:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_8992/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 9011:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_9011/cgroup.procs: No such file or directory
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9104 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1583): Deferring update until onResume
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1998351b
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9141 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9163 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8841:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8841/cgroup.procs: No such file or directory
,W/ResourcesManager( 8871): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8871): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8871): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8871): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8871): Installed default security provider GmsCore_OpenSSL
,I/art     (  885): Explicit concurrent mark sweep GC freed 19634(1002KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.130ms total 123.315ms
,W/asset   ( 9163): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9163): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9163): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9163): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f8a9ee5 new=com.google.android.velvet.VelvetApplication@3f8a9ee5
,I/UpdateIcingCorporaServi( 9104): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 8086): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9191 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 8086): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 9191): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 8086): Storage manager: low false usage 1.76MB avail 3.12GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 9104): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9230 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Waited long enough for: ServiceRecord{25922459 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ActivityManager(  885): Killing 9078:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 8086): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_9078/cgroup.procs: No such file or directory
,D/Finsky  ( 9230): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 8086): Internal init done: storage state 0
,I/Icing   ( 8086): Post-init done
,I/Icing   ( 8086): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 9230): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9230): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 9230): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 9230): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 9230): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 9230): Skipping gmscore version check
,D/Finsky  ( 9230): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 9230): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 8888:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_8888/cgroup.procs: No such file or directory
,I/Icing   ( 8086): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 8086): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 8086): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 9141:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_9141/cgroup.procs: No such file or directory
,W/SQLiteConnectionPool( 8086): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  885): Killing 8871:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8871/cgroup.procs: No such file or directory
,I/MDMCTBK (  310): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  310): NetlinkHandler, interfaceAdded
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
E/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  310): , Wifi = 0
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/CheckinService( 8086): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  310): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  310): NetlinkHandler, interfaceAdded
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
E/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  310): , Wifi = 0
I/MDMCTBK (  310): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  310): set_property_value, Exit
,I/MDMCTBK (  310): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  310): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  310): set_property_value, Enter
I/MDMCTBK (  310): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  310): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  310): set_property_value, Exit
E/MDMCTBK (  310): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e2bcdd7:true
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311194, SEQNUM=4732, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-1775, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 2789): info:x10
,D/        ( 2789): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,D/btif_config_util( 2789): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2789): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2789): onReceive
,I/BTConnectionReceiver( 9104): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 9104): Bluetooth Device Name: A3-1
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310754, SEQNUM=4734, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-2098, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {2cd44a42, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  885): send {ca856c4, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  885): done {2cd44a42, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [44ms]
,V/AlarmManager(  885): done {ca856c4, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [50ms]
,I/EventLogService( 8086): Aggregate from 1450361969851 (log), 1450360451217 (data)
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {277263a9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  885): cleanup(): cleared. Last call was 620096 ms ago
I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=9320 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [98ms]
,I/GAv4    ( 9320): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9320):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9320):   adb logcat -s GAv4
,W/GAv4    ( 9320): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9320): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9320): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {277263a9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [249ms]
,I/ActivityManager(  885): Killing 9163:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_9163/cgroup.procs: No such file or directory
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {23c81d2e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  885): done {23c81d2e, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [91ms]
,I/GoogleURLConnFactory( 1736): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1736): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,W/PhenotypeConfigurator( 1736): Server returned 404
,I/art     (  885): Explicit concurrent mark sweep GC freed 17934(918KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/30MB, paused 1.769ms total 123.715ms
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310637, SEQNUM=4748, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-565, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {2cd44a42, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {2cd44a42, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310045, SEQNUM=4749, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-552, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2789): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310629, SEQNUM=4750, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310343, SEQNUM=4752, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310633, SEQNUM=4753, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  310): NetlinkHandler, power_supply subsys
I/MDMCTBK (  310): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  310): checkDefaultInst, current pid is = 310
I/MDMCTBK (  310): checkDefaultInst, pid match
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  310): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  310): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {32faeccf, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {21294928, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  885): send {3f5eb060, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  885): Prepared write state in 12ms
,I/ProcessStatsService(  885): Prepared write state in 6ms
,V/AlarmManager(  885): done {21294928, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [64ms]
,V/AlarmManager(  885): done {32faeccf, *alarm*:android.intent.action.TIME_TICK} [89ms]
,V/AlarmManager(  885): done {3f5eb060, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [91ms]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  885): Pruning old procstats: /data/system/procstats/state-2015-12-16-20-30-31.bin
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 9412): 
D/AndroidRuntime( 9412): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9412): CheckJNI is OFF
D/AndroidRuntime( 9412): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10387 user=-1: uninstall pkg
I/ActivityManager(  885):   Force finishing activity ActivityRecord{27f1cc78 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  885): Skipping PackageSetting{288c2e8 com.example.hello/10377} due to missing metadata
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10387 user=0: pkg removed
I/art     ( 3341): Explicit concurrent mark sweep GC freed 16854(2MB) AllocSpace objects, 33(528KB) LOS objects, 39% free, 7MB/12MB, paused 784us total 37.435ms
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1423): resetDictionaries() : en_US
D/VoicemailCleanupService( 1627): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9441 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1423): run()
I/art     ( 1583): Explicit concurrent mark sweep GC freed 2987(158KB) AllocSpace objects, 5(240KB) LOS objects, 24% free, 13MB/17MB, paused 3.115ms total 134.706ms
I/Decoder ( 1423): createOrResetDecoder
I/art     (  885): Explicit concurrent mark sweep GC freed 14241(1096KB) AllocSpace objects, 6(185KB) LOS objects, 33% free, 20MB/30MB, paused 2.223ms total 169.937ms
I/art     (  885): WaitForGcToComplete blocked for 40.846ms for cause Explicit
W/asset   ( 9441): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9441): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9441): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9441): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ConfigService( 1736): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): run()
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=9468 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1423): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = contacts
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  885): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  885): Killing 9191:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1423): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1423): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1423): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1423): run()
I/StatsUtilsManager( 1423): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1423): shouldRecordStats() = Too Soon
I/art     (  885): Explicit concurrent mark sweep GC freed 5989(313KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.960ms total 224.168ms
W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_9191/cgroup.procs: No such file or directory
I/Launcher( 1583): Deferring update until onResume
W/ContextImpl( 9468): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 8086): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 8086): Reading stored module config
D/AccountUtils( 8086): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 8086): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8086): Loading module APK com.google.android.play.games
D/AndroidRuntime( 9412): Shutting down VM
I/LocationSettingsChecker( 8086): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 8086): App measurement is starting up, version: 8489
I/GMPM-SVC( 8086): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/Launcher( 1583): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f8a9ee5 new=com.google.android.velvet.VelvetApplication@3f8a9ee5
D/gH_CompatibleDatabase( 8086): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 8086): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 8086): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 8086): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 8086): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 8086): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 8086): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 8086): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 8086): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 8086): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 8086): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 8086): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 8086): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9499 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 9104): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Icing   ( 8086): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 8086): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8086): Module APK com.google.android.play.games already loaded
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
E/BaseAppContext( 8086): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
E/ConnectivityChangeReceiver( 8086): Ignoring connectivity change
D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  885): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 8086): CM callback handler got msg 524290
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/BaseAppContext( 8086): Using Auth Proxy for data requests.
W/DriveInitializer( 8086): Awaiting to be initialized
W/DriveInitializer( 8086): Background init thread started
I/PeopleDatabaseHelper( 8086): cleanUpNonGplusAccounts done.
I/GAv4    ( 9499): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9499):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9499):   adb logcat -s GAv4
W/GAv4    ( 9499): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 9499): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 8086): WaitForGcToComplete blocked for 19.375ms for cause Explicit
W/GAv4    ( 9499): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 9499): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/art     ( 8086): Explicit concurrent mark sweep GC freed 3302(146KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 13MB/17MB, paused 1.028ms total 66.561ms
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8086): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
I/UpdateIcingCorporaServi( 9104): UpdateCorporaTask done [took 934 ms] updated apps [took 934 ms] 
W/DriveInitializer( 8086): Background init thread ended
I/art     ( 3516): Explicit concurrent mark sweep GC freed 1469(51KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 457us total 23.632ms
W/FileUtils( 9499): Failed to chmod(/data/data/com.google.android.apps.docs/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 1736): (14) cannot open file at line 28604 of [9491ba7d73]
E/SQLiteLog( 1736): (14) os_unix.c:28604: (30) open(/data/data/com.google.android.gms/databases/playlog.db-shm) - 
E/SQLiteLog( 1736): (14) unable to open database file
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9499): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
E/AbstractDatabaseInstance( 9499): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 9499): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AbstractDatabaseInstance( 9499): 	at android.database.sqlite.SQLiteDatabase.enableWriteAheadLogging(SQLiteDatabase.java:1958)
E/AbstractDatabaseInstance( 9499): 	at aev.getWritableDatabase(PG:20264)
E/AbstractDatabaseInstance( 9499): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 9499): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 9499): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 9499): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 9499): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 9499): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 9499): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 9499): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 9499): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 9499): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 9499): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1736): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1736): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA journal_mode
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:889)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:634)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:320)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:291)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:215)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1736): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1736): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1736): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1736): unable to open database file (code 14): , while compiling: PRAGMA journal_mode
E/ClearcutLoggerIntentService( 1736): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA journal_mode
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:889)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:634)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:320)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:291)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:215)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 1736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearcutLoggerIntentService( 1736): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1736): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1736): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1736): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1736): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1736): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1736): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1736): 	at java.lang.Thread.run(Thread.java:818)
E/ClearcutLoggerIntentService( 1736): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearcutLoggerIntentService( 1736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/ClearcutLoggerIntentService( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.playlog.store.r.d(SourceFile:97)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:155)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearcutLoggerIntentService( 1736): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1736): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1736): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1736): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 9499): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9499): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9558 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 9230:com.android.vending/u0a32 (adj 15): empty #7
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
