#### Test 54970261e0c50c1_thali04_motorola-XT1072 Logs


```
--------- beginning of system
E/BackupManagerService(  881): Timeout restoring application @pm@
W/BackupManagerService(  881): Tried to clear data for @pm@ but not found
--------- beginning of main
W/GmsBackupTransport( 1715): Restore processing aborted, no more packages
E/BackupManagerService(  881): Failure getting next package name
E/BackupManagerService(  881): Duplicate finish
,D/AndroidRuntime( 6244): 
D/AndroidRuntime( 6244): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6244): CheckJNI is OFF
D/AndroidRuntime( 6244): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6263 uid=10425 gids={50425, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6244): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6263): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6263): Time to load native libraries: 14 ms (timestamps 9632-9646)
I/LibraryLoader( 6263): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6263): Binding Chromium to main looper Looper (main, tid 1) {1c8027de}
I/LibraryLoader( 6263): Expected native library version number "",actual native library version number ""
I/chromium( 6263): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6263): Initializing chromium process, singleProcess=true
W/art     ( 6263): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6263): ApplicationContext is null in ApplicationStatus
W/chromium( 6263): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6263): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6263): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6263): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6263): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6263): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6263): Local Branch: 
I/Adreno-EGL( 6263): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6263): Local Patches: NONE
I/Adreno-EGL( 6263): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cd0a430:true
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{3be7e5f5 u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6263): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6263): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6263): CordovaWebView is running on device made by: motorola
W/art     ( 6263): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6263): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6263): Render dirty regions requested: true
D/Atlas   ( 6263): Validating map...
W/chromium( 6263): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6263): Initialized EGL, version 1.4
D/OpenGLRenderer( 6263): Enabling debug mode 0
I/Keyboard.Facilitator( 1413): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1010
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +939ms (total +1s10ms)
W/IInputConnectionWrapper( 6263): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6263): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6263): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6263): Cannot call determinedVisibility() - never saw a connection for the pid: 6263
,D/JsMessageQueue( 6263): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6263): JniHelper::setJavaVM(0xb786c310), pthread_self() = -1212165184
D/JX-Cordova( 6263): jxcore cordova android initializing
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 6263): Initializing JXcore engine
W/jxcore-log( 6263): JXcore engine is ready
,W/jxcore-log( 6263): Starting JXcore engine
,W/.test.thalitest( 6263): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10425 path="socket:[6755]" dev="sockfs" ino=6755 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6263): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10425 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6263): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10425 path="socket:[7505]" dev="sockfs" ino=7505 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6263): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10425 path="socket:[25476]" dev="sockfs" ino=25476 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6263): Platform android
W/jxcore-log( 6263): 
W/jxcore-log( 6263): Process ARCH arm
W/jxcore-log( 6263): 
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6263): JXcore Cordova bridge is ready!
I/jxcore-log( 6263): 
W/jxcore-log( 6263): JXcore engine is started
,I/Choreographer( 6263): Skipped 172 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6263): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6263): Toggling radios to true
I/jxcore-log( 6263): 
,D/BluetoothAdapter( 6263): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6263, uid=10425
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6263): Radios toggled
I/jxcore-log( 6263): 
,D/TCMD    (  468): NL - Read 1004 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 68 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 68 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
,I/wpa_supplicant( 1402): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
,D/MDMCTBK (  305): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  305):  STA Disconnected !!
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  305): MdmCutbackHndler,Wifi disconnected !!!
,I/MDMCTBK (  305): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
E/MDMCTBK (  305): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/wpa_supplicant( 1402): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  305): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1402): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  305): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  881): InitialState.processMessage what=4
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881):  0
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService(  881): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1402): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  302): Clearing all IP addresses on wlan0
D/TCMD    (  468): NL - Read 60 bytes from update socket.
D/TCMD    (  468): NL - ignore NL message, type = 21
D/TCMD    (  468): Listening for incoming client connection request
,V/NativeCrypto( 1715): Read error: ssl=0xb7b6be50: I/O error during system call, Connection timed out
V/NativeCrypto( 1715): SSL shutdown failed: ssl=0xb7b6be50: I/O error during system call, Broken pipe
D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6323 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  881): connected time updated 125480
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/wpa_supplicant( 1402): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1402): wlan0: CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  305): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1402): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6323): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  302): Clearing all IP addresses on wlan0
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  881): Explicit concurrent mark sweep GC freed 53438(2MB) AllocSpace objects, 3(229KB) LOS objects, 33% free, 20MB/30MB, paused 1.888ms total 143.103ms
,I/Babel_SMS( 6323): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6323): MmsConfig.loadMmsSettings
I/Babel_SMS( 6323): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6323): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6323): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6323): MmsConfig.loadFromResources
,E/Babel_SMS( 6323): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6323): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6323): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6323): startup - clean
,I/Babel   ( 6323): deleted: false for 0
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  305): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  305): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1402): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  305): Event received = Trying to associate with
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  468): NL - Read 56 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
,E/wpa_supplicant( 1402): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  881): [1,452,274,532,800 ms] noteScanEnd no scan source
,E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1960bfb2 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6362 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6362): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6323): Unrecognized profile 2130706433 for video/avc
,D/TCMD    (  468): NL - Read 312 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 192 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 68 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 1004 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
W/AudioCapabilities( 6323): Unsupported mime audio/amr-wb-plus
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1402): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  305): Event received = Associated with c0:ff:d4
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
,W/VideoCapabilities( 6323): Unsupported mime video/mpeg2
,D/TCMD    (  468): NL - Read 80 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 80 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
,D/TCMD    (  468): Listening for incoming client connection request
D/TCMD    (  468): NL - Read 68 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
,D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1402): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1402): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  468): NL - Read 1004 bytes from update socket.
D/TCMD    (  468): NL - message type is RTM_NEWLINK
D/TCMD    (  468): Listening for incoming client connection request
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  305): Event received = WPA: Key negotiation com
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  305): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  305):  STA Connected !!
E/MDMCTBK (  305): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  305): get_freq !!, resp=2412
I/MDMCTBK (  305): get_freq !!, Strip data
I/MDMCTBK (  305): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  305): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  305): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
I/MDMCTBK (  305): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  305): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  305): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): get_property_value, Enter
I/MDMCTBK (  305): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  305): get_property_value, Exit
I/MDMCTBK (  305): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1224008240
I/MDMCTBK (  305): return from set_get_from_wpa_supplicant
I/MDMCTBK (  305): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  305): set_property_value, Enter
I/MDMCTBK (  305): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  305): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  305): set_property_value, Exit
E/MDMCTBK (  305): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  305): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  305): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  305): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  305): , reply_len: 3, ret: 0
E/MDMCTBK (  305): MdmCutbackHndler, resp=OK
E/MDMCTBK (  305): 
D/MDMCTBK (  305): wifi_set_tx_pwr: Exit
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/VideoCapabilities( 6323): Unsupported profile 4 for video/mp4v-es
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  302): Setting iface cfg
,E/WifiStateMachine(  881): Start Dhcp Watchdog 2
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
,W/VideoCapabilities( 6323): Unrecognized profile 2130706433 for video/avc
,E/wpa_supplicant( 1402): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1402): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4439547 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4439547 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6323): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6323): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6323): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Killing 6029:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,E/DHCPCD  ( 6382): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6382): version 5.5.6 starting
E/DHCPCD  ( 6382): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6382): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6382): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6029/cgroup.procs: No such file or directory
,V/AlarmManager(  881): send {1ad6429f, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/vclib   ( 6323): onServiceConnected
W/Babel   ( 6323): Attempted to change video mute state without an active call.
,V/AlarmManager(  881): done {1ad6429f, *walarm*:com.google.android.intent.action.SEND_IDLE} [90ms]
D/DHCPCD  ( 6382): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6382): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6382): wlan0: sending REQUEST (xid 0xb58578e2), next in 3.70 seconds
,I/ActivityManager(  881): Killing 6061:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/DHCPCD  ( 6382): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6061/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6382): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6382): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  468): NL - Read 60 bytes from update socket.
D/TCMD    (  468): NL - ignore NL message, type = 20
D/TCMD    (  468): Listening for incoming client connection request
D/DHCPCD  ( 6382): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6382): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6382): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6382): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  881): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
I/ModemStatsDSDetect( 1534): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=0
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 17:35:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452274534050], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452274534029]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1534): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1534): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1534): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1534): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/global frequency( 2585): no tags to log
,D/Checkin ( 2585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 55564(3MB) AllocSpace objects, 36(1230KB) LOS objects, 40% free, 7MB/12MB, paused 765us total 46.828ms
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 2585): Explicit concurrent mark sweep GC freed 9486(511KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 1.219ms total 66.316ms
,I/BSUtils ( 2585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 4050(170KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 740us total 27.065ms
,D/BSUtils ( 2585): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2585): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2585): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2585): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2585): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2585): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1458): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2585): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6456 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1458): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CCE     ( 2585): Registering with Alarm Manager to restart CCE
,D/Central_PollingManager( 1458): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2585): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2585): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2585): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2585): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2585): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2585): [debug] > CusSM.onRadioDown
,I/MusicStore( 6456): Database version: 120
,I/art     (  881): Explicit concurrent mark sweep GC freed 29455(1470KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.670ms total 129.603ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6456): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6456): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6456): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6456): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6456): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6456): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7fbf25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6456): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6456): GMSCore installation verified
,I/ConfigStore( 6456): Config Database version: 1
,I/MediaRouter( 6456): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6456): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6456): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6490 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6456): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6456): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 5894:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 6490): mnc/mcc: 
V/Mms     ( 6490): tag: int value: recipientLimit - 20
V/Mms     ( 6490): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6490): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6490): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6490): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6490): tag: bool value: enableGroupMms - false
,V/Mms     ( 6490):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5894/cgroup.procs: No such file or directory
,W/ResourcesManager( 6490): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6517 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 5971:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6517): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_5971/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6517): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6517): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6323:com.google.android.talk/u0a70 (adj 15): empty #7
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6323/cgroup.procs: No such file or directory
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): now: 198934 ,futureTime: 9223372036854775807
D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): now: 198935 ,futureTime: 9223372036854775807
D/PollingManager( 2585): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2585): now: 198935 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2585): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1458): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2585): [debug] > PollingManagerService, now: 198937 ,futureTime: 81623181
D/OtaApp  ( 2585): [debug] > Polling alarm set to expire at: 81623181 Current Time: 198938
,D/Central_PollingManager( 1458): now: 198939 ,futureTime: 86475843
D/Central_PollingManager( 1458): Polling alarm set to expire at: 86475843 Current Time: 198939
,I/NetworkMonitor( 6456): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2585): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2585): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2585): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2585): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2585): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2585): createDeviceIdOrLogin update_device
,D/Checkin ( 2585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2585): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2585): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2585): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,I/CheckinService( 6118): Checkin interval check for package: unspecified last checkin: 1452274453838 min interval config: 0 actual interval: 83413
,D/Checkin ( 2585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2585): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2585): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2585): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2585): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2585): isDeviceProvisioned: deviceId = 2072049230914535424
I/CheckinService( 6118): Disabling old GoogleServicesFramework version
,D/CCE     ( 2585): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2585): createDeviceIdOrLogin update_device
,D/Checkin ( 2585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2585): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2585): set mOutstandingReq to true.
I/ Nonce  ( 2585):  Nonce getNonce 
I/ Nonce  ( 2585):  Nonce Request 
I/ Nonce  ( 2585):  Nonce execute Request 
,I/CheckinService( 6118): Checking schedule, now: 1452274537303 next: 1452274483818
I/CheckinService( 6118): active receiver: enabled
,I/iu.SyncManager( 6118): SYNC; picasa accounts
,D/NetworkLogImpl( 6118): Loaded NetworkSpeedPredictor
,D/MMApiWebService( 2585): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/CheckinService( 6118): Preparing to send checkin request
,I/iu.Environment( 6118): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/MMApiProvisionService( 2585): isDeviceProvisioned: deviceId = 2072049230914535424
,I/EventLogService( 6118): Accumulating logs since 1452274450297
,D/CCE     ( 2585): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2585): createDeviceIdOrLogin update_device
,D/Checkin ( 2585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2585): Not proxy app, so login/provision not allowed
,I/iu.UploadsManager( 6118): num queued entries: 0
I/iu.UploadsManager( 6118): num updated entries: 0
I/iu.SyncManager( 6118): NEXT; no task
,D/MMApiWebService( 2585): generating token using payload instead of using session token
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6550 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/ Nonce  ( 2585):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2585): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2585): publish the event [tag = MOT_CCE event name = LOG]
,I/CheckinRequestBuilder( 6118): Checkin reason type: 8 attempt count: 1
,D/WifiService(  881): New client listening to asynchronous messages
,E/ActivityThread( 6118): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  881): Explicit concurrent mark sweep GC freed 10191(497KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.505ms total 110.445ms
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6573 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6590 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.994ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.085ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.685ms
,W/ResourcesManager( 6590): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6590): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager(  881): send {35dfa834, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/MultiDex( 6590): VM with version 2.1.0 has multidex support
I/MultiDex( 6590): install
I/MultiDex( 6590): VM has multidex support, MultiDex support library is disabled.
E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/Babel_SMS( 6573): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6573): MmsConfig.loadMmsSettings
I/Babel_SMS( 6573): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6573): MmsConfig.loadFromDatabase
,V/JNIHelp ( 6590): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 6573): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6573): MmsConfig.loadFromResources
,E/Babel_SMS( 6573): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6573): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 6590): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6590): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e8e1a33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6590): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6590): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6590): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 6573): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6573): startup - clean
,I/Babel   ( 6573): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6628 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ Nonce  ( 2585):  Nonce Reponse 
D/        ( 2585): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"00a20886-93dc-4e04-a39e-2440e2c7f9ef"}
D/MMApiWSBase( 2585): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2585):  Nonce Handle Reponse 
D/MMApiProvisionService( 2585): mOutstandingReq set to false
,D/NativeLibraryUtils( 6590): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb131a960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7912f08, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb78ecd58, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a0df80, idLength=0xb5604730
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=3705230786
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7946518
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7941da8, signature_length=3042985748
,W/AudioCapabilities( 6573): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6573): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6573): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6573): onServiceConnected
W/Babel   ( 6573): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 4501(193KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 885us total 102.075ms
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/Babel   ( 6573): connection state changed from UNKNOWN to CONNECTED
,D/MMApiProvisionService( 2585):  pTime 1452107623780 sExp 172742 cTime 1452274539058 tTime 1452280365780
D/MMApiProvisionService( 2585):  No login Required 
,I/ActivityManager(  881): Killing 6362:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,W/DataUsage( 2585): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2585): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb131a960
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7941fa0, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb78ecd58, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a0dfc0, idLength=0xbea1d2b0
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=2458016249
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7946518
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7912e08, signature_length=3198276244
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6362/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6628): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6628): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6628): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6628): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6628): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6628):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6628):   adb logcat -s GAv4
,W/GAv4    ( 6628): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6628): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6628): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  308): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 6676): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 6628): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 6676): dex2oat took 63.186ms (threads: 4)
,I/LibraryLoader( 6628): Time to load native libraries: 1 ms (timestamps 1349-1350)
I/LibraryLoader( 6628): Expected native library version number "",actual native library version number ""
,I/Adreno-EGL( 6590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6590): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6590): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6590): Local Branch: 
I/Adreno-EGL( 6590): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6590): Local Patches: NONE
I/Adreno-EGL( 6590): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/WebViewChromiumFactoryProvider( 6628): Binding Chromium to main looper Looper (main, tid 1) {3c91f623}
,I/LibraryLoader( 6628): Expected native library version number "",actual native library version number ""
I/chromium( 6628): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6628): Initializing chromium process, singleProcess=true
W/art     ( 6628): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6628): ApplicationContext is null in ApplicationStatus
,W/chromium( 6628): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6628): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6628): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6628): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6628): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6628): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6628): Local Branch: 
I/Adreno-EGL( 6628): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6628): Local Patches: NONE
I/Adreno-EGL( 6628): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6590): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6590): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6590): Local Branch: 
I/Adreno-EGL( 6590): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6590): Local Patches: NONE
I/Adreno-EGL( 6590): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6628): Requires BLUETOOTH permission
I/NSApplication( 6628): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6702 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6456:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6456/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6725 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6490:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 6590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6590): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6590): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6590): Local Branch: 
I/Adreno-EGL( 6590): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6590): Local Patches: NONE
I/Adreno-EGL( 6590): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6590): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6590): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6590): Local Branch: 
I/Adreno-EGL( 6590): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6590): Local Patches: NONE
I/Adreno-EGL( 6590): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6490/cgroup.procs: No such file or directory
,W/ResourcesManager( 6725): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6118): Classify the device as Phone.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6754 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinTask( 6118): Sending checkin request (9516 bytes)
,I/ActivityManager(  881): Killing 6550:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6754): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 6517:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/CheckinRequestBuilder( 6118): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6550/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2585): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6517/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2585): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2585): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2585): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2585): onServiceConnected()
,D/GetNotificationsWS( 2585): onServiceConnected(): Registered for remote service callbacks...
E/ActivityThread( 6118): Failed to find provider info for com.google.android.wearable.settings
D/GetNotificationsWS( 2585): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6784 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2585): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 6784): Database version: 120
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,I/art     ( 6090): Explicit concurrent mark sweep GC freed 1555(68KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 409us total 33.033ms
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310799, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20132, POWER_SUPPLY_CHARGE_COUNTER=-725, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 6118): Classify the device as Phone.
,I/CheckinTask( 6118): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6118): Checking schedule, now: 1452274541698 next: 1452875678690
I/CheckinService( 6118): active receiver: disabled
,D/CheckinService( 6118): Recording last checkin time for package unspecified as 1452274541724
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6784): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/ActivityManager(  881): Killing 6573:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  881): Explicit concurrent mark sweep GC freed 13081(672KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.783ms total 115.146ms
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6573/cgroup.procs: No such file or directory
,W/ResourcesManager( 6784): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6784): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6784): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6784): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6784): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7fbf25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6784): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6784): GMSCore installation verified
,I/ConfigStore( 6784): Config Database version: 1
,I/MediaRouter( 6784): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6784): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6784): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Killing 6628:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6628/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6784): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6833 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6784): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6784): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6702:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 6833): mnc/mcc: 
V/Mms     ( 6833): tag: int value: recipientLimit - 20
,V/Mms     ( 6833): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6833): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6833): tag: int value: maxSubjectLength - 80
V/Mms     ( 6833): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6833): tag: bool value: enableGroupMms - false
V/Mms     ( 6833):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6702/cgroup.procs: No such file or directory
,W/ResourcesManager( 6833): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6869 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6754:android.process.acore/u0a7 (adj 13): empty #7
,D/PhoneMonitor( 6869): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6754/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6869): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6869): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6725:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6725/cgroup.procs: No such file or directory
,I/CheckinService( 6118): Checkin interval check for package: unspecified last checkin: 1452274541724 min interval config: 0 actual interval: 1759
,I/CheckinService( 6118): Checking schedule, now: 1452274543496 next: 1452274571690
I/CheckinService( 6118): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6891 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6911 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6784:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6784/cgroup.procs: No such file or directory
,W/ResourcesManager( 6911): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6911): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6911): MmsConfig.loadMmsSettings
I/Babel_SMS( 6911): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6911): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6911): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6911): MmsConfig.loadFromResources
,E/Babel_SMS( 6911): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6911): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6911): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6911): startup - clean
,I/Babel   ( 6911): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6946 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6911): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6911): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6911): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6911): onServiceConnected
W/Babel   ( 6911): Attempted to change video mute state without an active call.
,I/GAv4    ( 6946): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6946):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6946):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 6911): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6833:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 6946): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 6263): Test app app.js loaded
I/jxcore-log( 6263): 
,I/Choreographer( 6263): Skipped 758 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6263): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6833/cgroup.procs: No such file or directory
,W/GAv4    ( 6946): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,W/GAv4    ( 6946): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6946): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6946): Time to load native libraries: 2 ms (timestamps 6735-6737)
I/LibraryLoader( 6946): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6946): Binding Chromium to main looper Looper (main, tid 1) {3c91f623}
I/LibraryLoader( 6946): Expected native library version number "",actual native library version number ""
,I/chromium( 6946): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6946): Initializing chromium process, singleProcess=true
,W/art     ( 6946): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6946): ApplicationContext is null in ApplicationStatus
,W/chromium( 6946): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6946): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6946): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6946): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6946): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6946): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6946): Local Branch: 
I/Adreno-EGL( 6946): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6946): Local Patches: NONE
I/Adreno-EGL( 6946): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6946): Requires BLUETOOTH permission
,I/NSApplication( 6946): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7013 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6869:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 24.451ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 24.032ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.098ms
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6869/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7037 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6891:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6891/cgroup.procs: No such file or directory
,W/ResourcesManager( 7037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7060 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7083 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6946:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7060): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 6911:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6946/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6911/cgroup.procs: No such file or directory
,I/MusicStore( 7083): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7083): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7083): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7083): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7083): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7083): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7083): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7083): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7fbf25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7083): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7083): GMSCore installation verified
,I/ConfigStore( 7083): Config Database version: 1
,I/art     (  881): Explicit concurrent mark sweep GC freed 11656(572KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.050ms total 121.077ms
,I/MediaRouter( 7083): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7083): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7083): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7083): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7120 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7083): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7083): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6590:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,V/Mms     ( 7120): mnc/mcc: 
V/Mms     ( 7120): tag: int value: recipientLimit - 20
V/Mms     ( 7120): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7120): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7120): tag: int value: maxSubjectLength - 80
V/Mms     ( 7120): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7120): tag: bool value: enableGroupMms - false
V/Mms     ( 7120):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6590/cgroup.procs: No such file or directory
,W/ResourcesManager( 7120): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7156 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7013:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7013/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7156): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7156): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7156): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 7037:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7037/cgroup.procs: No such file or directory
,I/CheckinService( 6118): Checkin interval check for package: unspecified last checkin: 1452274541724 min interval config: 0 actual interval: 5046
,I/CheckinService( 6118): Checking schedule, now: 1452274546776 next: 1452274571690
I/CheckinService( 6118): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7176 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7199 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7060:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7060/cgroup.procs: No such file or directory
,W/ResourcesManager( 7199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7199): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7199): MmsConfig.loadMmsSettings
I/Babel_SMS( 7199): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7199): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7199): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7199): MmsConfig.loadFromResources
,E/Babel_SMS( 7199): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7199): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/Settings( 7199): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7199): startup - clean
,I/Babel   ( 7199): deleted: false for 0
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5b8aef6
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7235 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,W/VideoCapabilities( 7199): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7199): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7199): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7199): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7199): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7199): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7199): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7199): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7199): onServiceConnected
,W/Babel   ( 7199): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7235): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 7235): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7235):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7235):   adb logcat -s GAv4
W/ContextImpl( 7235): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7199): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7083:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7235): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7235): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7083/cgroup.procs: No such file or directory
,W/GAv4    ( 7235): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7235): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7235): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7235): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7235): Time to load native libraries: 1 ms (timestamps 9862-9863)
I/LibraryLoader( 7235): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7235): Binding Chromium to main looper Looper (main, tid 1) {3c91f623}
,I/LibraryLoader( 7235): Expected native library version number "",actual native library version number ""
I/chromium( 7235): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7235): Initializing chromium process, singleProcess=true
,W/art     ( 7235): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7235): ApplicationContext is null in ApplicationStatus
,W/chromium( 7235): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7235): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7235): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7235): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7235): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7235): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7235): Local Branch: 
I/Adreno-EGL( 7235): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7235): Local Patches: NONE
I/Adreno-EGL( 7235): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7235): Requires BLUETOOTH permission
I/NSApplication( 7235): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7303 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7120:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7120/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7330 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7156:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7156/cgroup.procs: No such file or directory
,W/ResourcesManager( 7330): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7354 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 26.193ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.168ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.765ms
,I/ActivityManager(  881): Killing 7199:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7354): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7176:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7199/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2585): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7176/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2585): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2585): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2585): onServiceConnected()
D/GetNotificationsWS( 2585): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2585): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2585): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2585): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2585): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2585): [debug] > In cancelAnyPendingIntentSetPreviously
,I/art     (  881): Explicit concurrent mark sweep GC freed 17221(859KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.717ms total 120.895ms
I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2585): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7395 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2585): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2585): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2585): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2585): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2585): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2585): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2585): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2585): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2585): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
W/IInputConnectionWrapper( 6263): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,205
,V/AlarmManager(  881): done {35dfa834, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [11221ms]
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,D/LocationInitializer( 6118): Restart initialization of location
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1715): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7421 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,D/PhoneMonitor( 7421): Register our PhoneStateListener
,V/SetupWizard( 7421): Connected to Gservices successfully
,I/ActivityManager(  881): Killing 7235:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7235/cgroup.procs: No such file or directory
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7447 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7472 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7489 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7303:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7330:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7303/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7330/cgroup.procs: No such file or directory
,W/ResourcesManager( 7489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7489): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7489): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7489): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7489): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7489): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7489): MmsConfig.loadFromResources
,E/Babel_SMS( 7489): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7489): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7489): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7489): startup - clean
,I/Babel   ( 7489): deleted: false for 0
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7522 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7489): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7489): Unsupported mime video/mpeg2
,W/asset   ( 7522): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7522): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7489): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7489): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6118): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@51a5578 new=com.google.android.velvet.VelvetApplication@51a5578
,I/PackageBroadcastService( 6118): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7447): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7554 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7489): onServiceConnected
W/Babel   ( 7489): Attempted to change video mute state without an active call.
,I/Icing   ( 6118): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7447): UpdateCorporaTask done [took 185 ms] updated apps [took 185 ms] 
,I/ActivityManager(  881): Killing 7421:com.google.android.setupwizard/u0a35 (adj 15): empty #7
V/JNIHelp ( 7489): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7421/cgroup.procs: No such file or directory
,W/System  ( 7489): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7489): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7589 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7395:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7395/cgroup.procs: No such file or directory
,D/Finsky  ( 7589): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7589): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7589): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7589): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7589): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7589): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7589): Skipping gmscore version check
,D/Finsky  ( 7589): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7589): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7472:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7472/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6118): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6118): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6118): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 7522:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7522/cgroup.procs: No such file or directory
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  881): Killing 7447:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7447/cgroup.procs: No such file or directory
,I/CheckinService( 6118): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311154, SEQNUM=4468, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-811, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311268, SEQNUM=4470, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-868, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {2cd94be8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {237fc668, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  881): send {27ac1a37, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  881): done {2cd94be8, *alarm*:android.intent.action.TIME_TICK} [83ms]
,V/AlarmManager(  881): done {237fc668, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [85ms]
,V/AlarmManager(  881): done {27ac1a37, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [92ms]
,I/CheckinService( 6118): Checkin interval check for package: unspecified last checkin: 1452274541724 min interval config: 0 actual interval: 47336
,I/CheckinService( 6118): Checking schedule, now: 1452274589072 next: 1452274571690
I/CheckinService( 6118): active receiver: enabled
,I/CheckinService( 6118): Preparing to send checkin request
I/EventLogService( 6118): Accumulating logs since 1452274537554
,I/CheckinRequestBuilder( 6118): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6118): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  881): Explicit concurrent mark sweep GC freed 16578(846KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.767ms total 112.315ms
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7658 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7658): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7658): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7658): VM with version 2.1.0 has multidex support
I/MultiDex( 7658): install
I/MultiDex( 7658): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7658): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7658): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7658): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e8e1a33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7658): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,E/MDM     ( 1715): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6118): Restart initialization of location
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,I/art     ( 7658): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7658): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7658): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  308): Instantiating CDM.
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb5604960
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb78dc940, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79c2468, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a0dfa0, idLength=0xb131a730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=416266452
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7946518
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7912d90, signature_length=2972821268
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
,D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  308): CdmEngine::OpenSession
I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
,D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5029000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb141a960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb78dcb30, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79c2468, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7a0dfc0, idLength=0xb131a730
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=2296131450
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7946518
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7912d90, signature_length=2972821268
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  308): CdmEngine::CloseSession
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  308): L3 Terminate.
D/DrmWidevineDash(  308): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  308): Service_Uninitialize: starts!
D/QSEECOMAPI: (  308): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  308): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  308): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7713): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7713): dex2oat took 83.591ms (threads: 4)
,I/Adreno-EGL( 7658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7658): Local Branch: 
I/Adreno-EGL( 7658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7658): Local Patches: NONE
I/Adreno-EGL( 7658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7658): Local Branch: 
I/Adreno-EGL( 7658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7658): Local Patches: NONE
I/Adreno-EGL( 7658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7658): Local Branch: 
I/Adreno-EGL( 7658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7658): Local Patches: NONE
I/Adreno-EGL( 7658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7658): Local Branch: 
I/Adreno-EGL( 7658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7658): Local Patches: NONE
I/Adreno-EGL( 7658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6118): Classify the device as Phone.
,I/CheckinTask( 6118): Sending checkin request (9522 bytes)
,I/CheckinRequestBuilder( 6118): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6118): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6118): Classify the device as Phone.
,I/CheckinTask( 6118): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6118): Checking schedule, now: 1452274593206 next: 1452875730201
I/CheckinService( 6118): active receiver: disabled
,D/CheckinService( 6118): Recording last checkin time for package unspecified as 1452274593225
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7733 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7733): Register our PhoneStateListener
,V/SetupWizard( 7733): Connected to Gservices successfully
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Killing 7554:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  881): Killing 7354:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7554/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7354/cgroup.procs: No such file or directory
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7755 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 27.725ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.348ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.340ms
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@334b2e15
,I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,I/art     ( 1715): Explicit concurrent mark sweep GC freed 104701(5MB) AllocSpace objects, 31(519KB) LOS objects, 40% free, 15MB/25MB, paused 1.019ms total 115.801ms
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7794 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7816 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7589:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7589/cgroup.procs: No such file or directory
,W/ResourcesManager( 7489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7839 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7733:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 7816): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7733/cgroup.procs: No such file or directory
,W/asset   ( 7839): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7839): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7839): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7839): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6118): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6118): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@51a5578 new=com.google.android.velvet.VelvetApplication@51a5578
,I/UpdateIcingCorporaServi( 7755): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6118): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7865 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  881): Explicit concurrent mark sweep GC freed 16476(868KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.680ms total 121.796ms
,W/ResourcesManager( 7865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7755): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7890 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7658:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_7658/cgroup.procs: No such file or directory
,D/Finsky  ( 7890): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7890): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7890): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7890): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7890): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7890): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7890): Skipping gmscore version check
,D/Finsky  ( 7890): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7890): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7794:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7794/cgroup.procs: No such file or directory
,I/Icing   ( 6118): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6118): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 7839:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7839/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7489:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7489/cgroup.procs: No such file or directory
I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1715): onCreate
,I/ConfigService( 1715): onDestroy
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  305): NetlinkHandler, power_supply subsys
I/MDMCTBK (  305): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  305): checkDefaultInst, current pid is = 305
I/MDMCTBK (  305): checkDefaultInst, pid match
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  305): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  305): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311740, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-1076, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2451): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6263): ****TEST TOOK:  ms ****
I/jxcore-log( 6263): 
I/jxcore-log( 6263): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6263): 
,D/AndroidRuntime( 7961): 
D/AndroidRuntime( 7961): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7961): CheckJNI is OFF
,D/AndroidRuntime( 7961): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10425 user=-1: uninstall pkg
,I/ActivityManager(  881): Killing 6263:com.test.thalitest/u0a425 (adj 9): stop com.test.thalitest
,W/PackageSettings(  881): Skipping PackageSetting{3c5ff757 com.example.hello/10420} due to missing metadata
,I/WindowState(  881): WIN DEATH: Window{2f2d7960 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3be7e5f5 u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  881): Spurious death for ProcessRecord{37b68663 6263:com.test.thalitest/u0a425}, curProc for 6263: null
,I/ActivityManager(  881): Force stopping com.test.thalitest appid=10425 user=0: pkg removed
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3be7e5f5 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{3be7e5f5 u0 com.test.thalitest/.MainActivity t3 f}
,I/art     ( 2992): Explicit concurrent mark sweep GC freed 10212(2MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 7MB/12MB, paused 975us total 38.965ms
,I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
,I/Decoder ( 1413): createOrResetDecoder
,W/GeofencerStateMachine( 1715): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ConfigService( 1715): onCreate
,D/VoicemailCleanupService( 7816): Cleaning up data for package: com.test.thalitest
,I/art     ( 1571): Explicit concurrent mark sweep GC freed 5071(312KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 495us total 126.181ms
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7992 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7992): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
W/ResourcesManager( 7992): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7992): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7992): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 14831(980KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.060ms total 194.680ms
,I/art     (  881): WaitForGcToComplete blocked for 109.286ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8016 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  881): Killing 7755:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  881): Explicit concurrent mark sweep GC freed 4469(235KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.510ms total 164.110ms
,I/Launcher( 1571): Deferring update until onResume
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7755/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
,W/ContextImpl( 8016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6118): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6118): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6118): Reading stored module config
,D/ChimeraCfgMgr( 6118): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6118): Loading module APK com.google.android.play.games
,D/AndroidRuntime( 7961): Shutting down VM
,I/LocationSettingsChecker( 6118): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6118): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6118): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1715): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1715): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6118): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6118): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6118): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6118): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6118): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6118): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6118): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6118): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 6118): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6118): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6118): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6118): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6118): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8047 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@51a5578 new=com.google.android.velvet.VelvetApplication@51a5578
,I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8069 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 6118): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 6118): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6118): Module APK com.google.android.play.games already loaded
,I/Icing   ( 6118): doRemovePackageData com.test.thalitest
,E/BaseAppContext( 6118): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 6118): Using Auth Proxy for data requests.
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8106 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8047): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BaseAppContext( 6118): Using Auth Proxy for data requests.
W/BaseAppContext( 6118): Using Auth Proxy for data requests.
,I/ActivityManager(  881): Killing 7865:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  881): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6118): CM callback handler got msg 524290
,E/SQLiteLog( 8047): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7865/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=8127 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/art     (  327): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.325ms

```
