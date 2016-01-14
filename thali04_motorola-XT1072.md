#### Test 55613145b105d0b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,--------- beginning of system
E/BackupManagerService(  881): Timeout restoring application @pm@
W/BackupManagerService(  881): Tried to clear data for @pm@ but not found
W/GmsBackupTransport( 1744): Restore processing aborted, no more packages
E/BackupManagerService(  881): Failure getting next package name
E/BackupManagerService(  881): Duplicate finish
D/AndroidRuntime( 6294): 
D/AndroidRuntime( 6294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6294): CheckJNI is OFF
D/AndroidRuntime( 6294): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6313 uid=10448 gids={50448, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6294): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6313): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6313): Time to load native libraries: 4 ms (timestamps 7453-7457)
I/LibraryLoader( 6313): Expected native library version number "",actual native library version number ""
I/art     (  881): Explicit concurrent mark sweep GC freed 42239(2030KB) AllocSpace objects, 2(213KB) LOS objects, 33% free, 20MB/30MB, paused 1.423ms total 129.097ms
V/WebViewChromiumFactoryProvider( 6313): Binding Chromium to main looper Looper (main, tid 1) {24b8ed3c}
I/LibraryLoader( 6313): Expected native library version number "",actual native library version number ""
I/chromium( 6313): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6313): Initializing chromium process, singleProcess=true
W/art     ( 6313): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6313): ApplicationContext is null in ApplicationStatus
W/chromium( 6313): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6313): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6313): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6313): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6313): Local Branch: 
I/Adreno-EGL( 6313): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6313): Local Patches: NONE
I/Adreno-EGL( 6313): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{343386ca u0 com.test.thalitest/.MainActivity t6}
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c6360e9:true
W/art     ( 6313): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6313): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6313): CordovaWebView is running on device made by: motorola
W/art     ( 6313): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6313): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6313): Render dirty regions requested: true
,D/Atlas   ( 6313): Validating map...
,W/chromium( 6313): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6313): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6313): Enabling debug mode 0
I/Keyboard.Facilitator( 1422): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1098
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s26ms (total +1s98ms)
,W/IInputConnectionWrapper( 6313): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6313): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6313): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6313): Cannot call determinedVisibility() - never saw a connection for the pid: 6313
,D/JsMessageQueue( 6313): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6313): JniHelper::setJavaVM(0xb7d9a310), pthread_self() = -1206738280
D/JX-Cordova( 6313): jxcore cordova android initializing
,W/jxcore-log( 6313): Initializing JXcore engine
W/jxcore-log( 6313): JXcore engine is ready
,W/jxcore-log( 6313): Starting JXcore engine
,W/.test.thalitest( 6313): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10448 path="socket:[6407]" dev="sockfs" ino=6407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6313): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10448 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6313): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10448 path="socket:[7518]" dev="sockfs" ino=7518 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6313): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10448 path="socket:[26435]" dev="sockfs" ino=26435 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6313): Platform android
W/jxcore-log( 6313): 
,W/jxcore-log( 6313): Process ARCH arm
W/jxcore-log( 6313): 
,I/jxcore-log( 6313): JXcore Cordova bridge is ready!
I/jxcore-log( 6313): 
W/jxcore-log( 6313): JXcore engine is started
I/Choreographer( 6313): Skipped 174 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6313): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6313): Toggling radios to true
I/jxcore-log( 6313): 
,D/BluetoothAdapter( 6313): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6313, uid=10448
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6313): Radios toggled
I/jxcore-log( 6313): 
I/jxcore-log( 6313): My device name is: motorola-XT1072
I/jxcore-log( 6313): 
,I/wpa_supplicant( 1404): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  491): NL - Read 1004 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
,D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
,I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/wpa_supplicant( 1404): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  881): InitialState.processMessage what=4
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 1404): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881):  0
,D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1404): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  491): NL - Read 60 bytes from update socket.
D/TCMD    (  491): NL - ignore NL message, type = 21
D/TCMD    (  491): Listening for incoming client connection request
,V/NativeCrypto( 1744): Read error: ssl=0xb80be9b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1744): SSL shutdown failed: ssl=0xb80be9b0: I/O error during system call, Broken pipe
,D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6373 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.861ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.117ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.876ms
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  881): connected time updated 120954
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/wpa_supplicant( 1404): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1404): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1404): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524292
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1962): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1541): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/ModemStatsDSDetect( 1541): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1541): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1541): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1541): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1541): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6373): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6373): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6373): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6373): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6373): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6373): MmsConfig.loadFromResources
E/Babel_SMS( 6373): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6373): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/PhenotypeConfigurator( 1744): Scheduling Phenotype for one-off execution 9516 seconds from now (1452764016945)
,D/GetConfigurationSnapshotOperation( 1744): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/Settings( 6373): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6373): startup - clean
,D/TCMD    (  491): NL - Read 56 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1404): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1404): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  881): [1,452,764,017,051 ms] noteScanEnd no scan source
,D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@892bac1 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel   ( 6373): deleted: false for 0
,E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24c2be97)
E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cc75884)
E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17f1186d)
E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3866cca2)
E/DataBuffer( 1744): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d6aad33)
I/art     ( 1744): Explicit concurrent mark sweep GC freed 44710(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/23MB, paused 1.317ms total 93.899ms
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6419 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/TCMD    (  491): NL - Read 312 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 192 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 1004 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
,I/wpa_supplicant( 1404): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  491): NL - Read 80 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 80 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/TCMD    (  491): NL - Read 68 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1404): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1404): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,D/TCMD    (  491): NL - Read 1004 bytes from update socket.
D/TCMD    (  491): NL - message type is RTM_NEWLINK
D/TCMD    (  491): Listening for incoming client connection request
E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1224598112
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
,D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/PhenotypeFlagCommitter( 1744): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  881): Start Dhcp Watchdog 2
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
W/ResourcesManager( 6419): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 1744): Using platform SSLCertificateSocketFactory
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
,E/wpa_supplicant( 1404): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1404): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fe353f1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fe353f1 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6373): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6373): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6373): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Killing 5969:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6447): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6447): version 5.5.6 starting
E/DHCPCD  ( 6447): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6447): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6447): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  881): Killing 6182:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/DHCPCD  ( 6447): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6447): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6447): wlan0: sending REQUEST (xid 0x2a02d45e), next in 3.11 seconds
,I/DHCPCD  ( 6447): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5969/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6182/cgroup.procs: No such file or directory
,V/AlarmManager(  881): send {3a40fd92, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  881): done {3a40fd92, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [156ms]
I/vclib   ( 6373): onServiceConnected
,W/Babel   ( 6373): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6447): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6447): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  491): NL - Read 60 bytes from update socket.
D/TCMD    (  491): NL - ignore NL message, type = 20
D/DHCPCD  ( 6447): wlan0: adding route to 192.168.1.0/24
,D/DHCPCD  ( 6447): wlan0: adding default route via 192.168.1.1
D/TCMD    (  491): Listening for incoming client connection request
D/DHCPCD  ( 6447): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6447): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/Uploader( 1744): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  881): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1541): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1541): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1541): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1962): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 09:33:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452764018344], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452764018322]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1962): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1541): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1541): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1541): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1541): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524295
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1962): CM callback handler got msg 524295
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/global frequency( 2563): no tags to log
,D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 56621(3MB) AllocSpace objects, 36(1226KB) LOS objects, 39% free, 7MB/12MB, paused 6.431ms total 63.223ms
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6521 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1474): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 50644(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.990ms total 126.663ms
,I/MusicStore( 6521): Database version: 120
,D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6521): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1559): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 4274(187KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 728us total 29.882ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6521): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/BSUtils ( 2563): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/ResourcesManager( 6521): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6521): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2563): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2563): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioDown
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2563): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2563): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2563): publish the event [tag = DEV_ATTRIBS event name = SW]
,V/JNIHelp ( 6521): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Checkin ( 2563): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,W/ActivityThread( 6521): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6521): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27d56918: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6521): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6521): GMSCore installation verified
,I/ConfigStore( 6521): Config Database version: 1
,I/MediaRouter( 6521): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/global frequency( 2563): BcsDSCheckin.events found events 169
,D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/MusicLeanback( 6521): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6521): type=WIFI subType= reason=null isConnected=true
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/NetworkMonitor( 6521): type=WIFI subType= reason=null isConnected=true
,D/MMApiWebService( 2563): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6554 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6521): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6521): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6087:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     ( 2563): Explicit concurrent mark sweep GC freed 20692(1324KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 11MB/19MB, paused 1.045ms total 64.766ms
,I/MMApiWSBase( 2563): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6087/cgroup.procs: No such file or directory
,V/Mms     ( 6554): mnc/mcc: 
V/Mms     ( 6554): tag: int value: recipientLimit - 20
,V/Mms     ( 6554): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6554): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6554): tag: int value: maxSubjectLength - 80
V/Mms     ( 6554): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6554): tag: bool value: enableGroupMms - false
V/Mms     ( 6554):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6586 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  881): Killing 6117:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6586): Register our PhoneStateListener
,I/art     (  881): Explicit concurrent mark sweep GC freed 7348(362KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.756ms total 111.914ms
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6117/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6586): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6586): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6373:com.google.android.talk/u0a70 (adj 15): empty #7
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2563): now: 196906 ,futureTime: 9223372036854775807
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): now: 196906 ,futureTime: 9223372036854775807
D/PollingManager( 2563): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2563): now: 196906 ,futureTime: 9223372036854775807
D/OtaApp  ( 2563): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/NetworkMonitor( 6521): type=WIFI subType= reason=null isConnected=true
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6373/cgroup.procs: No such file or directory
,D/OtaApp  ( 2563): [debug] > PollingManagerService, now: 196921 ,futureTime: 30635347
D/OtaApp  ( 2563): [debug] > Polling alarm set to expire at: 30635347 Current Time: 196921
D/Central_PollingManager( 1474): now: 196922 ,futureTime: 86474994
D/Central_PollingManager( 1474): Polling alarm set to expire at: 86474994 Current Time: 196922
,D/OtaApp  ( 2563): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2563): [debug] > CusSM.onRadioUp
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452763939725 min interval config: 0 actual interval: 81639
,D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
I/OtaApp  ( 2563): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2563): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2563): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2563): set mOutstandingReq to true.
I/ Nonce  ( 2563):  Nonce getNonce 
I/ Nonce  ( 2563):  Nonce Request 
I/ Nonce  ( 2563):  Nonce execute Request 
,D/MMApiWebService( 2563): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6613 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 1962): Checking schedule, now: 1452764021451 next: 1452763969691
,I/CheckinService( 1962): active receiver: enabled
,I/CheckinService( 1962): Preparing to send checkin request
I/EventLogService( 1962): Accumulating logs since 1452763936634
,D/MMApiProvisionService( 2563): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2563): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2563): createDeviceIdOrLogin update_device
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
D/MMApiProvisionService( 2563): Not proxy app, so login/provision not allowed
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 3546(146KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 675us total 29.598ms
,D/MMApiWebService( 2563): generating token using payload instead of using session token
,D/ Nonce  ( 2563):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2563): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6633 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6633): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6633): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6633): VM with version 2.1.0 has multidex support
I/MultiDex( 6633): install
I/MultiDex( 6633): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6651 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/MMApiWSBase( 2563): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2563): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2563): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2563): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/JNIHelp ( 6633): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/CheckinProvider(  881): 169 events delete 1 left
,W/ResourcesManager( 6651): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/global frequency( 2563): BcsDSCheckin.events found events 0
,D/Checkin ( 2563): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
W/ActivityThread( 6633): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6633): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5826359: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6633): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6633): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6633): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6633): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6651): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6651): MmsConfig.loadMmsSettings
I/Babel_SMS( 6651): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6651): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6651): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6651): MmsConfig.loadFromResources
,E/Babel_SMS( 6651): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6651): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ Nonce  ( 2563):  Nonce Reponse 
D/        ( 2563): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7c927201-3e87-48ee-9b5f-8595f0b7c72b"}
D/MMApiWSBase( 2563): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2563):  Nonce Handle Reponse 
D/MMApiProvisionService( 2563): mOutstandingReq set to false
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
,W/Settings( 6651): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6651): startup - clean
D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
I/Babel   ( 6651): deleted: false for 0
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbefa14e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b66038, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b5c058, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c5a2f0, idLength=0xb54cc730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=4177057680
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c0ea38
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8ba9fe0, signature_length=3041707796
,W/DataUsage( 2563): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,W/DataUsage( 2563): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2563): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6689 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
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
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,W/VideoCapabilities( 6651): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbefa14e0
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b66008, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8b5c058, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c5a330, idLength=0xb54cc730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2586786758
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8b46798
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8b49a00, signature_length=3041707796
D/MMApiProvisionService( 2563):  pTime 1452672215335 sExp 172742 cTime 1452764022918 tTime 1452844957335
D/MMApiProvisionService( 2563):  No login Required 
W/AudioCapabilities( 6651): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6651): Unsupported mime video/mpeg2
,V/AlarmManager(  881): send {2b615281, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/VideoCapabilities( 6651): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6651): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6651): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6651): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6651): onServiceConnected
W/Babel   ( 6651): Attempted to change video mute state without an active call.
,I/Babel   ( 6651): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6419:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6419/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6689): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6689): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6689):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6689):   adb logcat -s GAv4
,W/GAv4    ( 6689): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6689): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6689): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  881): Explicit concurrent mark sweep GC freed 11964(584KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.109ms total 126.297ms
,I/WebViewFactory( 6689): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6689): Time to load native libraries: 1 ms (timestamps 9351-9352)
,I/LibraryLoader( 6689): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6689): Binding Chromium to main looper Looper (main, tid 1) {cf5d4c9}
I/LibraryLoader( 6689): Expected native library version number "",actual native library version number ""
I/chromium( 6689): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
I/BrowserStartupController( 6689): Initializing chromium process, singleProcess=true
W/art     ( 6689): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6689): ApplicationContext is null in ApplicationStatus
,W/chromium( 6689): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6689): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6689): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6689): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6689): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6689): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6689): Local Branch: 
I/Adreno-EGL( 6689): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6689): Local Patches: NONE
I/Adreno-EGL( 6689): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6689): Requires BLUETOOTH permission
,I/NSApplication( 6689): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6762 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6521:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 6769): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6769): dex2oat took 90.999ms (threads: 4)
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6633): Local Branch: 
I/Adreno-EGL( 6633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6633): Local Patches: NONE
I/Adreno-EGL( 6633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6521/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6633): Local Branch: 
I/Adreno-EGL( 6633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6633): Local Patches: NONE
I/Adreno-EGL( 6633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6792 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6554:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6554/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6633): Local Branch: 
I/Adreno-EGL( 6633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6633): Local Patches: NONE
I/Adreno-EGL( 6633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 6792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6633): Local Branch: 
I/Adreno-EGL( 6633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6633): Local Patches: NONE
I/Adreno-EGL( 6633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,I/CheckinTask( 1962): Sending checkin request (9568 bytes)
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6830 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6586:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.833ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 19.249ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.085ms
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6586/cgroup.procs: No such file or directory
,I/MusicStore( 6830): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6830): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6830): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6830): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6830): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6830): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,I/CheckinTask( 1962): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/ActivityThread( 6830): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6830): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27d56918: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6830): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6830): GMSCore installation verified
,I/CheckinService( 1962): Checking schedule, now: 1452764025854 next: 1453365162839
I/CheckinService( 1962): active receiver: disabled
,D/CheckinService( 1962): Recording last checkin time for package unspecified as 1452764025872
,I/ActivityManager(  881): Killing 6613:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6613/cgroup.procs: No such file or directory
,I/ConfigStore( 6830): Config Database version: 1
,I/MediaRouter( 6830): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6830): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6830): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Killing 6651:com.google.android.talk/u0a70 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6651/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6830): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6879 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6830): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6830): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6689:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312199, SEQNUM=4446, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20132, POWER_SUPPLY_CHARGE_COUNTER=-779, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,E/libprocessgroup(  881): failed to kill 1 processes for processgroup 6689
,V/Mms     ( 6879): mnc/mcc: 
,V/Mms     ( 6879): tag: int value: recipientLimit - 20
V/Mms     ( 6879): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6879): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6879): tag: int value: maxSubjectLength - 80
V/Mms     ( 6879): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6879): tag: bool value: enableGroupMms - false
,V/Mms     ( 6879):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,W/ResourcesManager( 6879): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6921 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6762:com.android.chrome/u0a52 (adj 13): empty #7
,D/PhoneMonitor( 6921): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6762/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6921): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6921): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6792:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6792/cgroup.procs: No such file or directory
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452764025872 min interval config: 0 actual interval: 1893
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6955 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1962): Checking schedule, now: 1452764027841 next: 1452764055839
I/CheckinService( 1962): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6972 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6830:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6830/cgroup.procs: No such file or directory
,W/ResourcesManager( 6972): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6972): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6972): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6972): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6972): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6972): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6972): MmsConfig.loadFromResources
,E/Babel_SMS( 6972): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6972): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6972): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6972): startup - clean
,I/Babel   ( 6972): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7008 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6972): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6972): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6972): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6972): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6972): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6972): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6972): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6972): Unrecognized profile 2130706433 for video/avc
,I/art     (  881): Explicit concurrent mark sweep GC freed 10566(544KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.284ms total 119.084ms
,I/vclib   ( 6972): onServiceConnected
,W/Babel   ( 6972): Attempted to change video mute state without an active call.
,I/Babel   ( 6972): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6879:com.android.mms/u0a23 (adj 13): empty #7
,I/jxcore-log( 6313): Test app app.js loaded
I/jxcore-log( 6313): 
,I/Choreographer( 6313): Skipped 772 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6313): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6879/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7008): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7008): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7008): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7008):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7008):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7008): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7008): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7008): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7008): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7008): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7008): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7008): Time to load native libraries: 2 ms (timestamps 4999-5001)
I/LibraryLoader( 7008): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7008): Binding Chromium to main looper Looper (main, tid 1) {cf5d4c9}
I/LibraryLoader( 7008): Expected native library version number "",actual native library version number ""
I/chromium( 7008): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7008): Initializing chromium process, singleProcess=true
,W/art     ( 7008): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7008): ApplicationContext is null in ApplicationStatus
,W/chromium( 7008): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7008): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7008): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7008): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7008): Local Branch: 
I/Adreno-EGL( 7008): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7008): Local Patches: NONE
I/Adreno-EGL( 7008): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7008): Starting up...
,W/AudioManagerAndroid( 7008): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7075 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6921:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6921/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7094 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6955:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6955/cgroup.procs: No such file or directory
,W/ResourcesManager( 7094): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Killing 6972:com.google.android.talk/u0a70 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6972/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
,D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7119 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2563): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7119): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7119): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27d56918: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7119): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7119): GMSCore installation verified
,I/ConfigStore( 7119): Config Database version: 1
,I/MediaRouter( 7119): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7119): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7119): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7119): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7149 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7119): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7119): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 7008:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,V/Mms     ( 7149): mnc/mcc: 
V/Mms     ( 7149): tag: int value: recipientLimit - 20
V/Mms     ( 7149): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7149): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7149): tag: int value: maxSubjectLength - 80
V/Mms     ( 7149): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7149): tag: bool value: enableGroupMms - false
V/Mms     ( 7149):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7008/cgroup.procs: No such file or directory
,W/ResourcesManager( 7149): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7179 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6633:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6633/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7179): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7179): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7179): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 7075:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7075/cgroup.procs: No such file or directory
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452764025872 min interval config: 0 actual interval: 5312
,I/CheckinService( 1962): Checking schedule, now: 1452764031191 next: 1452764055839
I/CheckinService( 1962): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7199 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 25.430ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.133ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.887ms
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7219 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7094:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7094/cgroup.procs: No such file or directory
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1559): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7219): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2babbe0c
,I/GCoreNlp( 1744): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1578): Deferring update until onResume
,I/Babel_SMS( 7219): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7219): MmsConfig.loadMmsSettings
I/Babel_SMS( 7219): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7219): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7219): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7219): MmsConfig.loadFromResources
,E/Babel_SMS( 7219): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7219): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7219): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7219): startup - clean
,I/Babel   ( 7219): deleted: false for 0
,I/art     (  881): Explicit concurrent mark sweep GC freed 17238(873KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.853ms total 122.494ms
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7257 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7219): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7219): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7219): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7219): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7219): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7219): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7219): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7219): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7219): onServiceConnected
,W/Babel   ( 7219): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7257): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7257):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7257):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7219): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7119:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7257): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7119/cgroup.procs: No such file or directory
,W/GAv4    ( 7257): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7257): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7257): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7257): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7257): Time to load native libraries: 1 ms (timestamps 8132-8133)
I/LibraryLoader( 7257): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7257): Binding Chromium to main looper Looper (main, tid 1) {cf5d4c9}
I/LibraryLoader( 7257): Expected native library version number "",actual native library version number ""
,I/chromium( 7257): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7257): Initializing chromium process, singleProcess=true
W/art     ( 7257): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7257): ApplicationContext is null in ApplicationStatus
,W/chromium( 7257): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7257): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7257): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7257): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7257): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7257): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7257): Local Branch: 
I/Adreno-EGL( 7257): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7257): Local Patches: NONE
I/Adreno-EGL( 7257): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7257): Starting up...
,W/AudioManagerAndroid( 7257): Requires BLUETOOTH permission
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7323 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7149:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7149/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7342 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7179:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7179/cgroup.procs: No such file or directory
,W/ResourcesManager( 7342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Killing 7199:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7199/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2563): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2563): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2563): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2563): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2563): onServiceConnected()
,D/GetNotificationsWS( 2563): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2563): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2563): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2563): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2563): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2563): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7368 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2563): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2563): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2563): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2563): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1422): onFinishInput()
,W/IInputConnectionWrapper( 6313): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,231
,D/WearableService( 1744): callingUid 10016, callindPid: 1744
,E/MDM     ( 1744): [203] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1744): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1962): Restart initialization of location
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  881): done {2b615281, *walarm*:com.google.android.intent.action.SEND_IDLE} [10771ms]
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7402 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,W/GCoreFlp( 1744): No location to return for getLastLocation()
,W/FusedLocationProvider( 1744): location=null
,D/PhoneMonitor( 7402): Register our PhoneStateListener
,V/SetupWizard( 7402): Connected to Gservices successfully
,I/ActivityManager(  881): Killing 7219:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7219/cgroup.procs: No such file or directory
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7428 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7458 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7467 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7257:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7323:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7257/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7323/cgroup.procs: No such file or directory
,W/ResourcesManager( 7467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7467): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7467): MmsConfig.loadMmsSettings
I/Babel_SMS( 7467): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7467): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7467): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7467): MmsConfig.loadFromResources
,E/Babel_SMS( 7467): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7467): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7467): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7467): startup - clean
,I/Babel   ( 7467): deleted: false for 0
,W/VideoCapabilities( 7467): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7508 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7467): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7467): Unsupported mime video/mpeg2
,W/asset   ( 7508): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7508): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7508): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7467): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7467): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7467): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7467): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7467): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1962): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1578): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@262d3fe6 new=com.google.android.velvet.VelvetApplication@262d3fe6
,I/UpdateIcingCorporaServi( 7428): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 7467): onServiceConnected
,W/Babel   ( 7467): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7428): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
,V/JNIHelp ( 7467): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  881): Explicit concurrent mark sweep GC freed 15694(762KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.892ms total 143.142ms
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7546 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 7467): Suspending all threads took: 11.627ms
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 50037(3MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 15MB/25MB, paused 1.743ms total 110.559ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 21.954ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 19.935ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 22.888ms
,W/System  ( 7467): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7467): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 7546): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7546): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7546): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7546): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
D/Finsky  ( 7546): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
D/Finsky  ( 7546): [1] Libraries$2.run: Finished loading 1 libraries.
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/Ads     ( 7546): Skipping gmscore version check
,D/Finsky  ( 7546): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  881): Killing 7402:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7402/cgroup.procs: No such file or directory
,D/Finsky  ( 7546): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7368:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7368/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 1962): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1962): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 7458:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7458/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7508:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7508/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310607, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-938, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1744): disconnect managed GoogleApiClient
,V/AlarmManager(  881): send {e88c1a1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {3bef3266, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): send {2c462ae0, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  881): done {3bef3266, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [21ms]
,V/AlarmManager(  881): done {2c462ae0, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [38ms]
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1452764025872 min interval config: 0 actual interval: 47806
,V/AlarmManager(  881): done {e88c1a1, *alarm*:android.intent.action.TIME_TICK} [59ms]
,I/CheckinService( 1962): Checking schedule, now: 1452764073701 next: 1452764055839
I/CheckinService( 1962): active receiver: enabled
,I/CheckinService( 1962): Preparing to send checkin request
I/EventLogService( 1962): Accumulating logs since 1452764021585
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7633 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7633): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7633): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7633): VM with version 2.1.0 has multidex support
I/MultiDex( 7633): install
I/MultiDex( 7633): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7633): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7633): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7633): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5826359: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7633): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1744): callingUid 10016, callindPid: 1744
,D/AuthorizationBluetoothService( 1744): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1744): [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1962): Restart initialization of location
,V/GLSActivity( 1744): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1744): No location to return for getLastLocation()
W/FusedLocationProvider( 1744): location=null
,I/art     ( 7633): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7633): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7633): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
I/WVCdm   (  294): CdmEngine::OpenSession
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54cc960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b66038, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c012a0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c5a310, idLength=0xb55cc730
,I/art     ( 7633): Background partial concurrent mark sweep GC freed 14316(862KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 10MB/16MB, paused 5.555ms total 44.374ms
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1059980365
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c0ea38
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8b463e8, signature_length=3042756372
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
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
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff0000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54cc960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8b66038, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8c377e0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8c5a330, idLength=0xbefa12b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=3876323618
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8b45da8
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8c0ef28, signature_length=3204059796
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
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7678): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7678): dex2oat took 86.102ms (threads: 4)
,I/Adreno-EGL( 7633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7633): Local Branch: 
I/Adreno-EGL( 7633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7633): Local Patches: NONE
I/Adreno-EGL( 7633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7633): Local Branch: 
I/Adreno-EGL( 7633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7633): Local Patches: NONE
I/Adreno-EGL( 7633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7633): Local Branch: 
I/Adreno-EGL( 7633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7633): Local Patches: NONE
I/Adreno-EGL( 7633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7633): Local Branch: 
I/Adreno-EGL( 7633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7633): Local Patches: NONE
I/Adreno-EGL( 7633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,I/CheckinTask( 1962): Sending checkin request (9565 bytes)
,I/CheckinRequestBuilder( 1962): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1962): Classify the device as Phone.
,I/CheckinTask( 1962): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1962): Checking schedule, now: 1452764076618 next: 1453365213612
I/CheckinService( 1962): active receiver: disabled
,D/CheckinService( 1962): Recording last checkin time for package unspecified as 1452764076636
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7697 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7697): Register our PhoneStateListener
,V/SetupWizard( 7697): Connected to Gservices successfully
,D/GCM     ( 1744): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Killing 7342:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  881): Killing 7428:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7342/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7428/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7724 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1a9c6a55
,I/GCoreNlp( 1744): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1578): Deferring update until onResume
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7756 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7775 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 19588(1004KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.521ms total 120.502ms
,I/ActivityManager(  881): Killing 7546:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7546/cgroup.procs: No such file or directory
,W/asset   ( 7775): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7775): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7775): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7775): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1962): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7724): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1578): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@262d3fe6 new=com.google.android.velvet.VelvetApplication@262d3fe6
,I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7814 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7724): UpdateCorporaTask done [took 216 ms] updated apps [took 216 ms] 
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7840 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7697:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7697/cgroup.procs: No such file or directory
,D/Finsky  ( 7840): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7840): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7840): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7840): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7840): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7840): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7840): Skipping gmscore version check
,I/ActivityManager(  881): Killing 7633:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_7633/cgroup.procs: No such file or directory
,D/Finsky  ( 7840): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7840): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1962): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1962): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 7756:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7756/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7467:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7467/cgroup.procs: No such file or directory
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1422): run()
I/Keyboard.Facilitator( 1422): flushDynamicLanguageModels()
,I/ConfigService( 1744): onCreate
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1744): onDestroy
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311106, SEQNUM=4497, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12419, POWER_SUPPLY_CHARGE_COUNTER=-1090, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2463): Disconnected process message: 10, size: 0
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6313): --= Surplus to requirements =--
I/jxcore-log( 6313): 
I/jxcore-log( 6313): ****TEST TOOK:  ms ****
I/jxcore-log( 6313): 
I/jxcore-log( 6313): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6313): 
,D/AndroidRuntime( 7915): 
D/AndroidRuntime( 7915): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7915): CheckJNI is OFF
,D/AndroidRuntime( 7915): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10448 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6313:com.test.thalitest/u0a448 (adj 9): stop com.test.thalitest
,W/PackageSettings(  881): Skipping PackageSetting{1e15101d com.example.hello/10440} due to missing metadata
,I/WindowState(  881): WIN DEATH: Window{32195659 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{343386ca u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  881): Spurious death for ProcessRecord{19601834 6313:com.test.thalitest/u0a448}, curProc for 6313: null
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10448 user=0: pkg removed
,I/art     ( 3006): Explicit concurrent mark sweep GC freed 9350(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 7MB/12MB, paused 770us total 30.523ms
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 16609(979KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/19MB, paused 947us total 110.591ms
,W/GeofencerStateMachine( 1744): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1422): resetDictionaries() : en_US
,I/art     ( 1578): Explicit concurrent mark sweep GC freed 4925(303KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 636us total 64.767ms
,I/Keyboard.Facilitator.DecoderInitializer( 1422): run()
,D/VoicemailCleanupService( 1624): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1422): createOrResetDecoder
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7949 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 14340(999KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 12.296ms total 145.662ms
I/art     (  881): WaitForGcToComplete blocked for 111.563ms for cause Explicit
,I/ConfigService( 1744): onCreate
,W/ContextImpl( 7949): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1744): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1744): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): run()
,D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1962): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/Launcher( 1578): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@262d3fe6 new=com.google.android.velvet.VelvetApplication@262d3fe6
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7979 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 7724): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/TaskPersister(  881): removeObsoleteFile: deleting file=6_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = user
,I/Icing   ( 1962): doRemovePackageData com.test.thalitest
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1422): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1422): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1422): run()
I/StatsUtilsManager( 1422): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1422): shouldRecordStats() = Too Soon
,I/art     (  881): Explicit concurrent mark sweep GC freed 7542(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.351ms total 299.556ms
,I/Launcher( 1578): Deferring update until onResume
,D/AndroidRuntime( 7915): Shutting down VM
,I/UpdateIcingCorporaServi( 7724): UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
,I/GAv4    ( 7979): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7979):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7979):   adb logcat -s GAv4
,W/GAv4    ( 7979): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7979): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7979): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 7979): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7979): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 7979): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7979): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7979): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SQLiteLog( 7979): (3850) statement aborts at 2: [PRAGMA journal_mode=WAL] 
,E/AbstractDatabaseInstance( 7979): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteDatabase.enableWriteAheadLogging(SQLiteDatabase.java:1958)
E/AbstractDatabaseInstance( 7979): 	at aev.getWritableDatabase(PG:20264)
E/AbstractDatabaseInstance( 7979): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7979): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7979): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7979): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7979): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7979): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7979): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  881): Killing 7775:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/System  ( 7979): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7979): Installed default security provider GmsCore_OpenSSL
,E/AbstractDatabaseInstance( 7979): Failed to query Account133 object
E/AbstractDatabaseInstance( 7979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AbstractDatabaseInstance( 7979): 	at android.database.sqlite.SQLiteDatabase.enableWriteAheadLogging(SQLiteDatabase.java:1958)
E/AbstractDatabaseInstance( 7979): 	at aev.getWritableDatabase(PG:20264)
E/AbstractDatabaseInstance( 7979): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7979): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7979): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7979): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7979): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7979): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7979): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7979): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7979): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7979): 	at java.lang.Thread.run(Thread.java:818)
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
