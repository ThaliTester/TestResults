#### Test 575312431745da8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6618): 
D/AndroidRuntime( 6618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6618): CheckJNI is OFF
D/AndroidRuntime( 6618): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6637 uid=10506 gids={50506, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6618): Shutting down VM
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6637): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6637): Time to load native libraries: 15 ms (timestamps 7290-7305)
,I/LibraryLoader( 6637): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6637): Binding Chromium to main looper Looper (main, tid 1) {2f987f29}
I/LibraryLoader( 6637): Expected native library version number "",actual native library version number ""
,I/chromium( 6637): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6637): Initializing chromium process, singleProcess=true
,W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6637): ApplicationContext is null in ApplicationStatus
,W/chromium( 6637): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6637): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6637): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6637): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6637): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6637): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6637): Local Branch: 
I/Adreno-EGL( 6637): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6637): Local Patches: NONE
I/Adreno-EGL( 6637): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@267d5525:true
,W/ActivityManager(  879): Activity pause timeout for ActivityRecord{32012e16 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6637): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6637): CordovaWebView is running on device made by: motorola
,W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6637): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6637): Render dirty regions requested: true
,D/Atlas   ( 6637): Validating map...
,W/chromium( 6637): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6637): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6637): Enabling debug mode 0
,I/Keyboard.Facilitator( 1415): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,954
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +884ms (total +954ms)
,W/IInputConnectionWrapper( 6637): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6637): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6637): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6637): Cannot call determinedVisibility() - never saw a connection for the pid: 6637
,D/JsMessageQueue( 6637): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6637): JniHelper::setJavaVM(0xb783f310), pthread_self() = -1212353352
,I/chromium( 6637): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6637): Initializing JXcore engine
W/jxcore-log( 6637): JXcore engine is ready
,I/art     ( 6637): Background partial concurrent mark sweep GC freed 21091(995KB) AllocSpace objects, 2(2MB) LOS objects, 39% free, 16MB/27MB, paused 8.914ms total 51.975ms
,W/Thread-808( 6686): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10506 path="socket:[9368]" dev="sockfs" ino=9368 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-808( 6686): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10506 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-808( 6686): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10506 path="socket:[6716]" dev="sockfs" ino=6716 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-808( 6686): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10506 path="socket:[31006]" dev="sockfs" ino=31006 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6637): Starting JXcore engine
,W/jxcore-log( 6637): Platform android
W/jxcore-log( 6637): 
,W/jxcore-log( 6637): Process ARCH arm
W/jxcore-log( 6637): 
,I/jxcore-log( 6637): JXcore Cordova bridge is ready!
I/jxcore-log( 6637): 
W/jxcore-log( 6637): JXcore engine is started
,I/jxcore-log( 6637): Toggling radios to true
I/jxcore-log( 6637): 
,D/BluetoothAdapter( 6637): enable(): BT is already enabled..!
,D/WifiService(  879): New client listening to asynchronous messages
,D/WifiService(  879): setWifiEnabled: true pid=6637, uid=10506
E/WifiService(  879): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6637): Radios toggled
I/jxcore-log( 6637): 
I/jxcore-log( 6637): My device name is: motorola-XT1072
I/jxcore-log( 6637): 
,I/wpa_supplicant( 1432): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
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
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
I/MDMCTBK (  294): set_property_value, Enter
D/TCMD    (  479): NL - message type is RTM_NEWLINK
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1432): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1432): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  879): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  879): InitialState.processMessage what=4
,W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
D/Tethering(  879):  0
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
,E/wpa_supplicant( 1432): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiP2pService(  879): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  879): sendTetherStateChangedBroadcast 0, 0, 0
,D/CommandListener(  292): Clearing all IP addresses on wlan0
D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 21
D/TCMD    (  479): Listening for incoming client connection request
,V/NativeCrypto( 1704): Read error: ssl=0xb7b80338: I/O error during system call, Connection timed out
,V/NativeCrypto( 1704): SSL shutdown failed: ssl=0xb7b80338: I/O error during system call, Broken pipe
,D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-5ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info<unknown ssid>
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6698 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  879): connected time updated 219979
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/wpa_supplicant( 1432): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  879): Start Disconnecting Watchdog 1
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1432): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  879): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1432): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6698): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  292): Clearing all IP addresses on wlan0
D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
,D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1961): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1516): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1516): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1516): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1516): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1516): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1516): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  879): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6698): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6698): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6698): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6698): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6698): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6698): MmsConfig.loadFromResources
,E/Babel_SMS( 6698): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6698): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6698): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6698): startup - clean
,I/Babel   ( 6698): deleted: false for 0
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/wpa_supplicant( 1432): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1432): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
,D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  879): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  879): [1,454,593,225,627 ms] noteScanEnd no scan source
E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@eff8cd sup_state=SCANNING debouncing=false
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6739 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/TCMD    (  479): NL - Read 312 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 192 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
I/wpa_supplicant( 1432): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/Tethering(  879): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  0
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1432): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1432): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
,D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
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
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223660064
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Tethering(  879): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  879): Network connection established
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  879): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  879): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  879): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  879): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  292): Setting iface cfg
E/WifiStateMachine(  879): Start Dhcp Watchdog 2
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend false
E/wpa_supplicant( 1432): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  879): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1432): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  879): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@192e26d2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@192e26d2 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6698): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6698): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6698): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6698): Unsupported profile 4 for video/mp4v-es
,I/art     (  879): Explicit concurrent mark sweep GC freed 33045(1714KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.692ms total 160.461ms
,W/ResourcesManager( 6739): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
W/VideoCapabilities( 6698): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6698): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6698): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6698): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Killing 6218:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/DHCPCD  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6758): version 5.5.6 starting
,E/DHCPCD  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6758): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6758): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_6218/cgroup.procs: No such file or directory
,I/vclib   ( 6698): onServiceConnected
W/Babel   ( 6698): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6758): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6758): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6758): wlan0: sending REQUEST (xid 0x30bba8d9), next in 4.36 seconds
,I/ActivityManager(  879): Killing 6421:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6421/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6758): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6758): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6758): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6758): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6758): wlan0: adding default route via 192.168.1.1
D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 20
D/DHCPCD  ( 6758): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  479): Listening for incoming client connection request
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/DHCPCD  ( 6758): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  879): WifiStateMachine DHCP successful
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  879): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  879): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  879): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  879): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  879): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  879): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  879): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  879): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  879): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  879): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879):    accepting network in place of null
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-13ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG700"
D/CSLegacyTypeTracker(  879): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1516): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1516): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1516): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1961): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:40:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454593228253], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454593228228]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
D/ConnectivityService(  879): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1961): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1516): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1516): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1516): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1516): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2586): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6818 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2586): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2586): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2586): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2586): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1467): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2586): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2586): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2586): [debug] > CusSM.onRadioDown
,D/CCE     ( 2586): Registering with Alarm Manager to restart CCE
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524295
D/CCE     ( 2586): Registering with Alarm Manager to restart CCE
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityManager.CallbackHandler( 1961): CM callback handler got msg 524295
,D/CCE     ( 2586): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6818): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6818): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6818): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6818): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6818): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6818): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6818): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6818): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6818): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11ef5b15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6818): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6818): GMSCore installation verified
,I/ConfigStore( 6818): Config Database version: 1
,I/MediaRouter( 6818): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6818): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6818): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6818): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6850 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6818): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6818): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6476:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/ConnectivityService(  879): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6476/cgroup.procs: No such file or directory
,V/Mms     ( 6850): mnc/mcc: 
,V/Mms     ( 6850): tag: int value: recipientLimit - 20
V/Mms     ( 6850): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6850): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6850): tag: int value: maxSubjectLength - 80
V/Mms     ( 6850): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6850): tag: bool value: enableGroupMms - false
,V/Mms     ( 6850):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6850): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6886 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6316:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6886): Register our PhoneStateListener
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_6316/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6886): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6886): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 6698:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6698/cgroup.procs: No such file or directory
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593048453 min interval config: 0 actual interval: 181603
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6908 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 1961): Checking schedule, now: 1454593230136 next: 1454593078428
I/CheckinService( 1961): active receiver: enabled
,I/CheckinService( 1961): Preparing to send checkin request
I/EventLogService( 1961): Accumulating logs since 1454593045400
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6934 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,W/ResourcesManager( 6934): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6934): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6934): VM with version 2.1.0 has multidex support
I/MultiDex( 6934): install
I/MultiDex( 6934): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6953 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.200ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 18.828ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.145ms
,V/JNIHelp ( 6934): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityThread( 6934): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6934): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a66a772: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6934): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6934): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6934): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6934): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6953): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6953): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6953): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6953): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6953): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6953): MmsConfig.loadFromResources
,E/Babel_SMS( 6953): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6953): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f75000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f75000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  879): MasterInitialState.processMessage what=3
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb1282960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb88a05a8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88419e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2586): now: 297125 ,futureTime: 9223372036854775807
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8970d48, idLength=0xb5547730
D/PollingManager( 2586): now: 297125 ,futureTime: 9223372036854775807
D/PollingManager( 2586): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2586): now: 297125 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2586): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1467): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/Central_PollingManager( 1467): now: 297134 ,futureTime: 86476418
D/Central_PollingManager( 1467): Polling alarm set to expire at: 86476418 Current Time: 297134
D/OtaApp  ( 2586): [debug] > PollingManagerService, now: 297133 ,futureTime: 28472507
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3194151874
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb88269d0
D/DrmWidevineDash(  296): message_length=1591, signature=0xb88ab3d0, signature_length=3042211604
D/OtaApp  ( 2586): [debug] > Polling alarm set to expire at: 28472507 Current Time: 297134
D/OtaApp  ( 2586): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2586): [debug] > CusSM.onRadioUp
I/NetworkMonitor( 6818): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2586): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2586): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2586): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2586): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2586): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2586): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiProvisionService( 2586): isDeviceProvisioned: deviceId = 2072049230914535424
,W/art     ( 6953): Suspending all threads took: 7.285ms
,I/art     (  879): Explicit concurrent mark sweep GC freed 24216(1176KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.539ms total 137.156ms
,D/CCE     ( 2586): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2586): createDeviceIdOrLogin update_device
,D/Checkin ( 2586): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2586): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2586): isDeviceProvisioned: deviceId = 2072049230914535424
D/CCE     ( 2586): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2586): createDeviceIdOrLogin update_device
D/Checkin ( 2586): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2586): isDeviceProvisioned: deviceId = 2072049230914535424
D/MMApiProvisionService( 2586): set mOutstandingReq to true.
I/ Nonce  ( 2586):  Nonce getNonce 
I/ Nonce  ( 2586):  Nonce Request 
I/ Nonce  ( 2586):  Nonce execute Request 
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
,D/MMApiWebService( 2586): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1467): Explicit concurrent mark sweep GC freed 5194(239KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 763us total 41.936ms
,W/Settings( 6953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MMApiProvisionService( 2586): isDeviceProvisioned: deviceId = 2072049230914535424
I/Babel_Crash( 6953): startup - clean
I/dex2oat ( 6990): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/CCE     ( 2586): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2586): createDeviceIdOrLogin update_device
I/Babel   ( 6953): deleted: false for 0
D/Checkin ( 2586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2586): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2586): generating token using payload instead of using session token
,I/dex2oat ( 6990): dex2oat took 84.503ms (threads: 4)
,I/Adreno-EGL( 6934): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6934): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6934): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6934): Local Branch: 
I/Adreno-EGL( 6934): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6934): Local Patches: NONE
I/Adreno-EGL( 6934): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6999 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 6934): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6934): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6934): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6934): Local Branch: 
I/Adreno-EGL( 6934): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6934): Local Patches: NONE
I/Adreno-EGL( 6934): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/VideoCapabilities( 6953): Unrecognized profile 2130706433 for video/avc
,I/art     ( 2586): Explicit concurrent mark sweep GC freed 12369(728KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 2.544ms total 161.016ms
,D/ Nonce  ( 2586):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
I/MMApiWSBase( 2586): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2586): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioCapabilities( 6953): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6953): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6953): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6953): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6953): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6953): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6953): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6953): onServiceConnected
,W/Babel   ( 6953): Attempted to change video mute state without an active call.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/Babel   ( 6953): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  879): Killing 6739:com.motorola.context/u0a8 (adj 15): empty #7
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f75000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f75000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb1382960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb88268c8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb892f8e8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8970d88, idLength=0xb5547730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=1859968941
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8825080
D/DrmWidevineDash(  296): message_length=1626, signature=0xb88a2af8, signature_length=3042211604
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_6739/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
W/ContextImpl( 6999): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6999): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6999): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6999): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6999): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6999):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6999):   adb logcat -s GAv4
,W/GAv4    ( 6999): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6999): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6999): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  879): send {e8c0689, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  879): send {d5a3a18, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  879): done {e8c0689, *alarm*:android.intent.action.TIME_TICK} [33ms]
,I/Adreno-EGL( 6934): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6934): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6934): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6934): Local Branch: 
I/Adreno-EGL( 6934): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6934): Local Patches: NONE
I/Adreno-EGL( 6934): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 6999): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6999): Time to load native libraries: 1 ms (timestamps 8544-8545)
I/LibraryLoader( 6999): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6999): Binding Chromium to main looper Looper (main, tid 1) {27d3d122}
,I/LibraryLoader( 6999): Expected native library version number "",actual native library version number ""
,I/chromium( 6999): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 6934): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6934): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6934): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6934): Local Branch: 
I/Adreno-EGL( 6934): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6934): Local Patches: NONE
I/Adreno-EGL( 6934): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BrowserStartupController( 6999): Initializing chromium process, singleProcess=true
,W/art     ( 6999): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6999): ApplicationContext is null in ApplicationStatus
,W/chromium( 6999): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6999): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6999): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6999): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6999): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6999): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6999): Local Branch: 
I/Adreno-EGL( 6999): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6999): Local Patches: NONE
I/Adreno-EGL( 6999): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6999): Starting up...
,W/AudioManagerAndroid( 6999): Requires BLUETOOTH permission
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7065 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6818:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6637): 
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/ Nonce  ( 2586):  Nonce Reponse 
D/        ( 2586): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"1668e5ac-9632-49e1-95df-79a16217fbc4"}
D/MMApiWSBase( 2586): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2586):  Nonce Handle Reponse 
D/MMApiProvisionService( 2586): mOutstandingReq set to false
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_6818/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2586):  pTime 1454523349198 sExp 172742 cTime 1454593232938 tTime 1454696091198
D/MMApiProvisionService( 2586):  No login Required 
,I/CheckinTask( 1961): Sending checkin request (9534 bytes)
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7088 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6850:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_6850/cgroup.procs: No such file or directory
,W/ResourcesManager( 7088): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/DataUsage( 2586): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2586): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7118 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6908:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
,I/ContactLocale( 7118): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 6886:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6637): 
,I/jxcore-log( 6637): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6637): 
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_6908/cgroup.procs: No such file or directory
,E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_6886/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7151 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7151): Database version: 120
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/art     (  879): Explicit concurrent mark sweep GC freed 9093(449KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.681ms total 113.220ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7151): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 1961): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1961): Checking schedule, now: 1454593234402 next: 1455194371384
I/CheckinService( 1961): active receiver: disabled
,D/CheckinService( 1961): Recording last checkin time for package unspecified as 1454593234417
,I/ActivityManager(  879): Killing 6953:com.google.android.talk/u0a70 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7151): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7151): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6953/cgroup.procs: No such file or directory
,W/ResourcesManager( 7151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7151): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11ef5b15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7151): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7151): GMSCore installation verified
,I/ConfigStore( 7151): Config Database version: 1
,I/MediaRouter( 7151): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7151): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7151): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Killing 6999:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  879): failed to kill 1 processes for processgroup 6999
,I/NetworkMonitor( 7151): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7198 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7151): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7151): Using platform SSLCertificateSocketFactory
,I/art     ( 6523): Explicit concurrent mark sweep GC freed 1541(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 364us total 30.082ms
,V/Mms     ( 7198): mnc/mcc: 
V/Mms     ( 7198): tag: int value: recipientLimit - 20
,V/Mms     ( 7198): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7198): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7198): tag: int value: maxSubjectLength - 80
V/Mms     ( 7198): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7198): tag: bool value: enableGroupMms - false
,V/Mms     ( 7198):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  879): Killing 7065:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7065/cgroup.procs: No such file or directory
,W/ResourcesManager( 7198): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7234 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7088:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7088/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7234): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7234): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7234): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 7118:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7118/cgroup.procs: No such file or directory
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593234417 min interval config: 0 actual interval: 1795
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7256 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1961): Checking schedule, now: 1454593236271 next: 1454593264384
I/CheckinService( 1961): active receiver: disabled
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7273 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7151:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_7151/cgroup.procs: No such file or directory
,W/ResourcesManager( 7273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7273): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7273): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7273): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7273): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7273): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7273): MmsConfig.loadFromResources
,E/Babel_SMS( 7273): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7273): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7273): startup - clean
,I/Babel   ( 7273): deleted: false for 0
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7300 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7273): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7273): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7273): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7273): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7273): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7273): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7273): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7273): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7273): onServiceConnected
W/Babel   ( 7273): Attempted to change video mute state without an active call.
,I/GAv4    ( 7300): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7300):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7300):   adb logcat -s GAv4
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7300): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7300): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7300): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 7273): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7300): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/ActivityManager(  879): Killing 7198:com.android.mms/u0a23 (adj 13): empty #7
,W/ContextImpl( 7300): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7300): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7300): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7198/cgroup.procs: No such file or directory
,I/WebViewFactory( 7300): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7300): Time to load native libraries: 1 ms (timestamps 3808-3809)
,I/LibraryLoader( 7300): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7300): Binding Chromium to main looper Looper (main, tid 1) {27d3d122}
,I/LibraryLoader( 7300): Expected native library version number "",actual native library version number ""
,I/chromium( 7300): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7300): Initializing chromium process, singleProcess=true
W/art     ( 7300): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7300): ApplicationContext is null in ApplicationStatus
,W/chromium( 7300): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7300): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7300): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7300): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7300): Local Branch: 
I/Adreno-EGL( 7300): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7300): Local Patches: NONE
I/Adreno-EGL( 7300): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7300): Requires BLUETOOTH permission
,I/NSApplication( 7300): Starting up...
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7368 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7234:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.682ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.308ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20ms
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7234/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7387 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7256:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7256/cgroup.procs: No such file or directory
,W/ResourcesManager( 7387): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311421, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-1215, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7407 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7300:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7407): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  879): failed to kill 1 processes for processgroup 7300
,I/ActivityManager(  879): Killing 7273:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7273/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2586): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2586): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2586): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2586): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2586): onServiceConnected()
,D/GetNotificationsWS( 2586): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2586): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7441 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2586): started with background data enabled, making sure notification mechanism is enabled
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1961): Restart initialization of location
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7467 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  879): Explicit concurrent mark sweep GC freed 13276(681KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.913ms total 120.492ms
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,E/MDM     ( 1704): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1704): No location to return for getLastLocation()
W/FusedLocationProvider( 1704): location=null
,I/MusicStore( 7467): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7467): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7467): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7467): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11ef5b15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7467): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7467): GMSCore installation verified
,I/ConfigStore( 7467): Config Database version: 1
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/MediaRouter( 7467): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7467): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7467): type=WIFI subType= reason=null isConnected=true
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36c72f71
,I/NetworkMonitor( 7467): type=WIFI subType= reason=null isConnected=true
,I/GCoreNlp( 1704): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7513 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/GHttpClientFactory( 7467): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/Launcher( 1569): Deferring update until onResume
,I/GoogleURLConnFactory( 7467): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6934:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7513): mnc/mcc: 
,V/Mms     ( 7513): tag: int value: recipientLimit - 20
V/Mms     ( 7513): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7513): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7513): tag: int value: maxSubjectLength - 80
V/Mms     ( 7513): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7513): tag: bool value: enableGroupMms - false
,V/Mms     ( 7513):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 1704): Background sticky concurrent mark sweep GC freed 106666(5MB) AllocSpace objects, 21(359KB) LOS objects, 28% free, 15MB/22MB, paused 1.085ms total 103.357ms
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5032368)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@218ff381)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d422c26)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a049067)
E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e9b0e14)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1dc746bd)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1894e4b2)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28bfcc03)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1724f780)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b2691b9)
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_6934/cgroup.procs: No such file or directory
,W/ResourcesManager( 7513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7540 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7368:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7368/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7540): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7540): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7540): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 7387:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7387/cgroup.procs: No such file or directory
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593234417 min interval config: 0 actual interval: 6911
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7571 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/CheckinService( 1961): Checking schedule, now: 1454593241387 next: 1454593264384
,I/CheckinService( 1961): active receiver: disabled
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593234417 min interval config: 0 actual interval: 7023
,I/CheckinService( 1961): Checking schedule, now: 1454593241456 next: 1454593264384
I/CheckinService( 1961): active receiver: disabled
,W/ResourcesManager( 7571): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7571): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7571): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7571): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7571): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7571): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7571): MmsConfig.loadFromResources
E/Babel_SMS( 7571): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7571): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7571): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7571): startup - clean
,I/Babel   ( 7571): deleted: false for 0
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7603 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7571): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7571): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7571): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7571): Unsupported profile 4 for video/mp4v-es
,I/GAv4    ( 7603): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7603):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7603):   adb logcat -s GAv4
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7571): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7571): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7571): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7571): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7603): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/vclib   ( 7571): onServiceConnected
W/Babel   ( 7571): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7603): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7603): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7571): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  879): Killing 7407:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7407/cgroup.procs: No such file or directory
,I/WebViewFactory( 7603): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7603): Time to load native libraries: 2 ms (timestamps 8559-8561)
I/LibraryLoader( 7603): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7603): Binding Chromium to main looper Looper (main, tid 1) {27d3d122}
,I/LibraryLoader( 7603): Expected native library version number "",actual native library version number ""
I/chromium( 7603): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7603): Initializing chromium process, singleProcess=true
W/art     ( 7603): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7603): ApplicationContext is null in ApplicationStatus
,W/chromium( 7603): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7603): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7603): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7603): Local Branch: 
I/Adreno-EGL( 7603): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7603): Local Patches: NONE
I/Adreno-EGL( 7603): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7603): Requires BLUETOOTH permission
,I/NSApplication( 7603): Starting up...
,I/jxcore-log( 6637): Test app app.js loaded
I/jxcore-log( 6637): 
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7667 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7467:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/chromium( 6637): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6637): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc6e9dc added. We now have 1 listener(s)
,I/jxcore-log( 6637): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6637): 
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_7467/cgroup.procs: No such file or directory
,I/art     (  879): Explicit concurrent mark sweep GC freed 17785(883KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.367ms total 113.472ms
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7695 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7513:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7513/cgroup.procs: No such file or directory
,W/ResourcesManager( 7695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7718 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.689ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 21.069ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.162ms
,I/ActivityManager(  879): Killing 7441:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7718): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 7540:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7441/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7540/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2586): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2586): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2586): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2586): onServiceConnected()
D/GetNotificationsWS( 2586): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 2586): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2586): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2586): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2586): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2586): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2586): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  879): done {d5a3a18, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [11347ms]
,D/OtaApp  ( 2586): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2586): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2586): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7755 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2586): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2586): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2586): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2586): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2586): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2586): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2586): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6637): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1415): onFinishInput()
,D/PhoneMonitor( 7755): Register our PhoneStateListener
,I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,196
,V/SetupWizard( 7755): Connected to Gservices successfully
,I/ActivityManager(  879): Killing 7571:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7571/cgroup.procs: No such file or directory
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7780 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7804 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7603:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7603/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7826 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7843 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7667:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  879): Killing 7695:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7667/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7695/cgroup.procs: No such file or directory
,W/ResourcesManager( 7843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Killing 7718:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7718/cgroup.procs: No such file or directory
,I/Babel_SMS( 7843): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7843): MmsConfig.loadMmsSettings
I/Babel_SMS( 7843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7843): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7843): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7843): MmsConfig.loadFromResources
,E/Babel_SMS( 7843): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7843): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7843): startup - clean
,I/Babel   ( 7843): deleted: false for 0
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7877 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7843): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7843): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7843): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7843): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7900 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7755:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 7877): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7755/cgroup.procs: No such file or directory
,W/asset   ( 7900): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7900): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7900): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7900): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/vclib   ( 7843): onServiceConnected
W/Babel   ( 7843): Attempted to change video mute state without an active call.
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1961): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7804): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32e5ba6b new=com.google.android.velvet.VelvetApplication@32e5ba6b
,W/ResourcesManager( 7843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7930 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 7843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7804): UpdateCorporaTask done [took 167 ms] updated apps [took 166 ms] 
,W/System  ( 7843): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7843): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7958 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7780:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7780/cgroup.procs: No such file or directory
,D/Finsky  ( 7958): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7958): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7958): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7958): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  879): Explicit concurrent mark sweep GC freed 13894(697KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.564ms total 115.318ms
,D/Finsky  ( 7958): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7958): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7958): Skipping gmscore version check
,D/Finsky  ( 7958): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7958): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8006 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7826:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_7826/cgroup.procs: No such file or directory
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 1961): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8027 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.728ms
,I/ActivityManager(  879): Killing 7900:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 24.002ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.470ms
,I/Icing   ( 1961): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_7900/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7804:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/PhoneMonitor( 8027): Register our PhoneStateListener
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_7804/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7877:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7877/cgroup.procs: No such file or directory
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593234417 min interval config: 0 actual interval: 12516
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 1961): Checking schedule, now: 1454593246951 next: 1454593264384
I/CheckinService( 1961): active receiver: disabled
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  879): Killing 7930:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7930/cgroup.procs: No such file or directory
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311363, SEQNUM=4470, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-1268, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1415): run()
I/Keyboard.Facilitator( 1415): flushDynamicLanguageModels()
,I/ConfigService( 1704): onCreate
,I/ConfigService( 1704): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310973, SEQNUM=4474, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-1302, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311139, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-45, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {e8c0689, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {1142bef6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  879): send {1004160b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  879): send {2d9b80b1, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  879): done {1142bef6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [28ms]
,V/AlarmManager(  879): done {1004160b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [44ms]
,I/ActivityManager(  879): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8067 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  879): done {e8c0689, *alarm*:android.intent.action.TIME_TICK} [124ms]
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1454593234417 min interval config: 0 actual interval: 517969
,I/CheckinService( 1961): Checking schedule, now: 1454593752403 next: 1454593264384
I/CheckinService( 1961): active receiver: enabled
,I/CheckinService( 1961): Preparing to send checkin request
I/EventLogService( 1961): Accumulating logs since 1454593230190
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,I/GAv4    ( 8067): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8067):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8067):   adb logcat -s GAv4
,W/GAv4    ( 8067): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 8067): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8067): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8103 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/AlarmManager(  879): done {2d9b80b1, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [373ms]
,W/ResourcesManager( 8103): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8103): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8103): VM with version 2.1.0 has multidex support
I/MultiDex( 8103): install
I/MultiDex( 8103): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8103): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8103): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8103): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a66a772: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8103): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,D/LocationInitializer( 1961): Restart initialization of location
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1704): [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1704): No location to return for getLastLocation()
,W/FusedLocationProvider( 1704): location=null
,I/art     ( 8103): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8103): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8103): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f74000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f74000
,I/GoogleURLConnFactory( 8103): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,I/art     ( 8103): Background sticky concurrent mark sweep GC freed 20855(1233KB) AllocSpace objects, 2(32KB) LOS objects, 11% free, 9MB/11MB, paused 5.714ms total 57.700ms
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbe9ad4e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb88a2be8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8824558, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8970d68, idLength=0xb1382730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=855146565
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89168f0
D/DrmWidevineDash(  296): message_length=1591, signature=0xb888bc38, signature_length=2973247252
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8148): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8148): dex2oat took 101.616ms (threads: 4)
,I/Adreno-EGL( 8103): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8103): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8103): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8103): Local Branch: 
I/Adreno-EGL( 8103): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8103): Local Patches: NONE
I/Adreno-EGL( 8103): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8103): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8103): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8103): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8103): Local Branch: 
I/Adreno-EGL( 8103): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8103): Local Patches: NONE
I/Adreno-EGL( 8103): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f72000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f72000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb1382960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb88a5708, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88419e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb8970d88, idLength=0xb1382730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=4251622671
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8825080
D/DrmWidevineDash(  296): message_length=1626, signature=0xb88a2948, signature_length=2973247252
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
,I/Adreno-EGL( 8103): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8103): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8103): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8103): Local Branch: 
I/Adreno-EGL( 8103): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8103): Local Patches: NONE
I/Adreno-EGL( 8103): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8103): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8103): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8103): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8103): Local Branch: 
I/Adreno-EGL( 8103): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8103): Local Patches: NONE
I/Adreno-EGL( 8103): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/CheckinTask( 1961): Sending checkin request (9445 bytes)
,I/CheckinRequestBuilder( 1961): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1961): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1961): Classify the device as Phone.
,I/CheckinTask( 1961): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1961): Checking schedule, now: 1454593756605 next: 1455194893597
I/CheckinService( 1961): active receiver: disabled
,D/CheckinService( 1961): Recording last checkin time for package unspecified as 1454593756616
,V/SetupWizard( 8027): Connected to Gservices successfully
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Killing 8006:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  879): Killing 7958:com.android.vending/u0a32 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_8006/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_7958/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8176 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@26b2f49a
,I/GCoreNlp( 1704): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/art     (  879): Explicit concurrent mark sweep GC freed 20383(1086KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.343ms total 120.649ms
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8214 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8233 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8067:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10055/pid_8067/cgroup.procs: No such file or directory
,W/ResourcesManager( 7843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8262 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8027:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8233): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_8027/cgroup.procs: No such file or directory
,W/asset   ( 8262): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8262): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8262): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1961): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32e5ba6b new=com.google.android.velvet.VelvetApplication@32e5ba6b
,I/UpdateIcingCorporaServi( 8176): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8287 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8176): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8322 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8103:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_8103/cgroup.procs: No such file or directory
,D/Finsky  ( 8322): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8322): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8322): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8322): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8322): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8322): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8322): Skipping gmscore version check
,D/Finsky  ( 8322): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8322): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 8214:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_8214/cgroup.procs: No such file or directory
,I/Icing   ( 1961): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1961): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 8262:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_8262/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7843:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7843/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {e8c0689, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {364371da, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {364371da, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  879): done {e8c0689, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {7db92e4, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  879): done {7db92e4, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [80ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310455, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-644, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {e8c0689, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {3f97334d, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  879): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8386 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): done {e8c0689, *alarm*:android.intent.action.TIME_TICK} [95ms]
,I/GAv4    ( 8386): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8386):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8386):   adb logcat -s GAv4
,W/GAv4    ( 8386): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8386): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8386): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  879): done {3f97334d, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [240ms]
I/ActivityManager(  879): Killing 8176:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_8176/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8431): 
D/AndroidRuntime( 8431): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8431): CheckJNI is OFF
D/AndroidRuntime( 8431): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10506 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 6637:com.test.thalitest/u0a506 (adj 9): stop com.test.thalitest
W/PackageSettings(  879): Skipping PackageSetting{27f45a6 com.example.hello/10440} due to missing metadata
I/WindowState(  879): WIN DEATH: Window{1fe6d195 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
I/ActivityManager(  879):   Force finishing activity ActivityRecord{32012e16 u0 com.test.thalitest/.MainActivity t6}
W/ActivityManager(  879): Spurious death for ProcessRecord{1f907e02 6637:com.test.thalitest/u0a506}, curProc for 6637: null
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10506 user=0: pkg removed
I/ActivityManager(  879):   Force finishing activity ActivityRecord{32012e16 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  879): Duplicate finish request for ActivityRecord{32012e16 u0 com.test.thalitest/.MainActivity t6 f}
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1704): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1415): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1415): run()
I/art     ( 3274): Explicit concurrent mark sweep GC freed 10774(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 7MB/12MB, paused 835us total 89.779ms
I/Decoder ( 1415): createOrResetDecoder
I/ConfigService( 1704): onCreate
D/VoicemailCleanupService( 8233): Cleaning up data for package: com.test.thalitest
I/art     ( 1569): Explicit concurrent mark sweep GC freed 5032(309KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 506us total 119.384ms
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8462 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  879): Explicit concurrent mark sweep GC freed 17359(1175KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/30MB, paused 1.989ms total 168.465ms
I/art     (  879): WaitForGcToComplete blocked for 52.559ms for cause Explicit
I/art     ( 1961): Explicit concurrent mark sweep GC freed 17189(1018KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 1.155ms total 182.261ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1415): run()
W/asset   ( 8462): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8462): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8462): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
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
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8489 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  879): removeObsoleteFile: deleting file=6_task.xml
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 22.225ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.611ms
I/ActivityManager(  879): Killing 8287:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1569): Deferring update until onResume
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 22.078ms
I/art     (  879): Explicit concurrent mark sweep GC freed 6184(335KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.282ms total 200.059ms
D/AndroidRuntime( 8431): Shutting down VM
W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_8287/cgroup.procs: No such file or directory
W/ContextImpl( 8489): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1961): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1961): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1961): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1704): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1704): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1961): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1961): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1961): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1961): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1961): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1961): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8511 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1961): doRemovePackageData com.test.thalitest
W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32e5ba6b new=com.google.android.velvet.VelvetApplication@32e5ba6b
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8538 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8566 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a

```
