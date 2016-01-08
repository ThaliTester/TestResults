#### Test 549702610b97681_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  894): send {3668535d, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  894): done {3668535d, *walarm*:com.google.android.intent.action.SEND_IDLE} [15ms]
--------- beginning of main
I/PhenotypeConfigurator( 1781): Scheduling Phenotype for one-off execution 1310 seconds from now (1452294391745)
D/GetConfigurationSnapshotOperation( 1781): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
D/AndroidRuntime( 6647): 
D/AndroidRuntime( 6647): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6647): CheckJNI is OFF
I/PhenotypeFlagCommitter( 1781): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1781): Using platform SSLCertificateSocketFactory
D/AndroidRuntime( 6647): Calling main entry com.android.commands.am.Am
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6677 uid=10431 gids={50431, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6647): Shutting down VM
V/ActivityManager(  894): Display changed displayId=0
W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/WebViewFactory( 6677): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6677): Time to load native libraries: 14 ms (timestamps 6628-6642)
I/LibraryLoader( 6677): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6677): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 6677): Expected native library version number "",actual native library version number ""
,I/chromium( 6677): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6677): Initializing chromium process, singleProcess=true
,W/art     ( 6677): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6677): ApplicationContext is null in ApplicationStatus
,W/chromium( 6677): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6677): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6677): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6677): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6677): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6677): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6677): Local Branch: 
I/Adreno-EGL( 6677): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6677): Local Patches: NONE
I/Adreno-EGL( 6677): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  894): Activity pause timeout for ActivityRecord{2cd8ccff u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f279c9:true
,W/art     ( 6677): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6677): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6677): CordovaWebView is running on device made by: motorola
,W/art     ( 6677): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6677): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6677): Render dirty regions requested: true
,D/Atlas   ( 6677): Validating map...
,W/chromium( 6677): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  894): Explicit concurrent mark sweep GC freed 38155(1836KB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 20MB/30MB, paused 1.527ms total 136.938ms
,I/OpenGLRenderer( 6677): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6677): Enabling debug mode 0
,I/Keyboard.Facilitator( 1429): onFinishInput()
,I/LaunchCheckinHandler(  894): Displayed com.test.thalitest/.MainActivity,cp,ca,1126
I/ActivityManager(  894): Displayed com.test.thalitest/.MainActivity: +1s53ms (total +1s126ms)
,W/IInputConnectionWrapper( 6677): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6677): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6677): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6677): Cannot call determinedVisibility() - never saw a connection for the pid: 6677
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/JsMessageQueue( 6677): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6677): JniHelper::setJavaVM(0xb7017310), pthread_self() = -1220907488
,D/JX-Cordova( 6677): jxcore cordova android initializing
,W/jxcore-log( 6677): Initializing JXcore engine
W/jxcore-log( 6677): JXcore engine is ready
,W/jxcore-log( 6677): Starting JXcore engine
,W/.test.thalitest( 6677): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10431 path="socket:[5587]" dev="sockfs" ino=5587 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6677): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10431 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6677): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10431 path="socket:[7520]" dev="sockfs" ino=7520 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6677): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10431 path="socket:[27591]" dev="sockfs" ino=27591 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6677): Platform android
W/jxcore-log( 6677): 
W/jxcore-log( 6677): Process ARCH arm
W/jxcore-log( 6677): 
,I/jxcore-log( 6677): JXcore Cordova bridge is ready!
I/jxcore-log( 6677): 
,W/jxcore-log( 6677): JXcore engine is started
,I/chromium( 6677): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6677): Toggling radios to true
I/jxcore-log( 6677): 
,D/BluetoothAdapter( 6677): enable(): BT is already enabled..!
,D/WifiService(  894): New client listening to asynchronous messages
,D/WifiService(  894): setWifiEnabled: true pid=6677, uid=10431
E/WifiService(  894): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6677): Radios toggled
I/jxcore-log( 6677): 
I/jxcore-log( 6677): My device name is: motorola-XT1072
I/jxcore-log( 6677): 
,D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
I/MDMCTBK (  295): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  295): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  295): set_property_value, Exit
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
,D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  894): InitialState.processMessage what=4
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  295): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  894): ApnList is empty for checkDunConfigured()
D/Tethering(  894):  upstream interface types: 
D/Tethering(  894):  1
D/Tethering(  894):  5
D/Tethering(  894):  7
D/Tethering(  894):  0
,E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  894): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering(  894): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 21
D/TCMD    (  481): Listening for incoming client connection request
,V/NativeCrypto( 1781): Read error: ssl=0xb726eb50: I/O error during system call, Connection timed out
V/NativeCrypto( 1781): SSL shutdown failed: ssl=0xb726eb50: I/O error during system call, Broken pipe
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info<unknown ssid>
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6758 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/global frequency( 2952): no tags to log
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin ( 2952): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/WifiMetrics(  894): connected time updated 160602
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  894): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): ConnectModeState: Network connection lost 
E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/ResourcesManager( 6758): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1546): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1546): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1546): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1546): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1546): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1546): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  894): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 56456(3MB) AllocSpace objects, 37(1278KB) LOS objects, 39% free, 7MB/12MB, paused 836us total 51.328ms
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2952): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/Babel_SMS( 6758): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6758): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6758): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6758): MmsConfig.loadFromDatabase
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2952): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/Babel_SMS( 6758): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6758): MmsConfig.loadFromResources
,E/Babel_SMS( 6758): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6758): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/wpa_supplicant( 1448): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  295): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  481): NL - Read 56 bytes from update socket.
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  295): Event received = Trying to associate with
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/WifiMonitor(  894): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1448): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  894): [1,452,294,397,283 ms] noteScanEnd no scan source
,E/WifiStateMachine(  894): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  894): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  894): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/PhoneInterfaceManager( 1565): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 4383(182KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 587us total 26.695ms
,W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6758): startup - clean
,I/Babel   ( 6758): deleted: false for 0
,D/BSUtils ( 2952): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/TCMD    (  481): NL - Read 312 bytes from update socket.
,D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 192 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,I/wpa_supplicant( 1448): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  295): Event received = Associated with c0:ff:d4
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1448): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  295): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1448): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  295):  STA Connected !!
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,E/MDMCTBK (  295): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
,D/MDMCTBK (  295): get_freq !!, resp=2412
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
D/Tethering(  894): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  894): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
I/MDMCTBK (  295): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1219349320
I/MDMCTBK (  295): return from set_get_from_wpa_supplicant
I/MDMCTBK (  295): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  295): set_property_value, Enter
I/MDMCTBK (  295): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  295): set_property_value, Values updated in the property file Successfully
E/Tethering(  894): ApnList is empty for checkDunConfigured()
I/MDMCTBK (  295): set_property_value, Exit
D/Tethering(  894):  upstream interface types: 
E/MDMCTBK (  295): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering(  894):  0
D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/Tethering(  894):  1
D/MDMCTBK (  295): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  894):  5
D/Tethering(  894):  7
,D/MDMCTBK (  295): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  295): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  295): , reply_len: 3, ret: 0
E/MDMCTBK (  295): MdmCutbackHndler, resp=OK
E/MDMCTBK (  295): 
D/MDMCTBK (  295): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
D/Tethering(  894): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): Network connection established
,E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  894): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  894): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  894): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  894): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  894): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  292): Setting iface cfg
,E/WifiStateMachine(  894): Start Dhcp Watchdog 2
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend false
,E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  894): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1448): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d8f5036 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d8f5036 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6758): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6758): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6758): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
I/art     (  894): Explicit concurrent mark sweep GC freed 35948(1844KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.124ms total 163.779ms
,I/BSUtils ( 2952): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  894): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6804 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6394:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/vclib   ( 6758): onServiceConnected
W/Babel   ( 6758): Attempted to change video mute state without an active call.
,E/DHCPCD  ( 6821): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6821): version 5.5.6 starting
,E/DHCPCD  ( 6821): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6821): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6821): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6821): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6821): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6821): wlan0: sending REQUEST (xid 0x86f7375a), next in 4.20 seconds
,W/libprocessgroup(  894): failed to open /acct/uid_10057/pid_6394/cgroup.procs: No such file or directory
,I/BSUtils ( 2952): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2952): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2952): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2952): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2952): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2952): publish the event [tag = DEV_ATTRIBS event name = SW]
,W/ResourcesManager( 6804): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin ( 2952): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/ActivityManager(  894): Killing 6444:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/global frequency( 2952): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2952): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_6444/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6821): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6821): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6821): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6821): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6821): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6821): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 20
D/TCMD    (  481): Listening for incoming client connection request
,D/DHCPCD  ( 6821): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  894): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  894): WifiStateMachine DHCP successful
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  894): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  894): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  894): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  894): Setting Dns servers for network 101 to [/192.168.1.1]
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 101]
D/Checkin (  894): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  894):    accepting network in place of null
,D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1546): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1546): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1546): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  894): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:06:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294399533], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294399512]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1546): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1546): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1546): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1546): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1485): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2952): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6887 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1485): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1485): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2952): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2952): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2952): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2952): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2952): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2952): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2952): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2952): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2952): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2952): [debug] > CusSM.onRadioDown
,I/MusicStore( 6887): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6887): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6887): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6887): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6887): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6887): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6887): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ConnectivityService(  894): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ActivityThread( 6887): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6887): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6887): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6887): GMSCore installation verified
,I/ConfigStore( 6887): Config Database version: 1
,I/MediaRouter( 6887): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6887): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6887): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6887): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6921 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6887): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6887): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 6238:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_6238/cgroup.procs: No such file or directory
,V/Mms     ( 6921): mnc/mcc: 
V/Mms     ( 6921): tag: int value: recipientLimit - 20
V/Mms     ( 6921): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6921): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6921): tag: int value: maxSubjectLength - 80
V/Mms     ( 6921): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6921): tag: bool value: enableGroupMms - false
,V/Mms     ( 6921):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6921): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6956 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6315:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6956): Register our PhoneStateListener
,W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_6315/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6956): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6956): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  894): Killing 6758:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_6758/cgroup.procs: No such file or directory
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294310388 min interval config: 0 actual interval: 91282
,I/CheckinService( 6508): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6508): SYNC; picasa accounts
,D/NetworkLogImpl( 6508): Loaded NetworkSpeedPredictor
I/iu.Environment( 6508): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 6508): Checking schedule, now: 1452294401727 next: 1452294340349
I/CheckinService( 6508): active receiver: enabled
,I/iu.UploadsManager( 6508): num queued entries: 0
,I/iu.UploadsManager( 6508): num updated entries: 0
,I/iu.SyncManager( 6508): NEXT; no task
,I/CheckinService( 6508): Preparing to send checkin request
,I/EventLogService( 6508): Accumulating logs since 1452294307112
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6985 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6508): Checkin reason type: 8 attempt count: 1
,D/WifiService(  894): New client listening to asynchronous messages
,E/ActivityThread( 6508): Failed to find provider info for com.google.android.wearable.settings
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  894): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7007 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7024 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Tethering(  894): MasterInitialState.processMessage what=3
D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1485): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2952): now: 206730 ,futureTime: 9223372036854775807
D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2952): now: 206730 ,futureTime: 9223372036854775807
W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2952): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2952): now: 206730 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2952): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2952): [debug] > PollingManagerService, now: 206736 ,futureTime: 61765135
D/OtaApp  ( 2952): [debug] > Polling alarm set to expire at: 61765135 Current Time: 206736
,D/Central_PollingManager( 1485): now: 206737 ,futureTime: 86480983
D/Central_PollingManager( 1485): Polling alarm set to expire at: 86480983 Current Time: 206738
,I/NetworkMonitor( 6887): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7024): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 2952): Explicit concurrent mark sweep GC freed 23490(1368KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 951us total 70.054ms
,D/MMApiProvisionService( 2952): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MultiDex( 7007): VM with version 2.1.0 has multidex support
,I/MultiDex( 7007): install
I/MultiDex( 7007): VM has multidex support, MultiDex support library is disabled.
,I/art     (  894): Explicit concurrent mark sweep GC freed 22758(1131KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.088ms total 116.232ms
,D/CCE     ( 2952): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2952): createDeviceIdOrLogin update_device
D/Checkin ( 2952): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2952): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2952): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2952): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2952): createDeviceIdOrLogin update_device
,V/JNIHelp ( 7007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Checkin ( 2952): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2952): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2952): set mOutstandingReq to true.
I/ Nonce  ( 2952):  Nonce getNonce 
I/ Nonce  ( 2952):  Nonce Request 
I/ Nonce  ( 2952):  Nonce execute Request 
,D/MMApiWebService( 2952): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2952): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2952): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2952): createDeviceIdOrLogin update_device
,D/Checkin ( 2952): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2952): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2952): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2952): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2952): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2952): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2952): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2952): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2952): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2952): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2952): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2952): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ActivityThread( 7007): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7007): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7007): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7007): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel_SMS( 7024): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7024): MmsConfig.loadMmsSettings
I/Babel_SMS( 7024): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7024): MmsConfig.loadFromDatabase
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 3812(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 606us total 39.018ms
,E/Babel_SMS( 7024): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7024): MmsConfig.loadFromResources
D/MMApiWebService( 2952): generating token using payload instead of using session token
E/Babel_SMS( 7024): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7024): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ Nonce  ( 2952):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/NativeLibraryUtils( 7007): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/MMApiWSBase( 2952): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
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
,D/Checkin ( 2952): publish the event [tag = MOT_CCE event name = LOG]
,W/Settings( 7024): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7024): startup - clean
,I/Babel   ( 7024): deleted: false for 0
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb548e960
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb8047338, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb803bc68, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8047ef8, idLength=0xb13a4730
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
D/WVCdm   (  297): PrepareKeyRequest: nonce=2986084984
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f7bed8
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7f32430, signature_length=2973386516
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7062 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.509ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 397us total 19.726ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 31.323ms
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
,D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  297): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 7024): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7024): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7024): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7024): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7024): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7024): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7024): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7024): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7024): onServiceConnected
,W/Babel   ( 7024): Attempted to change video mute state without an active call.
,V/AlarmManager(  894): send {29ff44ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/Babel   ( 7024): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  894): Killing 6804:com.motorola.context/u0a8 (adj 15): empty #7
,I/dex2oat ( 7084): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  894): failed to open /acct/uid_10008/pid_6804/cgroup.procs: No such file or directory
,I/dex2oat ( 7084): dex2oat took 89.120ms (threads: 4)
,I/Adreno-EGL( 7007): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7007): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7007): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7007): Local Branch: 
I/Adreno-EGL( 7007): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7007): Local Patches: NONE
I/Adreno-EGL( 7007): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7062): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7062):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7062):   adb logcat -s GAv4
,W/GAv4    ( 7062): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 7007): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7007): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7007): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7007): Local Branch: 
I/Adreno-EGL( 7007): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7007): Local Patches: NONE
I/Adreno-EGL( 7007): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 7062): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7062): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb13a4960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb80476d0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f4f280, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8047f38, idLength=0xb548e730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=3490105548
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f4dad0
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7f322d8, signature_length=3041453844
,I/WebViewFactory( 7062): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7062): Time to load native libraries: 1 ms (timestamps 8545-8546)
I/LibraryLoader( 7062): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7062): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7062): Expected native library version number "",actual native library version number ""
I/chromium( 7062): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7062): Initializing chromium process, singleProcess=true
W/art     ( 7062): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7062): ApplicationContext is null in ApplicationStatus
,I/ Nonce  ( 2952):  Nonce Reponse 
D/        ( 2952): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"71f1c074-3681-46df-acaa-491f67e7284a"}
D/MMApiWSBase( 2952): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2952):  Nonce Handle Reponse 
D/MMApiProvisionService( 2952): mOutstandingReq set to false
,W/chromium( 7062): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7062): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7062): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7062): Local Branch: 
I/Adreno-EGL( 7062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7062): Local Patches: NONE
I/Adreno-EGL( 7062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,D/MMApiProvisionService( 2952):  pTime 1452280438857 sExp 172742 cTime 1452294404387 tTime 1452453180857
D/MMApiProvisionService( 2952):  No login Required 
,W/AudioManagerAndroid( 7062): Requires BLUETOOTH permission
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
I/NSApplication( 7062): Starting up...
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7007): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7007): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7007): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7007): Local Branch: 
I/Adreno-EGL( 7007): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7007): Local Patches: NONE
I/Adreno-EGL( 7007): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7132 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6887:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 7007): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7007): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7007): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7007): Local Branch: 
I/Adreno-EGL( 7007): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7007): Local Patches: NONE
I/Adreno-EGL( 7007): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_6887/cgroup.procs: No such file or directory
,W/DataUsage( 2952): invalid counter update blocked: 'err' by 0
D/Checkin ( 2952): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinRequestBuilder( 6508): Classify the device as Phone.
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7157 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6921:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_6921/cgroup.procs: No such file or directory
,W/ResourcesManager( 7157): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 6508): Sending checkin request (11468 bytes)
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7186 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7207 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 6985:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7186): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 6956:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/CheckinRequestBuilder( 6508): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_6985/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_6956/cgroup.procs: No such file or directory
,E/ActivityThread( 6508): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 7207): Database version: 120
,I/art     (  894): Explicit concurrent mark sweep GC freed 9147(443KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.533ms total 110.680ms
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7207): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 6472): Explicit concurrent mark sweep GC freed 1780(78KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 383us total 34.888ms
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7207): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7207): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6508): Classify the device as Phone.
,I/CheckinTask( 6508): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/ResourcesManager( 7207): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7207): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CheckinService( 6508): Checking schedule, now: 1452294406447 next: 1452895543429
I/CheckinService( 6508): active receiver: disabled
,D/CheckinService( 6508): Recording last checkin time for package unspecified as 1452294406461
,I/ActivityManager(  894): Killing 7024:com.google.android.talk/u0a70 (adj 15): empty #7
,V/JNIHelp ( 7207): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7207): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7207): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7207): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7207): GMSCore installation verified
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7024/cgroup.procs: No such file or directory
,I/ConfigStore( 7207): Config Database version: 1
,I/MediaRouter( 7207): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7207): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7207): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Killing 7062:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,E/libprocessgroup(  894): failed to kill 1 processes for processgroup 7062
,I/NetworkMonitor( 7207): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7267 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7207): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7207): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 7132:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7267): mnc/mcc: 
V/Mms     ( 7267): tag: int value: recipientLimit - 20
V/Mms     ( 7267): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7267): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7267): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7267): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7267): tag: bool value: enableGroupMms - false
V/Mms     ( 7267):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7132/cgroup.procs: No such file or directory
,W/ResourcesManager( 7267): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7302 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7157:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7157/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7302): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7302): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7302): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  894): Killing 7186:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7186/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7327 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294406461 min interval config: 0 actual interval: 1775
,I/CheckinService( 6508): Checking schedule, now: 1452294408254 next: 1452294436429
I/CheckinService( 6508): active receiver: disabled
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7354 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  894): Killing 7207:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_7207/cgroup.procs: No such file or directory
,W/ResourcesManager( 7354): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7354): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7354): MmsConfig.loadMmsSettings
I/Babel_SMS( 7354): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7354): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7354): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7354): MmsConfig.loadFromResources
,E/Babel_SMS( 7354): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7354): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7354): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7354): startup - clean
,I/Babel   ( 7354): deleted: false for 0
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7398 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6677): Test app app.js loaded
I/jxcore-log( 6677): 
,I/chromium( 6677): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/VideoCapabilities( 7354): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7354): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7354): Unsupported mime video/mpeg2
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,I/VideoCapabilities( 7354): Unsupported profile 4 for video/mp4v-es
W/ContextImpl( 7398): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7354): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7354): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7398): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7398):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7398):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 7354): Unrecognized profile 2130706433 for video/avc
,W/ContextImpl( 7398): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 7354): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 7398): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7354): onServiceConnected
,W/Babel   ( 7354): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7398): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7398): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7398): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7398): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7354): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  894): Killing 7267:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_7267/cgroup.procs: No such file or directory
,I/WebViewFactory( 7398): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7398): Time to load native libraries: 1 ms (timestamps 3972-3973)
I/LibraryLoader( 7398): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7398): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7398): Expected native library version number "",actual native library version number ""
I/chromium( 7398): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7398): Initializing chromium process, singleProcess=true
,W/art     ( 7398): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7398): ApplicationContext is null in ApplicationStatus
,W/chromium( 7398): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7398): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7398): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7398): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7398): Local Branch: 
I/Adreno-EGL( 7398): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7398): Local Patches: NONE
I/Adreno-EGL( 7398): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7398): Requires BLUETOOTH permission
,I/NSApplication( 7398): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7464 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7302:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7302/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7483 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7327:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 24.563ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.284ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.774ms
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7327/cgroup.procs: No such file or directory
,W/ResourcesManager( 7483): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7503 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7398:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 7503): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Killing 7354:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_7398/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7354/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2952): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2952): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2952): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2952): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2952): onServiceConnected()
D/GetNotificationsWS( 2952): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2952): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2952): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7536 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  894): Explicit concurrent mark sweep GC freed 12396(628KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.468ms total 109.812ms
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7559 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7007:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/MusicStore( 7559): Database version: 120
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_7007/cgroup.procs: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7559): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7559): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7559): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7559): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7559): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7559): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7559): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7559): GMSCore installation verified
,I/ConfigStore( 7559): Config Database version: 1
,I/MediaRouter( 7559): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7559): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7559): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7559): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  894): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7594 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7559): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7559): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  894): Killing 7464:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7594): mnc/mcc: 
,V/Mms     ( 7594): tag: int value: recipientLimit - 20
V/Mms     ( 7594): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7594): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7594): tag: int value: maxSubjectLength - 80
V/Mms     ( 7594): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7594): tag: bool value: enableGroupMms - false
V/Mms     ( 7594):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7464/cgroup.procs: No such file or directory
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7594): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7629 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  894): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  894): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@719acb1
,I/GCoreNlp( 1781): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PhoneMonitor( 7629): Register our PhoneStateListener
I/ActivityManager(  894): Killing 7483:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1582): Deferring update until onResume
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7483/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7629): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7629): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294406461 min interval config: 0 actual interval: 5672
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294406461 min interval config: 0 actual interval: 5674
,I/CheckinService( 6508): Checking schedule, now: 1452294412140 next: 1452294436429
I/CheckinService( 6508): active receiver: disabled
,I/CheckinService( 6508): Checking schedule, now: 1452294412152 next: 1452294436429
I/CheckinService( 6508): active receiver: disabled
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7651 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  894): Killing 7503:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7503/cgroup.procs: No such file or directory
,W/ResourcesManager( 7651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7651): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7651): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7651): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7651): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7651): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7651): MmsConfig.loadFromResources
E/Babel_SMS( 7651): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7651): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7651): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7651): startup - clean
,I/Babel   ( 7651): deleted: false for 0
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7684 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7651): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7651): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7651): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7651): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7651): onServiceConnected
W/Babel   ( 7651): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7684): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7684):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7684):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7684): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7684): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7651): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  894): Killing 7559:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7684): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7684): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  894): failed to open /acct/uid_10080/pid_7559/cgroup.procs: No such file or directory
,I/WebViewFactory( 7684): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7684): Time to load native libraries: 1 ms (timestamps 7569-7570)
,I/LibraryLoader( 7684): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7684): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7684): Expected native library version number "",actual native library version number ""
I/chromium( 7684): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7684): Initializing chromium process, singleProcess=true
,W/art     ( 7684): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7684): ApplicationContext is null in ApplicationStatus
,W/chromium( 7684): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7684): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7684): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7684): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7684): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7684): Local Branch: 
I/Adreno-EGL( 7684): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7684): Local Patches: NONE
I/Adreno-EGL( 7684): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7684): Requires BLUETOOTH permission
,I/NSApplication( 7684): Starting up...
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7760 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7594:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10023/pid_7594/cgroup.procs: No such file or directory
,I/art     (  894): Explicit concurrent mark sweep GC freed 17532(881KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.120ms total 115.404ms
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7779 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7629:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7629/cgroup.procs: No such file or directory
,W/ResourcesManager( 7779): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7799 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7651:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  894): Killing 7536:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7799): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2952): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7651/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7536/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2952): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2952): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2952): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2952): onServiceConnected()
,D/GetNotificationsWS( 2952): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2952): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2952): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2952): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2952): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2952): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  894): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WearableService( 1781): callingUid 10016, callindPid: 1781
,E/MDM     ( 1781): [173] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/OtaApp  ( 2952): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2952): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2952): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1781): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6508): Restart initialization of location
,D/OtaApp  ( 2952): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2952): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2952): publish the event [tag = MOT_OTA event name = LOG]
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2952): [debug] > DownloadActivity, FormattedText
,V/AlarmManager(  894): done {29ff44ba, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10790ms]
,I/OtaApp  ( 2952): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2952): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2952): [debug] > cancelling the previous pending intent set for download later
,W/GCoreFlp( 1781): No location to return for getLastLocation()
,W/FusedLocationProvider( 1781): location=null
I/OtaApp  ( 2952): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2952): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6677): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1429): onFinishInput()
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7841 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 27.364ms
,I/LaunchCheckinHandler(  894): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,189
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 23.759ms
,D/PhoneMonitor( 7841): Register our PhoneStateListener
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.505ms
,V/SetupWizard( 7841): Connected to Gservices successfully
,D/GCM     ( 1781): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1781): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7862 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7888 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7684:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10081/pid_7684/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7911 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7928 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7760:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  894): Killing 7779:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10052/pid_7760/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7779/cgroup.procs: No such file or directory
,W/ResourcesManager( 7928): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7928): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7928): MmsConfig.loadMmsSettings
I/Babel_SMS( 7928): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7928): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7928): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7928): MmsConfig.loadFromResources
E/Babel_SMS( 7928): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7928): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7928): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7928): startup - clean
,I/Babel   ( 7928): deleted: false for 0
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7961 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7928): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7928): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7928): Unsupported mime video/mpeg2
,W/asset   ( 7961): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7961): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7961): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7961): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7928): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7928): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7928): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7928): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7928): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6508): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 7888): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6508): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7992 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7928): onServiceConnected
,W/Babel   ( 7928): Attempted to change video mute state without an active call.
I/Icing   ( 6508): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7928): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7928): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7888): UpdateCorporaTask done [took 177 ms] updated apps [took 177 ms] 
,I/ActivityManager(  894): Killing 7841:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,V/JNIHelp ( 7928): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7928): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7928): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_7841/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8027 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7862:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_7862/cgroup.procs: No such file or directory
,D/Finsky  ( 8027): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8027): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8027): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8027): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     (  894): Explicit concurrent mark sweep GC freed 13814(670KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.512ms total 117.945ms
,D/Finsky  ( 8027): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8027): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8027): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 8027): Skipping gmscore version check
,D/Finsky  ( 8027): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  894): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8075 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7911:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_7911/cgroup.procs: No such file or directory
,I/Icing   ( 6508): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/TaskPersister(  894): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  894): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8095 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 7961:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10027/pid_7961/cgroup.procs: No such file or directory
,D/Icing   ( 6508): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6508): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/PhoneMonitor( 8095): Register our PhoneStateListener
,I/ActivityManager(  894): Killing 7888:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_7888/cgroup.procs: No such file or directory
,D/GCM     ( 1781): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294406461 min interval config: 0 actual interval: 11001
,I/CheckinService( 6508): Checking schedule, now: 1452294417469 next: 1452294436429
I/CheckinService( 6508): active receiver: disabled
,D/GCM     ( 1781): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310569, SEQNUM=4585, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2118, POWER_SUPPLY_CHARGE_COUNTER=-699, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2808): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2808): Disconnected process message: 10, size: 0
,I/ActivityManager(  894): Killing 7799:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10007/pid_7799/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 7992:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10090/pid_7992/cgroup.procs: No such file or directory
,I/CheckinService( 6508): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310302, SEQNUM=4591, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=-689, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2808): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1781): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  894): send {21b0be03, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {30236311, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  894): send {2f906680, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  894): done {30236311, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [14ms]
,V/AlarmManager(  894): done {2f906680, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [37ms]
,I/CheckinService( 6508): Checkin interval check for package: unspecified last checkin: 1452294406461 min interval config: 0 actual interval: 37925
,V/AlarmManager(  894): done {21b0be03, *alarm*:android.intent.action.TIME_TICK} [57ms]
,I/CheckinService( 6508): Checking schedule, now: 1452294444408 next: 1452294436429
I/CheckinService( 6508): active receiver: enabled
,I/CheckinService( 6508): Preparing to send checkin request
I/EventLogService( 6508): Accumulating logs since 1452294402002
,I/CheckinRequestBuilder( 6508): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6508): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  894): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8154 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8154): VM with version 2.1.0 has multidex support
I/MultiDex( 8154): install
,I/MultiDex( 8154): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8154): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8154): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1781): callingUid 10016, callindPid: 1781
,D/LocationInitializer( 6508): Restart initialization of location
,D/AuthorizationBluetoothService( 1781): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1781): [173] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1781): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1781): No location to return for getLastLocation()
,W/FusedLocationProvider( 1781): location=null
,I/art     ( 8154): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8154): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8154): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  297): Instantiating CDM.
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
,E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbebde4e0
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb8037620, dataLength=8
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7f4f280, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8047f18, idLength=0xb13a4730
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
D/WVCdm   (  297): PrepareKeyRequest: nonce=4141992836
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f7bed8
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7f33ba8, signature_length=2973386516
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8181): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8181): dex2oat took 73.210ms (threads: 4)
,I/Adreno-EGL( 8154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8154): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8154): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8154): Local Branch: 
I/Adreno-EGL( 8154): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8154): Local Patches: NONE
I/Adreno-EGL( 8154): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8154): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8154): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8154): Local Branch: 
I/Adreno-EGL( 8154): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8154): Local Patches: NONE
I/Adreno-EGL( 8154): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
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
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb3000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb548e960
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb7f4c1e8, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb803bc68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb8047f38, idLength=0xb13a4730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  297): PrepareKeyRequest: nonce=21364909
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f4dad0
D/DrmWidevineDash(  297): message_length=1625, signature=0xb7f32598, signature_length=2973386516
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8154): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8154): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8154): Local Branch: 
I/Adreno-EGL( 8154): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8154): Local Patches: NONE
I/Adreno-EGL( 8154): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8154): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8154): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8154): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8154): Local Branch: 
I/Adreno-EGL( 8154): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8154): Local Patches: NONE
I/Adreno-EGL( 8154): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6508): Classify the device as Phone.
,I/CheckinTask( 6508): Sending checkin request (11458 bytes)
,I/CheckinRequestBuilder( 6508): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6508): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6508): Classify the device as Phone.
,I/CheckinTask( 6508): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6508): Checking schedule, now: 1452294447510 next: 1452895584504
,I/CheckinService( 6508): active receiver: disabled
,D/CheckinService( 6508): Recording last checkin time for package unspecified as 1452294447521
,V/SetupWizard( 8095): Connected to Gservices successfully
,D/GCM     ( 1781): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  894): Killing 8027:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10032/pid_8027/cgroup.procs: No such file or directory
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8219 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 25.324ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.859ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.685ms
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  894): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  894): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  894): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1a9a8022
,I/GCoreNlp( 1781): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1582): Deferring update until onResume
,I/art     ( 1781): Explicit concurrent mark sweep GC freed 101792(5MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 15MB/25MB, paused 1.091ms total 128.797ms
,E/DataBuffer( 1781): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34d35d95)
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8249 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8075:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  894): Explicit concurrent mark sweep GC freed 19261(1009KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.633ms total 126.811ms
,W/libprocessgroup(  894): failed to open /acct/uid_10088/pid_8075/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8269 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 7928): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7928): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8269): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8292 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 8095:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_8095/cgroup.procs: No such file or directory
,W/asset   ( 8292): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8292): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8292): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8292): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6508): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6508): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6508): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 8219): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  894): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8318 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8318): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8219): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
,I/ActivityManager(  894): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8346 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 8154:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_8154/cgroup.procs: No such file or directory
,D/Finsky  ( 8346): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8346): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8346): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8346): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8346): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8346): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8346): Skipping gmscore version check
,I/ActivityManager(  894): Killing 8249:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10019/pid_8249/cgroup.procs: No such file or directory
,D/Finsky  ( 8346): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8346): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6508): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6508): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  894): Killing 8292:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10027/pid_8292/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 7928:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10070/pid_7928/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1429): run()
I/Keyboard.Facilitator( 1429): flushDynamicLanguageModels()
,I/ConfigService( 1781): onCreate
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309596, SEQNUM=4605, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1613, POWER_SUPPLY_CHARGE_COUNTER=-669, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2808): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2808): Disconnected process message: 10, size: 0
,I/ConfigService( 1781): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6677): --= Surplus to requirements =--
I/jxcore-log( 6677): 
I/jxcore-log( 6677): ****TEST TOOK:  ms ****
I/jxcore-log( 6677): 
I/jxcore-log( 6677): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6677): 
,D/AndroidRuntime( 8403): 
D/AndroidRuntime( 8403): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8403): CheckJNI is OFF
,D/AndroidRuntime( 8403): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  894): Force stopping com.test.thalitest appid=10431 user=-1: uninstall pkg
,I/ActivityManager(  894): Killing 6677:com.test.thalitest/u0a431 (adj 9): stop com.test.thalitest
,W/PackageSettings(  894): Skipping PackageSetting{f36067b com.example.hello/10426} due to missing metadata
,I/WindowState(  894): WIN DEATH: Window{2f906739 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  894): Client connection lost with reason: 4
,I/ActivityManager(  894):   Force finishing activity ActivityRecord{2cd8ccff u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  894): Spurious death for ProcessRecord{2dbb2356 6677:com.test.thalitest/u0a431}, curProc for 6677: null
,I/ActivityManager(  894): Force stopping com.test.thalitest appid=10431 user=0: pkg removed
,I/art     ( 3416): Explicit concurrent mark sweep GC freed 5251(1137KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 7MB/12MB, paused 711us total 36.291ms
,I/Keyboard.Facilitator( 1429): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1781): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1429): run()
,D/VoicemailCleanupService( 8269): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1429): createOrResetDecoder
,I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8430 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1582): Explicit concurrent mark sweep GC freed 6835(454KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 479us total 104.403ms
,I/art     (  894): Explicit concurrent mark sweep GC freed 15078(1016KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.453ms total 157.475ms
,I/art     (  894): WaitForGcToComplete blocked for 158.277ms for cause Explicit
,I/ConfigService( 1781): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1429): run()
,W/asset   ( 8430): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8430): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8430): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8430): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1429): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1429): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1429): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1429): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1429): run()
,I/StatsUtilsManager( 1429): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1429): shouldRecordStats() = Too Soon
,D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  894): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8455 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  894): removeObsoleteFile: deleting file=3_task.xml
,I/ActivityManager(  894): Killing 8219:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  894): Explicit concurrent mark sweep GC freed 4989(278KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.186ms total 213.210ms
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_8219/cgroup.procs: No such file or directory
,W/ContextImpl( 8455): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/Launcher( 1582): Deferring update until onResume
,D/PackageBroadcastService( 6508): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 6508): Reading stored module config
,D/AccountUtils( 6508): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6508): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6508): Loading module APK com.google.android.play.games
,D/AndroidRuntime( 8403): Shutting down VM
,I/LocationSettingsChecker( 6508): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6508): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6508): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1781): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1781): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6508): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6508): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6508): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6508): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6508): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 6508): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6508): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6508): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 6508): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6508): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6508): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6508): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6508): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8487 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,D/ChimeraCfgMgr( 6508): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6508): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,I/Icing   ( 6508): doRemovePackageData com.test.thalitest
,W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  894): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8508 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/BaseAppContext( 6508): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,D/ConnectivityService(  894): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  894): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6508): CM callback handler got msg 524290
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,W/art     ( 6508): Suspending all threads took: 7.499ms
,W/BaseAppContext( 6508): Using Auth Proxy for data requests.
,I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8541 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8487): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/SQLiteLog( 6508): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 6508): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6508): Process: com.google.android.gms, PID: 6508
E/AndroidRuntime( 6508): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6508): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6508): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6508): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6508): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6508): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6508): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6508): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6508): Sending signal. PID: 6508 SIG: 9
E/SQLiteLog( 8487): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ConnectivityService(  894): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@29323203)
D/WifiService(  894): Client connection lost with reason: 4
D/ConnectivityService(  894): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  894): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  894): Process com.google.android.gms (pid 6508) has died
,W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
,W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
W/ActivityManager(  894): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
I/ActivityManager(  894): Killing 8318:com.google.android.apps.plus/u0a90 (adj 15): empty #7

```
