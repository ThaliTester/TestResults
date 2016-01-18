#### Test 5615109370bee58_thali04_motorola-XT1072 Logs


```
--------- beginning of system
E/BackupManagerService(  886): Timeout restoring application @pm@
W/BackupManagerService(  886): Tried to clear data for @pm@ but not found
--------- beginning of main
W/GmsBackupTransport( 1714): Restore processing aborted, no more packages
E/BackupManagerService(  886): Failure getting next package name
E/BackupManagerService(  886): Duplicate finish
,D/AndroidRuntime( 6500): 
D/AndroidRuntime( 6500): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6500): CheckJNI is OFF
D/AndroidRuntime( 6500): Calling main entry com.android.commands.am.Am
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  886): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6518 uid=10461 gids={50461, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6500): Shutting down VM
I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 22.971ms
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.853ms
V/ActivityManager(  886): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 395us total 22.449ms
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6518): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6518): Time to load native libraries: 9 ms (timestamps 5856-5865)
I/LibraryLoader( 6518): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6518): Binding Chromium to main looper Looper (main, tid 1) {1606c197}
I/LibraryLoader( 6518): Expected native library version number "",actual native library version number ""
I/chromium( 6518): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6518): Initializing chromium process, singleProcess=true
W/art     ( 6518): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6518): ApplicationContext is null in ApplicationStatus
W/chromium( 6518): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6518): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6518): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6518): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6518): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6518): Local Branch: 
I/Adreno-EGL( 6518): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6518): Local Patches: NONE
I/Adreno-EGL( 6518): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ActivityManager(  886): Activity pause timeout for ActivityRecord{3b9a6a1c u0 com.test.thalitest/.MainActivity t6}
D/BluetoothManagerService(  886): Message: 20
D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24f63723:true
W/art     ( 6518): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6518): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6518): CordovaWebView is running on device made by: motorola
,W/art     ( 6518): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6518): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6518): Render dirty regions requested: true
,D/Atlas   ( 6518): Validating map...
,W/chromium( 6518): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6518): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6518): Enabling debug mode 0
,I/Keyboard.Facilitator( 1421): onFinishInput()
,I/LaunchCheckinHandler(  886): Displayed com.test.thalitest/.MainActivity,cp,ca,1069
I/ActivityManager(  886): Displayed com.test.thalitest/.MainActivity: +963ms (total +1s69ms)
,W/IInputConnectionWrapper( 6518): showStatusIcon on inactive InputConnection
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,E/Adreno-ES20( 6518): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6518): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6518): Cannot call determinedVisibility() - never saw a connection for the pid: 6518
,D/JsMessageQueue( 6518): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6518): JniHelper::setJavaVM(0xb854b310), pthread_self() = -1198671832
,D/JX-Cordova( 6518): jxcore cordova android initializing
,W/jxcore-log( 6518): Initializing JXcore engine
W/jxcore-log( 6518): JXcore engine is ready
W/jxcore-log( 6518): Starting JXcore engine
,W/.test.thalitest( 6518): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10461 path="socket:[5799]" dev="sockfs" ino=5799 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6518): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10461 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6518): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10461 path="socket:[7724]" dev="sockfs" ino=7724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6518): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10461 path="socket:[30725]" dev="sockfs" ino=30725 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6518): Platform android
W/jxcore-log( 6518): 
W/jxcore-log( 6518): Process ARCH arm
W/jxcore-log( 6518): 
,I/jxcore-log( 6518): JXcore Cordova bridge is ready!
I/jxcore-log( 6518): 
,W/jxcore-log( 6518): JXcore engine is started
,I/chromium( 6518): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6518): Toggling radios to true
I/jxcore-log( 6518): 
,D/BluetoothAdapter( 6518): enable(): BT is already enabled..!
,D/WifiService(  886): New client listening to asynchronous messages
,D/WifiService(  886): setWifiEnabled: true pid=6518, uid=10461
E/WifiService(  886): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6518): Radios toggled
I/jxcore-log( 6518): 
I/jxcore-log( 6518): My device name is: motorola-XT1072
I/jxcore-log( 6518): 
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297):  STA Disconnected !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  297): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering(  886): InitialState.processMessage what=4
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
D/Tethering(  886):  0
E/WifiStateMachine(  886): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  886): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  886): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1714): Read error: ssl=0xb88c3e20: I/O error during system call, Connection timed out
,V/NativeCrypto( 1714): SSL shutdown failed: ssl=0xb88c3e20: I/O error during system call, Broken pipe
,D/ConnectivityService(  886): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6573 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  886): connected time updated 119897
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  886): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  886): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  886): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  295): Clearing all IP addresses on wlan0
D/ConnectivityService(  886): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  886): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  886): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Disconnected - quitting
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  886): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  886): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  886): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  886): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  886): Explicit concurrent mark sweep GC freed 52997(2MB) AllocSpace objects, 3(227KB) LOS objects, 33% free, 20MB/30MB, paused 1.930ms total 157.254ms
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  297): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1416): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  297): Event received = Trying to associate with
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1416): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  886): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  886): [1,453,126,658,760 ms] noteScanEnd no scan source
,E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e76b55b sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6573): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6573): MmsConfig.loadMmsSettings
I/Babel_SMS( 6573): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6573): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6573): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6573): MmsConfig.loadFromResources
E/Babel_SMS( 6573): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6573): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
,D/TCMD    (  482): Listening for incoming client connection request
I/wpa_supplicant( 1416): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  297): Event received = Associated with c0:ff:d4
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  886): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
W/Settings(  886): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  886): ApnList is empty for checkDunConfigured()
D/Tethering(  886):  upstream interface types: 
D/Tethering(  886):  0
D/Tethering(  886):  1
D/Tethering(  886):  5
D/Tethering(  886):  7
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Tethering(  886): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1416): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  297): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/MDMCTBK (  297): Event received = CTRL-EVENT-CONNECTED - C
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  297):  STA Connected !!
E/MDMCTBK (  297): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  297): get_freq !!, resp=2412
I/MDMCTBK (  297): get_freq !!, Strip data
I/MDMCTBK (  297): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  297): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  297): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216180840
I/MDMCTBK (  297): return from set_get_from_wpa_supplicant
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  297): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  297): , reply_len: 3, ret: 0
E/MDMCTBK (  297): MdmCutbackHndler, resp=OK
E/MDMCTBK (  297): 
D/MDMCTBK (  297): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  886): Network connection established
E/WifiStateMachine(  886): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  886): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  886): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  886): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  886): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  886): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  886): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  886): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  295): Setting iface cfg
E/WifiStateMachine(  886): Start Dhcp Watchdog 2
E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/Settings( 6573): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend false
I/Babel_Crash( 6573): startup - clean
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  886): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1416): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  886): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ab079df target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2ab079df target=com.android.internal.util.StateMachine$SmHandler }
I/Babel   ( 6573): deleted: false for 0
,I/ActivityManager(  886): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6623 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6573): Unsupported mime audio/amr-wb-plus
,W/ResourcesManager( 6623): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6573): Unsupported mime video/mpeg2
,E/DHCPCD  ( 6640): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6640): version 5.5.6 starting
E/DHCPCD  ( 6640): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6640): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6640): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/VideoCapabilities( 6573): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6573): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Killing 6283:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/DHCPCD  ( 6640): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6640): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6640): wlan0: sending REQUEST (xid 0x9d46073c), next in 4.30 seconds
,W/libprocessgroup(  886): failed to open /acct/uid_10057/pid_6283/cgroup.procs: No such file or directory
,I/vclib   ( 6573): onServiceConnected
W/Babel   ( 6573): Attempted to change video mute state without an active call.
,I/ActivityManager(  886): Killing 6316:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6316/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6640): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6640): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6640): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6640): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6640): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6640): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
,D/DHCPCD  ( 6640): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,V/AlarmManager(  886): send {288f4f16, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  886): done {288f4f16, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4ms]
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  886): do suspend true
,D/WifiP2pService(  886): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  886): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  886): WifiStateMachine DHCP successful
E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  886): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  886): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  886): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  886): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  886): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  886): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  886): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  886): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  886): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  886): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  886): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  886): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  886): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  886): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,E/WifiStateMachine(  886): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 14:17:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453126660381], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453126660356]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  886): Validated
,D/ConnectivityService(  886): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  886): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  886): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  886): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  886): MasterInitialState.processMessage what=3
D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6708 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2567): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2567): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2567): [debug] > CusSM.onRadioDown
,I/MusicStore( 6708): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6708): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6708): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6708): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6708): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6708): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@274d43e3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6708): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6708): GMSCore installation verified
,I/ConfigStore( 6708): Config Database version: 1
,I/MediaRouter( 6708): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6708): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6749 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6708): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6708): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 6148:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_6148/cgroup.procs: No such file or directory
,V/Mms     ( 6749): mnc/mcc: 
V/Mms     ( 6749): tag: int value: recipientLimit - 20
V/Mms     ( 6749): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6749): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6749): tag: int value: maxSubjectLength - 80
V/Mms     ( 6749): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6749): tag: bool value: enableGroupMms - false
,V/Mms     ( 6749):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6749): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6776 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6225:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6776): Register our PhoneStateListener
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_6225/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6776): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6776): onReceive CONNECTIVITY_CHANGE networkType=1
,E/WifiStateMachine(  886): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  886): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  886): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  886): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  886): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524295
,I/ActivityManager(  886): Killing 6573:com.google.android.talk/u0a70 (adj 15): empty #7
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6518): 
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6573/cgroup.procs: No such file or directory
,I/CheckinService( 6372): Checkin interval check for package: unspecified last checkin: 1453126581717 min interval config: 0 actual interval: 81348
,I/CheckinService( 6372): Disabling old GoogleServicesFramework version
,I/CheckinService( 6372): Checking schedule, now: 1453126663089 next: 1453126611671
I/CheckinService( 6372): active receiver: enabled
,I/CheckinService( 6372): Preparing to send checkin request
,I/EventLogService( 6372): Accumulating logs since 1453126578596
,I/iu.SyncManager( 6372): SYNC; picasa accounts
,D/NetworkLogImpl( 6372): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6372): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6372): num queued entries: 0
I/iu.UploadsManager( 6372): num updated entries: 0
I/iu.SyncManager( 6372): NEXT; no task
,E/global frequency( 2567): no tags to log
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6805 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/ConnectivityService(  886): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  886): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1477): now: 195337 ,futureTime: 86475040
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86475040 Current Time: 195338
,I/NetworkMonitor( 6708): type=WIFI subType= reason=null isConnected=true
,I/art     ( 2567): Explicit concurrent mark sweep GC freed 16175(877KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.398ms total 94.618ms
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/CheckinRequestBuilder( 6372): Checkin reason type: 8 attempt count: 1
,D/WifiService(  886): New client listening to asynchronous messages
,E/ActivityThread( 6372): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  886): Explicit concurrent mark sweep GC freed 37642(1867KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.860ms total 128.613ms
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6829 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/AlarmManager(  886): send {372f03cc, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6518): 
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6518): 
,W/ResourcesManager( 6829): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 53344(2MB) AllocSpace objects, 34(1164KB) LOS objects, 39% free, 7MB/12MB, paused 891us total 44.330ms
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6518): 
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6518): 
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6518): 
,E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/jxcore-log( 6518): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6518): 
,D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 196045 ,futureTime: 9223372036854775807
D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 196046 ,futureTime: 9223372036854775807
,D/PollingManager( 2567): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2567): now: 196046 ,futureTime: 9223372036854775807
D/OtaApp  ( 2567): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2567): [debug] > PollingManagerService, now: 196048 ,futureTime: 84360385
,D/OtaApp  ( 2567): [debug] > Polling alarm set to expire at: 84360385 Current Time: 196049
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Babel_SMS( 6829): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6829): MmsConfig.loadMmsSettings
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,I/Babel_SMS( 6829): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6829): MmsConfig.loadFromDatabase
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2567): set mOutstandingReq to true.
I/ Nonce  ( 2567):  Nonce getNonce 
I/ Nonce  ( 2567):  Nonce Request 
I/ Nonce  ( 2567):  Nonce execute Request 
,D/MMApiWebService( 2567): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 3544(139KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.027ms total 33.944ms
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6857 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,E/Babel_SMS( 6829): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6829): MmsConfig.loadFromResources
,E/Babel_SMS( 6829): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6829): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6857): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6857): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/MMApiProvisionService( 2567): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2567): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2567): createDeviceIdOrLogin update_device
D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2567): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2567): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2567): [debug] > CusSM.onRadioUp
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/global frequency( 2567): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2567): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2567): publish the event [tag = DEV_ATTRIBS event name = SW]
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/art     (  886): Explicit concurrent mark sweep GC freed 5980(262KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.608ms total 127.649ms
I/OtaApp  ( 2567): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2567): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2567): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MultiDex( 6857): VM with version 2.1.0 has multidex support
I/MultiDex( 6857): install
I/MultiDex( 6857): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6857): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6829): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6829): startup - clean
,D/MMApiWebService( 2567): generating token using payload instead of using session token
,D/ Nonce  ( 2567):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/Babel   ( 6829): deleted: false for 0
,I/MMApiWSBase( 2567): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,W/ActivityThread( 6857): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6857): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f6caf68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6857): Installed default security provider GmsCore_OpenSSL
,W/VideoCapabilities( 6829): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6881 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 6857): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6857): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,W/AudioCapabilities( 6829): Unsupported mime audio/amr-wb-plus
,D/NativeLibraryUtils( 6857): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6829): Unsupported mime video/mpeg2
,D/WVCdm   (  299): Instantiating CDM.
,I/WVCdm   (  299): CdmEngine::OpenSession
I/WVCdm   (  299): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  299): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/VideoCapabilities( 6829): Unsupported profile 4 for video/mp4v-es
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  299): Service_Initialize: starts!
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
,W/VideoCapabilities( 6829): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6829): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6829): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 6518): Test app app.js loaded
I/jxcore-log( 6518): 
,W/VideoCapabilities( 6829): Unrecognized profile 2130706433 for video/avc
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6518): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6518): BLE advertisement is supported
I/jxcore-log( 6518): 
,D/QSEECOMAPI: (  299): Loaded image: APP id = 3
,D/DrmWidevineDash(  299): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
E/DrmWidevineDash(  299): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
,I/vclib   ( 6829): onServiceConnected
,W/Babel   ( 6829): Attempted to change video mute state without an active call.
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  299): hlos api version =  9
,D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  299): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: starts! SID=0xb5591960
D/DrmWidevineDash(  299): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: starts! randomData=0xb72be278, dataLength=8
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71c55d0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  299): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  299): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  299): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  299): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: starts! deviceID=0xb72e4838, idLength=0xb5491730
,I/chromium( 6518): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  299): PrepareKeyRequest: nonce=455962244
D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb728a530
D/DrmWidevineDash(  299): message_length=1591, signature=0xb721dc10, signature_length=3041466132
,I/Babel   ( 6829): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  886): Killing 6623:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10008/pid_6623/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  299): CdmEngine::CloseSession
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  299): L3 Terminate.
D/DrmWidevineDash(  299): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  299): Service_Uninitialize: starts!
D/QSEECOMAPI: (  299): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  299): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  299): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  299): OEMCrypto_Terminate: ends! returns 0
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6881): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6881): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6881): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6881): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6881): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6881):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6881):   adb logcat -s GAv4
,W/GAv4    ( 6881): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6881): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6881): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6881): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 6929): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LibraryLoader( 6881): Time to load native libraries: 2 ms (timestamps 7504-7506)
I/LibraryLoader( 6881): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6881): Binding Chromium to main looper Looper (main, tid 1) {13dec298}
,I/LibraryLoader( 6881): Expected native library version number "",actual native library version number ""
I/chromium( 6881): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6881): Initializing chromium process, singleProcess=true
W/art     ( 6881): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6881): ApplicationContext is null in ApplicationStatus
,I/ Nonce  ( 2567):  Nonce Reponse 
D/        ( 2567): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"646c772d-d874-489f-9d7f-b3b4fa574deb"}
D/MMApiWSBase( 2567): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2567):  Nonce Handle Reponse 
D/MMApiProvisionService( 2567): mOutstandingReq set to false
,W/chromium( 6881): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6881): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6881): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6881): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6881): Local Branch: 
I/Adreno-EGL( 6881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6881): Local Patches: NONE
I/Adreno-EGL( 6881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6929): dex2oat took 140.564ms (threads: 4)
,I/Adreno-EGL( 6857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6857): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6857): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6857): Local Branch: 
I/Adreno-EGL( 6857): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6857): Local Patches: NONE
I/Adreno-EGL( 6857): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     ( 2567): Explicit concurrent mark sweep GC freed 15166(901KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 992us total 58.746ms
,W/AudioManagerAndroid( 6881): Requires BLUETOOTH permission
,I/NSApplication( 6881): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6954 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6708:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/MMApiProvisionService( 2567):  pTime 1453032756427 sExp 172742 cTime 1453126665688 tTime 1453205498427
D/MMApiProvisionService( 2567):  No login Required 
,I/Adreno-EGL( 6857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6857): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6857): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6857): Local Branch: 
I/Adreno-EGL( 6857): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6857): Local Patches: NONE
I/Adreno-EGL( 6857): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_6708/cgroup.procs: No such file or directory
,I/WVCdm   (  299): CdmEngine::OpenSession
I/WVCdm   (  299): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  299): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  299): Service_Initialize: starts!
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
,D/QSEECOMAPI: (  299): Loaded image: APP id = 3
,D/DrmWidevineDash(  299): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
,E/DrmWidevineDash(  299): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  299): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: starts! SID=0xbea654e0
D/DrmWidevineDash(  299): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  299): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_GetRandom: starts! randomData=0xb72be5a0, dataLength=8
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71c55d0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  299): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  299): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  299): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  299): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: starts! deviceID=0xb72e4878, idLength=0xb13a7730
,D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  299): PrepareKeyRequest: nonce=3095413680
D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb728a530
D/DrmWidevineDash(  299): message_length=1626, signature=0xb721dc10, signature_length=2973398804
,W/DataUsage( 2567): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6979 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6749:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  318): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.802ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 24.891ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.028ms
,D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  299): CdmEngine::CloseSession
,D/DrmWidevineDash(  299): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  299): L3 Terminate.
D/DrmWidevineDash(  299): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  299): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  299): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  299): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  299): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_6749/cgroup.procs: No such file or directory
,W/ResourcesManager( 6979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6857): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6857): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6857): Local Branch: 
I/Adreno-EGL( 6857): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6857): Local Patches: NONE
I/Adreno-EGL( 6857): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6857): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6857): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6857): Local Branch: 
I/Adreno-EGL( 6857): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6857): Local Patches: NONE
I/Adreno-EGL( 6857): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7010 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6372): Classify the device as Phone.
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7039 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6805:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7010): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 6776:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_6805/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_6776/cgroup.procs: No such file or directory
,I/CheckinTask( 6372): Sending checkin request (9449 bytes)
,I/MusicStore( 7039): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7039): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7039): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7039): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@274d43e3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7039): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7039): GMSCore installation verified
,I/ConfigStore( 7039): Config Database version: 1
,I/MediaRouter( 7039): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7039): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7039): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7039): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7074 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6344): Explicit concurrent mark sweep GC freed 1512(65KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 496us total 50.788ms
,I/GHttpClientFactory( 7039): Using our fixed implementation of GMSCore's GoogleHttpClient
,V/Mms     ( 7074): mnc/mcc: 
,V/Mms     ( 7074): tag: int value: recipientLimit - 20
V/Mms     ( 7074): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7074): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7074): tag: int value: maxSubjectLength - 80
V/Mms     ( 7074): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7074): tag: bool value: enableGroupMms - false
,I/GoogleURLConnFactory( 7039): Using platform SSLCertificateSocketFactory
V/Mms     ( 7074):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  886): Explicit concurrent mark sweep GC freed 9602(460KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.671ms total 111.617ms
,I/ActivityManager(  886): Killing 6829:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 6372): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_6829/cgroup.procs: No such file or directory
,E/ActivityThread( 6372): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7074): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7104 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7104): Register our PhoneStateListener
,I/ActivityManager(  886): Killing 6881:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/MobileConnectivityChangeReceiver( 7104): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7104): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  886): Killing 6954:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinRequestBuilder( 6372): Classify the device as Phone.
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_6954/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_6881/cgroup.procs: No such file or directory
,I/CheckinService( 6372): Checkin interval check for package: unspecified last checkin: 1453126581717 min interval config: 0 actual interval: 86119
,I/CheckinTask( 6372): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7125 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 6372): Checking schedule, now: 1453126667913 next: 1453727804851
,I/CheckinService( 6372): active receiver: disabled
,I/CheckinService( 6372): Checking schedule, now: 1453126667938 next: 1453727804851
I/CheckinService( 6372): active receiver: disabled
,D/CheckinService( 6372): Recording last checkin time for package unspecified as 1453126667942
,I/ActivityManager(  886): Killing 6979:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  886): Killing 7010:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_6979/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7010/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7143 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7039:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_7039/cgroup.procs: No such file or directory
,W/ResourcesManager( 7143): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7143): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7143): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7143): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7143): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7143): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7143): MmsConfig.loadFromResources
,E/Babel_SMS( 7143): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7143): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7143): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7143): startup - clean
,I/Babel   ( 7143): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7177 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7143): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7143): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7143): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7143): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7143): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7143): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7143): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7143): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7143): onServiceConnected
W/Babel   ( 7143): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7177): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7177): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7177):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7177):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7177): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7177): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7177): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7177): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7177): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7143): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7177): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  886): Killing 7074:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_7074/cgroup.procs: No such file or directory
,I/WebViewFactory( 7177): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7177): Time to load native libraries: 1 ms (timestamps 1397-1398)
,I/LibraryLoader( 7177): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7177): Binding Chromium to main looper Looper (main, tid 1) {13dec298}
,I/LibraryLoader( 7177): Expected native library version number "",actual native library version number ""
,I/chromium( 7177): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7177): Initializing chromium process, singleProcess=true
,W/art     ( 7177): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7177): ApplicationContext is null in ApplicationStatus
,W/chromium( 7177): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7177): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7177): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7177): Local Branch: 
I/Adreno-EGL( 7177): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7177): Local Patches: NONE
I/Adreno-EGL( 7177): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7177): Requires BLUETOOTH permission
,I/NSApplication( 7177): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7253 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7104:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7104/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7272 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 7125:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7125/cgroup.procs: No such file or directory
,W/ResourcesManager( 7272): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7295 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7177:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/art     ( 7272): Suspending all threads took: 5.381ms
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310425, SEQNUM=4457, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-429, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ContactLocale( 7295): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 7143:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7177/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7143/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/HeadsetStateMachine( 2460): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2460): Disconnected process message: 10, size: 0
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
,D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
I/PushService( 2567): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  886): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7333 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.549ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 19.776ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.442ms
,I/MusicStore( 7333): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7333): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7333): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7333): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7333): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7333): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7333): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7333): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7333): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@274d43e3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7333): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7333): GMSCore installation verified
,I/ConfigStore( 7333): Config Database version: 1
,I/MediaRouter( 7333): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7333): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7333): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7333): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7365 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7333): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7333): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  886): Killing 7253:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7253/cgroup.procs: No such file or directory
,I/art     (  886): Explicit concurrent mark sweep GC freed 12489(648KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.944ms total 140.893ms
,V/Mms     ( 7365): mnc/mcc: 
V/Mms     ( 7365): tag: int value: recipientLimit - 20
V/Mms     ( 7365): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7365): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7365): tag: int value: maxSubjectLength - 80
V/Mms     ( 7365): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7365): tag: bool value: enableGroupMms - false
,V/Mms     ( 7365):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7365): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7401 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7272:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7272/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7401): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7401): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7401): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6372): Checkin interval check for package: unspecified last checkin: 1453126667942 min interval config: 0 actual interval: 3431
,I/CheckinService( 6372): Checkin interval check for package: unspecified last checkin: 1453126667942 min interval config: 0 actual interval: 3437
,I/CheckinService( 6372): Checking schedule, now: 1453126671385 next: 1453126697851
I/CheckinService( 6372): active receiver: disabled
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7424 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6372): Checking schedule, now: 1453126671442 next: 1453126697851
I/CheckinService( 6372): active receiver: disabled
,I/ActivityManager(  886): Killing 7295:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7295/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7444 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7333:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10080/pid_7333/cgroup.procs: No such file or directory
,W/ResourcesManager( 7444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7444): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7444): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7444): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7444): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7444): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7444): MmsConfig.loadFromResources
,E/Babel_SMS( 7444): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7444): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7444): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7444): startup - clean
,I/Babel   ( 7444): deleted: false for 0
,I/ActivityManager(  886): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7475 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7444): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7444): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7444): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7444): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7444): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7444): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7444): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7444): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7444): onServiceConnected
,W/Babel   ( 7444): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7475): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 7444): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7475): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7475): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7475):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7475):   adb logcat -s GAv4
I/ActivityManager(  886): Killing 7365:com.android.mms/u0a23 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7475): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7475): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  886): failed to open /acct/uid_10023/pid_7365/cgroup.procs: No such file or directory
,W/GAv4    ( 7475): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7475): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7475): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7475): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7475): Time to load native libraries: 3 ms (timestamps 4814-4817)
I/LibraryLoader( 7475): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7475): Binding Chromium to main looper Looper (main, tid 1) {13dec298}
,I/LibraryLoader( 7475): Expected native library version number "",actual native library version number ""
I/chromium( 7475): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7475): Initializing chromium process, singleProcess=true
,W/art     ( 7475): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7475): ApplicationContext is null in ApplicationStatus
,W/chromium( 7475): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7475): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7475): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7475): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7475): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7475): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7475): Local Branch: 
I/Adreno-EGL( 7475): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7475): Local Patches: NONE
I/Adreno-EGL( 7475): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7475): Requires BLUETOOTH permission
,I/NSApplication( 7475): Starting up...
,I/ActivityManager(  886): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7546 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 6857:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_6857/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7565 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7401:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7401/cgroup.procs: No such file or directory
,W/ResourcesManager( 7565): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@34b13bab
,I/GCoreNlp( 1714): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1564): Deferring update until onResume
,I/ActivityManager(  886): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7591 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7444:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7591): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Killing 7424:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7444/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2567): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7424/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2567): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2567): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2567): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2567): onServiceConnected()
D/GetNotificationsWS( 2567): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2567): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2567): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  886): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7616 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  886): done {372f03cc, *walarm*:com.google.android.intent.action.SEND_IDLE} [10353ms]
,D/OtaApp  ( 2567): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2567): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2567): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  886): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/WearableService( 1714): callingUid 10016, callindPid: 1714
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 6372): Restart initialization of location
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
E/MDM     ( 1714): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,W/GCoreFlp( 1714): No location to return for getLastLocation()
,W/FusedLocationProvider( 1714): location=null
,I/Keyboard.Facilitator( 1421): onFinishInput()
,W/IInputConnectionWrapper( 6518): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  886): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,187
,I/art     (  886): Explicit concurrent mark sweep GC freed 18784(937KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.636ms total 120.273ms
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7656 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7656): Register our PhoneStateListener
,V/SetupWizard( 7656): Connected to Gservices successfully
,I/ActivityManager(  886): Killing 7475:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_7475/cgroup.procs: No such file or directory
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7682 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 23.096ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.224ms
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.795ms
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7709 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7726 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7546:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  886): Killing 7565:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10052/pid_7546/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7565/cgroup.procs: No such file or directory
,W/ResourcesManager( 7726): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7726): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7726): MmsConfig.loadMmsSettings
I/Babel_SMS( 7726): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7726): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7726): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7726): MmsConfig.loadFromResources
,E/Babel_SMS( 7726): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7726): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7726): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7726): startup - clean
,I/Babel   ( 7726): deleted: false for 0
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7759 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7759): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7759): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7759): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7759): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7726): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7726): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7726): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 6372): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1564): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d3fb969 new=com.google.android.velvet.VelvetApplication@d3fb969
,I/UpdateIcingCorporaServi( 7682): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6372): Null package name or gms related package.  Ignoreing.
,I/VideoCapabilities( 7726): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7726): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7726): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7726): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7788 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7726): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 6372): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7788): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7726): onServiceConnected
W/Babel   ( 7726): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7682): UpdateCorporaTask done [took 223 ms] updated apps [took 223 ms] 
,I/ActivityManager(  886): Killing 7656:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/ResourcesManager( 7726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7656/cgroup.procs: No such file or directory
,V/JNIHelp ( 7726): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7726): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7726): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7825 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7616:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10088/pid_7616/cgroup.procs: No such file or directory
,D/Finsky  ( 7825): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7825): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7825): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7825): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7825): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7825): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7825): Skipping gmscore version check
,D/Finsky  ( 7825): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7825): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  886): Killing 7709:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_7709/cgroup.procs: No such file or directory
,I/Icing   ( 6372): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6372): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6372): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/TaskPersister(  886): removeObsoleteFile: deleting file=5_task.xml
,I/ActivityManager(  886): Killing 7759:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_7759/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7682:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7682/cgroup.procs: No such file or directory
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/CheckinService( 6372): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311228, SEQNUM=4482, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-480, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2460): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2460): Disconnected process message: 10, size: 0
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1714): disconnect managed GoogleApiClient
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  886): send {dc44ad1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {c588e1f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  886): send {7fc256c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  886): send {26ab828a, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  886): done {c588e1f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [24ms]
,V/AlarmManager(  886): done {dc44ad1, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  886): done {7fc256c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [54ms]
,V/AlarmManager(  886): done {26ab828a, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [78ms]
,I/CheckinService( 6372): Checkin interval check for package: unspecified last checkin: 1453126667942 min interval config: 0 actual interval: 47309
,I/EventLogService( 6372): Aggregate from 1453126663367 (log), 1453124876485 (data)
,I/CheckinService( 6372): Checking schedule, now: 1453126715259 next: 1453126697851
I/CheckinService( 6372): active receiver: enabled
,I/CheckinService( 6372): Preparing to send checkin request
,I/EventLogService( 6372): Accumulating logs since 1453126715264
,I/CheckinRequestBuilder( 6372): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6372): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  886): Explicit concurrent mark sweep GC freed 15142(782KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.566ms total 112.022ms
,I/ActivityManager(  886): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7901 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7901): VM with version 2.1.0 has multidex support
I/MultiDex( 7901): install
,I/MultiDex( 7901): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7901): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7901): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f6caf68: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7901): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1714): callingUid 10016, callindPid: 1714
,D/LocationInitializer( 6372): Restart initialization of location
,E/MDM     ( 1714): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1714): No location to return for getLastLocation()
W/FusedLocationProvider( 1714): location=null
,I/art     ( 7901): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7901): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7901): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  299): Instantiating CDM.
,I/WVCdm   (  299): CdmEngine::OpenSession
I/WVCdm   (  299): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  299): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  299): Service_Initialize: starts!
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
,D/QSEECOMAPI: (  299): Loaded image: APP id = 3
,D/DrmWidevineDash(  299): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
E/DrmWidevineDash(  299): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  299): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: starts! SID=0xb13a7960
,D/DrmWidevineDash(  299): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  299): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: starts! randomData=0xb72be988, dataLength=8
,D/DrmWidevineDash(  299): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71c55d0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  299): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  299): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  299): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  299): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: starts! deviceID=0xb72e4858, idLength=0xbea652b0
,D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  299): PrepareKeyRequest: nonce=1707458700
D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb728a530
D/DrmWidevineDash(  299): message_length=1591, signature=0xb721dc10, signature_length=3198571156
,D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  299): CdmEngine::CloseSession
,D/DrmWidevineDash(  299): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  299): L3 Terminate.
D/DrmWidevineDash(  299): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  299): Service_Uninitialize: starts!
D/QSEECOMAPI: (  299): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  299): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  299): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7935): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7935): dex2oat took 74.794ms (threads: 4)
,I/Adreno-EGL( 7901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7901): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7901): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7901): Local Branch: 
I/Adreno-EGL( 7901): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7901): Local Patches: NONE
I/Adreno-EGL( 7901): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7901): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7901): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7901): Local Branch: 
I/Adreno-EGL( 7901): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7901): Local Patches: NONE
I/Adreno-EGL( 7901): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  299): CdmEngine::OpenSession
I/WVCdm   (  299): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  299): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  299): Service_Initialize: starts!
,D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
E/QSEECOMAPI: (  299): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  299): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  299): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  299): App is not loaded in QSEE
,D/QSEECOMAPI: (  299): Loaded image: APP id = 3
,D/DrmWidevineDash(  299): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
E/DrmWidevineDash(  299): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fb7000
,D/DrmWidevineDash(  299): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  299): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  299): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: starts! SID=0xb13a7960
D/DrmWidevineDash(  299): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  299): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: starts! randomData=0xb72c10b0, dataLength=8
D/DrmWidevineDash(  299): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb71c55d0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  299): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  299): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  299): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  299): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  299): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: starts! deviceID=0xb72e4878, idLength=0xb5591730
,D/DrmWidevineDash(  299): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  299): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  299): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  299): hlos api version =  9
D/DrmWidevineDash(  299): tz api version =  8
D/DrmWidevineDash(  299): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  299): PrepareKeyRequest: nonce=337097900
D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb728a530
D/DrmWidevineDash(  299): message_length=1626, signature=0xb721dc10, signature_length=3042514708
,D/DrmWidevineDash(  299): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  299): CdmEngine::CloseSession
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  299): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  299): L3 Terminate.
D/DrmWidevineDash(  299): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  299): Service_Uninitialize: starts!
D/QSEECOMAPI: (  299): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  299): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  299): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  299): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7901): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7901): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7901): Local Branch: 
I/Adreno-EGL( 7901): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7901): Local Patches: NONE
I/Adreno-EGL( 7901): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7901): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7901): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7901): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7901): Local Branch: 
I/Adreno-EGL( 7901): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7901): Local Patches: NONE
I/Adreno-EGL( 7901): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6372): Classify the device as Phone.
,I/CheckinTask( 6372): Sending checkin request (9452 bytes)
,I/CheckinRequestBuilder( 6372): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6372): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6372): Classify the device as Phone.
,I/CheckinTask( 6372): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6372): Checking schedule, now: 1453126719404 next: 1453727856398
I/CheckinService( 6372): active receiver: disabled
,D/CheckinService( 6372): Recording last checkin time for package unspecified as 1453126719420
,I/ActivityManager(  886): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7965 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7965): Register our PhoneStateListener
,V/SetupWizard( 7965): Connected to Gservices successfully
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  886): Killing 7788:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  886): Killing 7591:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_7788/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10007/pid_7591/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7987 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1cc8fa8e
,I/GCoreNlp( 1714): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1564): Deferring update until onResume
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8020 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8039 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7825:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10032/pid_7825/cgroup.procs: No such file or directory
,W/ResourcesManager( 7726): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7726): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8039): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8062 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 7965:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  318): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.997ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 19.907ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.862ms
,W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_7965/cgroup.procs: No such file or directory
,W/asset   ( 8062): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8062): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8062): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8062): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6372): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6372): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1564): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d3fb969 new=com.google.android.velvet.VelvetApplication@d3fb969
I/UpdateIcingCorporaServi( 7987): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 6372): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  886): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8089 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8089): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7987): UpdateCorporaTask done [took 129 ms] updated apps [took 129 ms] 
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8118 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  886): Explicit concurrent mark sweep GC freed 17455(908KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.490ms total 127.932ms
,I/ActivityManager(  886): Killing 7901:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_7901/cgroup.procs: No such file or directory
,D/Finsky  ( 8118): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8118): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8118): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8118): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8118): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8118): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8118): Skipping gmscore version check
,I/ActivityManager(  886): Killing 8020:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10019/pid_8020/cgroup.procs: No such file or directory
,D/Finsky  ( 8118): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8118): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6372): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6372): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  886): Killing 8062:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10027/pid_8062/cgroup.procs: No such file or directory
,I/ActivityManager(  886): Killing 7726:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10070/pid_7726/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1421): run()
,I/Keyboard.Facilitator( 1421): flushDynamicLanguageModels()
,I/ConfigService( 1714): onCreate
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 97605(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 15MB/25MB, paused 1.071ms total 125.740ms
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1714): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311461, SEQNUM=4502, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-527, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2460): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6518): --= Surplus to requirements =--
I/jxcore-log( 6518): 
I/jxcore-log( 6518): ****TEST TOOK:  ms ****
I/jxcore-log( 6518): 
I/jxcore-log( 6518): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6518): 
,D/AndroidRuntime( 8185): 
D/AndroidRuntime( 8185): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8185): CheckJNI is OFF
,D/AndroidRuntime( 8185): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  886): Force stopping com.test.thalitest appid=10461 user=-1: uninstall pkg
,I/ActivityManager(  886): Killing 6518:com.test.thalitest/u0a461 (adj 9): stop com.test.thalitest
,I/WindowState(  886): WIN DEATH: Window{8732f13 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  886): Client connection lost with reason: 4
,W/PackageSettings(  886): Skipping PackageSetting{2e57203c com.example.hello/10440} due to missing metadata
,I/ActivityManager(  886):   Force finishing activity ActivityRecord{3b9a6a1c u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  886): Spurious death for ProcessRecord{3b362f77 6518:com.test.thalitest/u0a461}, curProc for 6518: null
,I/ActivityManager(  886): Force stopping com.test.thalitest appid=10461 user=0: pkg removed
I/ActivityManager(  886):   Force finishing activity ActivityRecord{3b9a6a1c u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  886): Duplicate finish request for ActivityRecord{3b9a6a1c u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 3024): Explicit concurrent mark sweep GC freed 10052(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 7MB/12MB, paused 873us total 39.368ms
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1421): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1421): run()
,D/VoicemailCleanupService( 8039): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8216 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1564): Explicit concurrent mark sweep GC freed 5055(311KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 509us total 131.994ms
,I/art     (  886): Explicit concurrent mark sweep GC freed 9493(712KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.465ms total 139.162ms
,I/art     (  886): WaitForGcToComplete blocked for 61.814ms for cause Explicit
,I/Decoder ( 1421): createOrResetDecoder
,I/ConfigService( 1714): onCreate
,W/asset   ( 8216): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8216): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8216): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8216): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): run()
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1421): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1421): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1421): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1421): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1421): run()
I/StatsUtilsManager( 1421): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1421): shouldRecordStats() = Too Soon
,I/ActivityManager(  886): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8240 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  886): removeObsoleteFile: deleting file=6_task.xml
,I/art     (  886): Explicit concurrent mark sweep GC freed 5087(278KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.923ms total 195.920ms
,I/ActivityManager(  886): Killing 7987:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/AndroidRuntime( 8185): Shutting down VM
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_7987/cgroup.procs: No such file or directory
,I/Launcher( 1564): Deferring update until onResume
,W/ContextImpl( 8240): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6372): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 6372): Reading stored module config
,D/AccountUtils( 6372): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6372): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6372): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 6372): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6372): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6372): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1714): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1714): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8270 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 6372): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6372): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6372): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6372): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6372): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6372): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6372): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6372): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6372): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6372): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6372): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6372): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,W/Launcher( 1564): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d3fb969 new=com.google.android.velvet.VelvetApplication@d3fb969
,D/gH_CompatibleDatabase( 6372): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  886): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8292 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 6372): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6372): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 6372): Using Auth Proxy for data requests.
,I/Icing   ( 6372): doRemovePackageData com.test.thalitest
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8318 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,E/SQLiteLog( 6372): (778) statement aborts at 16: [INSERT OR REPLACE  INTO properties(name,value) VALUES (?,?)] 
,E/SQLiteDatabase( 6372): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase( 6372): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase( 6372): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase( 6372): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase( 6372): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6372): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6372): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 6372): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 6372): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6372): Process: com.google.android.gms, PID: 6372
E/AndroidRuntime( 6372): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6372): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6372): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6372): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6372): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6372): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6372): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6372): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6372): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6372): Sending signal. PID: 6372 SIG: 9
,E/native  ( 1421): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1421): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1421): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1421): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/UpdateIcingCorporaServi( 8270): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/WifiService(  886): Client connection lost with reason: 4
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
