#### Test 549702610263d9b_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {3a82f002, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  878): done {3a82f002, *walarm*:com.google.android.intent.action.SEND_IDLE} [19ms]
V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [48ms]
--------- beginning of main
D/AndroidRuntime( 6147): 
D/AndroidRuntime( 6147): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6147): CheckJNI is OFF
D/AndroidRuntime( 6147): Calling main entry com.android.commands.am.Am
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6166 uid=10413 gids={50413, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6147): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/WebViewFactory( 6166): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6166): Time to load native libraries: 17 ms (timestamps 6604-6621)
,I/LibraryLoader( 6166): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6166): Binding Chromium to main looper Looper (main, tid 1) {cb562f8}
I/LibraryLoader( 6166): Expected native library version number "",actual native library version number ""
,I/chromium( 6166): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6166): Initializing chromium process, singleProcess=true
,W/art     ( 6166): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6166): ApplicationContext is null in ApplicationStatus
,W/chromium( 6166): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6166): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6166): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6166): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6166): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6166): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6166): Local Branch: 
I/Adreno-EGL( 6166): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6166): Local Patches: NONE
I/Adreno-EGL( 6166): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  878): Activity pause timeout for ActivityRecord{326cfd13 u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  878): Message: 20
,D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a231526:true
,W/art     ( 6166): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6166): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6166): CordovaWebView is running on device made by: motorola
,W/art     ( 6166): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6166): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6166): Render dirty regions requested: true
,D/Atlas   ( 6166): Validating map...
,W/chromium( 6166): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6166): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6166): Enabling debug mode 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1122
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +984ms (total +1s122ms)
,W/IInputConnectionWrapper( 6166): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6166): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6166): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6166): Cannot call determinedVisibility() - never saw a connection for the pid: 6166
,D/JsMessageQueue( 6166): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6166): JniHelper::setJavaVM(0xb73d0310), pthread_self() = -1216999792
,D/JX-Cordova( 6166): jxcore cordova android initializing
,W/jxcore-log( 6166): Initializing JXcore engine
W/jxcore-log( 6166): JXcore engine is ready
,W/jxcore-log( 6166): Starting JXcore engine
,W/.test.thalitest( 6166): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10413 path="socket:[9383]" dev="sockfs" ino=9383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6166): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10413 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6166): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10413 path="socket:[6709]" dev="sockfs" ino=6709 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6166): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10413 path="socket:[29002]" dev="sockfs" ino=29002 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6166): Platform android
W/jxcore-log( 6166): 
W/jxcore-log( 6166): Process ARCH arm
W/jxcore-log( 6166): 
,E/global frequency( 2693): no tags to log
,D/Checkin ( 2693): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  878): Explicit concurrent mark sweep GC freed 41856(2038KB) AllocSpace objects, 3(235KB) LOS objects, 33% free, 20MB/30MB, paused 1.897ms total 122.380ms
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2693): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 53956(2MB) AllocSpace objects, 34(1223KB) LOS objects, 39% free, 7MB/12MB, paused 744us total 41.927ms
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2693): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2693): Explicit concurrent mark sweep GC freed 19084(1104KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 1.035ms total 65.030ms
,D/BSUtils ( 2693): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2693): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2693): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2693): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2693): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2693): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2693): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2693): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2693): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2693): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2693): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/jxcore-log( 6166): JXcore Cordova bridge is ready!
I/jxcore-log( 6166): 
,W/jxcore-log( 6166): JXcore engine is started
I/chromium( 6166): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6166): Toggling radios to true
I/jxcore-log( 6166): 
,D/BluetoothAdapter( 6166): enable(): BT is already enabled..!
,D/WifiService(  878): New client listening to asynchronous messages
,D/WifiService(  878): setWifiEnabled: true pid=6166, uid=10413
E/WifiService(  878): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6166): Radios toggled
I/jxcore-log( 6166): 
,D/TCMD    (  509): NL - Read 1004 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,D/TCMD    (  509): NL - Read 68 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 68 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering(  878): InitialState.processMessage what=4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  878): WifiStateMachine: Leaving Connected state
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  1
D/Tethering(  878):  5
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  878): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  878):  7
D/Tethering(  878):  0
D/Tethering(  878): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  509): NL - Read 60 bytes from update socket.
D/TCMD    (  509): NL - ignore NL message, type = 21
D/TCMD    (  509): Listening for incoming client connection request
,V/NativeCrypto( 1736): Read error: ssl=0xb75f30f8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xb75f30f8: I/O error during system call, Broken pipe
,D/ConnectivityService(  878): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6236 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  878): connected time updated 159587
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  878): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): ConnectModeState: Network connection lost 
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
E/WifiStateMachine(  878): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  878): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=false, hasIPv4Address=true
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Disconnected - quitting
D/CSLegacyTypeTracker(  878): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  878): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1527): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1527): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1527): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1527): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1527): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1527): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  878): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  878): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  878): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6236): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6236): MmsConfig.loadMmsSettings
I/Babel_SMS( 6236): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6236): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6236): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6236): MmsConfig.loadFromResources
,E/Babel_SMS( 6236): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6236): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6236): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6236): startup - clean
,I/Babel   ( 6236): deleted: false for 0
,D/TCMD    (  509): NL - Read 56 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1433): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1433): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/WifiMonitor(  878): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  878): [1,452,015,254,521 ms] noteScanEnd no scan source
,E/WifiStateMachine(  878): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@4d8842c sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  878): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6275 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.545ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.206ms
,D/TCMD    (  509): NL - Read 312 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 192 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 68 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 1004 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.134ms
D/TCMD    (  509): NL - Read 80 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 80 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/TCMD    (  509): NL - Read 68 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,I/wpa_supplicant( 1433): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  878): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  878): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  878): ApnList is empty for checkDunConfigured()
D/Tethering(  878):  upstream interface types: 
D/Tethering(  878):  0
D/Tethering(  878):  1
D/Tethering(  878):  5
D/Tethering(  878):  7
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1433): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  509): NL - Read 1004 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2412
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191707392
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  878): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  878): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  878): Network connection established
E/WifiStateMachine(  878): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
W/ResourcesManager( 6275): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  878): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  878): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  878): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  878): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  878): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  878): Start Dhcp Watchdog 2
,W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/AudioCapabilities( 6236): Unsupported mime audio/amr-wb-plus
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend false
,W/VideoCapabilities( 6236): Unsupported mime video/mpeg2
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  878): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3124aaa2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3124aaa2 target=com.android.internal.util.StateMachine$SmHandler }
,I/VideoCapabilities( 6236): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  878): Killing 5916:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10057/pid_5916/cgroup.procs: No such file or directory
,I/vclib   ( 6236): onServiceConnected
W/Babel   ( 6236): Attempted to change video mute state without an active call.
,E/DHCPCD  ( 6296): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6296): version 5.5.6 starting
E/DHCPCD  ( 6296): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6296): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6296): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  878): Killing 5948:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6296): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6296): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6296): wlan0: sending REQUEST (xid 0xb034f9b3), next in 3.20 seconds
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_5948/cgroup.procs: No such file or directory
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310606, SEQNUM=4413, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4337, POWER_SUPPLY_CHARGE_COUNTER=-294, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/DHCPCD  ( 6296): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6296): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6296): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6296): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  509): NL - Read 60 bytes from update socket.
D/DHCPCD  ( 6296): wlan0: adding default route via 192.168.1.1
,D/TCMD    (  509): NL - ignore NL message, type = 20
D/TCMD    (  509): Listening for incoming client connection request
D/DHCPCD  ( 6296): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6296): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  878): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  878): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  878): do suspend true
,D/WifiP2pService(  878): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  878): WifiStateMachine DHCP successful
E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  878): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  878): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  878): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  878): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  878): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  878): Unexpected mtu value: 0, wlan0
D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  878): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  878): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  878): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  878): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Checking http://clients3.google.com/generate_204 on "NG700"
I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878):    accepting network in place of null
D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  878): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  878): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1527): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1527): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1527): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1287): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  878): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/Checkin (  878): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 17:34:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452015256969], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452015256951]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  878): Validated
D/ConnectivityService(  878): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  878): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1527): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1287): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1527): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1287): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1527): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1527): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1287): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1287): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  878): MasterInitialState.processMessage what=3
,D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6359 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  878): MasterInitialState.processMessage what=3
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1469): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2693): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2693): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2693): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2693): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2693): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2693): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2693): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2693): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2693): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2693): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2693): [debug] > CusSM.onRadioDown
,I/MusicStore( 6359): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6359): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6359): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6359): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6359): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6359): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@706b194: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6359): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6359): GMSCore installation verified
,I/ConfigStore( 6359): Config Database version: 1
,I/MediaRouter( 6359): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6359): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6359): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  878): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/art     (  878): Explicit concurrent mark sweep GC freed 44985(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.050ms total 128.473ms
,I/NetworkMonitor( 6359): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6393 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6359): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6359): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 5773:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_5773/cgroup.procs: No such file or directory
,V/Mms     ( 6393): mnc/mcc: 
V/Mms     ( 6393): tag: int value: recipientLimit - 20
V/Mms     ( 6393): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6393): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6393): tag: int value: maxSubjectLength - 80
V/Mms     ( 6393): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6393): tag: bool value: enableGroupMms - false
V/Mms     ( 6393):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6421 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 5858:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6421): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_5858/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6421): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6421): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 6236:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6236/cgroup.procs: No such file or directory
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015165257 min interval config: 0 actual interval: 93557
,I/CheckinService( 6004): Disabling old GoogleServicesFramework version
,I/CheckinService( 6004): Checking schedule, now: 1452015258844 next: 1452015195236
I/CheckinService( 6004): active receiver: enabled
,I/iu.SyncManager( 6004): SYNC; picasa accounts
,D/NetworkLogImpl( 6004): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6004): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/CheckinService( 6004): Preparing to send checkin request
,I/EventLogService( 6004): Accumulating logs since 1452015162309
,I/iu.UploadsManager( 6004): num queued entries: 0
I/iu.UploadsManager( 6004): num updated entries: 0
I/iu.SyncManager( 6004): NEXT; no task
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6449 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6004): Checkin reason type: 8 attempt count: 1
D/WifiService(  878): New client listening to asynchronous messages
E/ActivityThread( 6004): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6476 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6493 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6493): VM with version 2.1.0 has multidex support
I/MultiDex( 6493): install
I/MultiDex( 6493): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6493): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6493): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37d954a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6493): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6476): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6476): MmsConfig.loadMmsSettings
I/Babel_SMS( 6476): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6476): MmsConfig.loadFromDatabase
,I/art     ( 6493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6476): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6476): MmsConfig.loadFromResources
,E/Babel_SMS( 6476): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6476): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ConnectivityService(  878): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2693): now: 206891 ,futureTime: 9223372036854775807
D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2693): now: 206892 ,futureTime: 9223372036854775807
D/PollingManager( 2693): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2693): now: 206892 ,futureTime: 9223372036854775807
D/OtaApp  ( 2693): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  878): MasterInitialState.processMessage what=3
D/Central_PollingManager( 1469): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1469): now: 206902 ,futureTime: 86479774
D/Central_PollingManager( 1469): Polling alarm set to expire at: 86479774 Current Time: 206903
D/OtaApp  ( 2693): [debug] > PollingManagerService, now: 206903 ,futureTime: 81612263
D/OtaApp  ( 2693): [debug] > Polling alarm set to expire at: 81612263 Current Time: 206904
D/OtaApp  ( 2693): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2693): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2693): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2693): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2693): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2693): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2693): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2693): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2693): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2693): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/NetworkMonitor( 6359): type=WIFI subType= reason=null isConnected=true
,D/NativeLibraryUtils( 6493): Install completed successfully. count=14 extracted=0
,D/MMApiProvisionService( 2693): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2693): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2693): createDeviceIdOrLogin update_device
,D/Checkin ( 2693): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2693): Not proxy app, so login/provision not allowed
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
D/MMApiProvisionService( 2693): isDeviceProvisioned: deviceId = 2072049230914535424
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/CCE     ( 2693): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2693): createDeviceIdOrLogin update_device
,D/Checkin ( 2693): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/MMApiProvisionService( 2693): isDeviceProvisioned: deviceId = 2072049230914535424
D/MMApiProvisionService( 2693): set mOutstandingReq to true.
I/ Nonce  ( 2693):  Nonce getNonce 
I/ Nonce  ( 2693):  Nonce Request 
I/ Nonce  ( 2693):  Nonce execute Request 
,D/MMApiWebService( 2693): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,W/Settings( 6476): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,D/MMApiProvisionService( 2693): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2693): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2693): createDeviceIdOrLogin update_device
,D/Checkin ( 2693): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/MMApiProvisionService( 2693): Not proxy app, so login/provision not allowed
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,I/Babel_Crash( 6476): startup - clean
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55b9960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8101e10, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb814a1c8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8216770, idLength=0xb13cf730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2231302039
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81caed8
D/DrmWidevineDash(  295): message_length=1591, signature=0xb80e3ba8, signature_length=2973562644
,I/Babel   ( 6476): deleted: false for 0
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 3970(172KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 747us total 142.083ms
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/art     (  878): Explicit concurrent mark sweep GC freed 11132(539KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.040ms total 124.986ms
,D/MMApiWebService( 2693): generating token using payload instead of using session token
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6536 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 6535): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/WifiStateMachine(  878): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  878): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  878): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  878): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  878): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1287): CM callback handler got msg 524295
D/ Nonce  ( 2693):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2693): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2693): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 6535): dex2oat took 85.971ms (threads: 4)
W/VideoCapabilities( 6476): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6476): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6476): Unsupported mime video/mpeg2
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6493): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6493): Local Branch: 
I/Adreno-EGL( 6493): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6493): Local Patches: NONE
I/Adreno-EGL( 6493): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/VideoCapabilities( 6476): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6476): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6476): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6476): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6476): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6476): onServiceConnected
W/Babel   ( 6476): Attempted to change video mute state without an active call.
,I/Babel   ( 6476): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 6275:com.motorola.context/u0a8 (adj 15): empty #7
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6493): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6493): Local Branch: 
I/Adreno-EGL( 6493): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6493): Local Patches: NONE
I/Adreno-EGL( 6493): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbec5c4e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8149dd8, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8149200, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb82167b0, idLength=0xb54b9730
,W/libprocessgroup(  878): failed to open /acct/uid_10008/pid_6275/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2800414461
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb80e3568
D/DrmWidevineDash(  295): message_length=1626, signature=0xb811ea88, signature_length=3041629972
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6536): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6536): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6536):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6536):   adb logcat -s GAv4
,W/GAv4    ( 6536): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6536): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6536): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/WebViewFactory( 6536): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6536): Time to load native libraries: 1 ms (timestamps 8415-8416)
I/LibraryLoader( 6536): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6536): Binding Chromium to main looper Looper (main, tid 1) {1deafc2a}
I/LibraryLoader( 6536): Expected native library version number "",actual native library version number ""
I/chromium( 6536): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6536): Initializing chromium process, singleProcess=true
W/art     ( 6536): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6536): ApplicationContext is null in ApplicationStatus
,W/chromium( 6536): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6536): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6536): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6536): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6536): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6536): Local Branch: 
I/Adreno-EGL( 6536): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6536): Local Patches: NONE
I/Adreno-EGL( 6536): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6536): Requires BLUETOOTH permission
,I/NSApplication( 6536): Starting up...
,I/ Nonce  ( 2693):  Nonce Reponse 
D/        ( 2693): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"2e30d1c8-3f53-41b6-b413-4c77cf1a3a9a"}
D/MMApiWSBase( 2693): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2693):  Nonce Handle Reponse 
D/MMApiProvisionService( 2693): mOutstandingReq set to false
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6614 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 6359:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6493): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6493): Local Branch: 
I/Adreno-EGL( 6493): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6493): Local Patches: NONE
I/Adreno-EGL( 6493): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/MMApiProvisionService( 2693):  pTime 1451923699777 sExp 172742 cTime 1452015261677 tTime 1452096441777
D/MMApiProvisionService( 2693):  No login Required 
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6493): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6493): Local Branch: 
I/Adreno-EGL( 6493): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6493): Local Patches: NONE
I/Adreno-EGL( 6493): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_6359/cgroup.procs: No such file or directory
,V/AlarmManager(  878): send {3fe7819a, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/CheckinRequestBuilder( 6004): Classify the device as Phone.
,I/CheckinTask( 6004): Sending checkin request (9514 bytes)
,W/DataUsage( 2693): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2693): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6638 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6393:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_6393/cgroup.procs: No such file or directory
,W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6004): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6004): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5976): Explicit concurrent mark sweep GC freed 1528(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 6.459ms total 30.205ms
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6665 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6004): Classify the device as Phone.
,W/art     ( 6638): Suspending all threads took: 5.188ms
I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6688 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6449:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.631ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 19.565ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.208ms
,I/ContactLocale( 6665): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 6421:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_6449/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_6421/cgroup.procs: No such file or directory
,I/CheckinTask( 6004): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6004): Checking schedule, now: 1452015263043 next: 1452616400031
I/CheckinService( 6004): active receiver: disabled
,D/CheckinService( 6004): Recording last checkin time for package unspecified as 1452015263063
,I/ActivityManager(  878): Killing 6536:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/MusicStore( 6688): Database version: 120
,E/libprocessgroup(  878): failed to kill 1 processes for processgroup 6536
I/ActivityManager(  878): Killing 6476:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6476/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6688): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6688): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6688): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6688): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6688): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6688): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6688): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6688): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@706b194: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6688): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6688): GMSCore installation verified
,I/ConfigStore( 6688): Config Database version: 1
,I/MediaRouter( 6688): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6688): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6688): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6738 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6688): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6688): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  878): Killing 6614:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_6614/cgroup.procs: No such file or directory
,I/art     (  878): Explicit concurrent mark sweep GC freed 11887(603KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.633ms total 116.120ms
,V/Mms     ( 6738): mnc/mcc: 
V/Mms     ( 6738): tag: int value: recipientLimit - 20
V/Mms     ( 6738): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6738): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6738): tag: int value: maxSubjectLength - 80
V/Mms     ( 6738): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6738): tag: bool value: enableGroupMms - false
V/Mms     ( 6738):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6738): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6776 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6638:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 6776): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_6638/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6776): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6776): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 6665:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_6665/cgroup.procs: No such file or directory
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015263063 min interval config: 0 actual interval: 1972
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6800 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6004): Checking schedule, now: 1452015265090 next: 1452015293031
I/CheckinService( 6004): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6817 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6688:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_6688/cgroup.procs: No such file or directory
,W/ResourcesManager( 6817): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6817): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6817): MmsConfig.loadMmsSettings
I/Babel_SMS( 6817): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6817): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6817): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6817): MmsConfig.loadFromResources
E/Babel_SMS( 6817): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6817): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6817): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6817): startup - clean
,I/Babel   ( 6817): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6856 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6817): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6817): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6817): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6817): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6817): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6817): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6817): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6817): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6817): onServiceConnected
W/Babel   ( 6817): Attempted to change video mute state without an active call.
,I/jxcore-log( 6166): Test app app.js loaded
I/jxcore-log( 6166): 
,I/GAv4    ( 6856): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6856):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6856):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6856): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/chromium( 6166): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6856): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6856): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 6817): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  878): Killing 6738:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6856): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6856): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6856): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6856): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_6738/cgroup.procs: No such file or directory
,I/WebViewFactory( 6856): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6856): Time to load native libraries: 1 ms (timestamps 3586-3587)
I/LibraryLoader( 6856): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6856): Binding Chromium to main looper Looper (main, tid 1) {601b115}
I/LibraryLoader( 6856): Expected native library version number "",actual native library version number ""
,I/chromium( 6856): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6856): Initializing chromium process, singleProcess=true
,W/art     ( 6856): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6856): ApplicationContext is null in ApplicationStatus
,W/chromium( 6856): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6856): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6856): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6856): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6856): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6856): Local Branch: 
I/Adreno-EGL( 6856): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6856): Local Patches: NONE
I/Adreno-EGL( 6856): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6856): Requires BLUETOOTH permission
,I/NSApplication( 6856): Starting up...
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6924 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 6776:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_6776/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6943 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 6800:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_6800/cgroup.procs: No such file or directory
,W/ResourcesManager( 6943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6963 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6856:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 6963): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 6817:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_6856/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2693): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_6817/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2693): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2693): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2693): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2693): onServiceConnected()
D/GetNotificationsWS( 2693): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2693): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2693): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6988 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/LocationInitializer( 6004): Restart initialization of location
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1736): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7011 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
,I/MusicStore( 7011): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7011): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7011): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7011): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7011): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7011): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@706b194: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7011): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7011): GMSCore installation verified
,I/ConfigStore( 7011): Config Database version: 1
,I/MediaRouter( 7011): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7011): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7011): type=WIFI subType= reason=null isConnected=true
,I/art     (  878): Explicit concurrent mark sweep GC freed 12080(582KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.527ms total 119.778ms
,I/NetworkMonitor( 7011): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  878): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7042 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 24.841ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 21.690ms
,I/GHttpClientFactory( 7011): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7011): Using platform SSLCertificateSocketFactory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 21.070ms
,I/ActivityManager(  878): Killing 6493:com.google.android.gms.unstable/u0a16 (adj 15): empty #7,
,V/Mms     ( 7042): mnc/mcc: 
,V/Mms     ( 7042): tag: int value: recipientLimit - 20
V/Mms     ( 7042): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7042): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7042): tag: int value: maxSubjectLength - 80
V/Mms     ( 7042): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7042): tag: bool value: enableGroupMms - false
V/Mms     ( 7042):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_6493/cgroup.procs: No such file or directory
,W/ResourcesManager( 7042): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7077 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6924:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7077): Register our PhoneStateListener
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_6924/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7077): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7077): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  878): Killing 6943:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_6943/cgroup.procs: No such file or directory
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015263063 min interval config: 0 actual interval: 5833
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015263063 min interval config: 0 actual interval: 5835
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/CheckinService( 6004): Checking schedule, now: 1452015268922 next: 1452015293031
,I/CheckinService( 6004): active receiver: disabled
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7101 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6004): Checking schedule, now: 1452015268989 next: 1452015293031
I/CheckinService( 6004): active receiver: disabled
,W/ResourcesManager( 7101): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@13d75587
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1566): Deferring update until onResume
,I/Babel_SMS( 7101): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7101): MmsConfig.loadMmsSettings
I/Babel_SMS( 7101): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7101): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7101): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7101): MmsConfig.loadFromResources
E/Babel_SMS( 7101): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7101): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7101): startup - clean
,I/Babel   ( 7101): deleted: false for 0
,I/ActivityManager(  878): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7137 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,W/AudioCapabilities( 7101): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7101): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7101): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7101): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7101): onServiceConnected
,W/Babel   ( 7101): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7101): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 7137): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7137):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7137):   adb logcat -s GAv4
,I/ActivityManager(  878): Killing 6963:android.process.acore/u0a7 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_6963/cgroup.procs: No such file or directory
,W/GAv4    ( 7137): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7137): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7137): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7137): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7137): Time to load native libraries: 3 ms (timestamps 6899-6902)
I/LibraryLoader( 7137): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7137): Binding Chromium to main looper Looper (main, tid 1) {601b115}
I/LibraryLoader( 7137): Expected native library version number "",actual native library version number ""
,I/chromium( 7137): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7137): Initializing chromium process, singleProcess=true
,W/art     ( 7137): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7137): ApplicationContext is null in ApplicationStatus
,W/chromium( 7137): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7137): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7137): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7137): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7137): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7137): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7137): Local Branch: 
I/Adreno-EGL( 7137): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7137): Local Patches: NONE
I/Adreno-EGL( 7137): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7137): Requires BLUETOOTH permission
,I/NSApplication( 7137): Starting up...
,W/ProcessCpuTracker(  878): Skipping unknown process pid 7161
W/ProcessCpuTracker(  878): Skipping unknown process pid 7162
W/ProcessCpuTracker(  878): Skipping unknown process pid 7168
W/ProcessCpuTracker(  878): Skipping unknown process pid 7190
,I/ActivityManager(  878): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7208 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7011:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10080/pid_7011/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7227 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7042:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10023/pid_7042/cgroup.procs: No such file or directory
,W/ResourcesManager( 7227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  878): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7247 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 6988:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7247): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Killing 7077:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2693): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_6988/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7077/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2693): bindWebServices(): registering our AIDL callback...
I/SundryService( 2693): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2693): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2693): onServiceConnected()
D/GetNotificationsWS( 2693): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2693): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2693): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2693): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
D/OtaApp  ( 2693): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2693): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  878): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  878): done {3fe7819a, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9123ms]
,D/OtaApp  ( 2693): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2693): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2693): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7278 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2693): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2693): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2693): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2693): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2693): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2693): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2693): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2693): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2693): publish the event [tag = MOT_OTA event name = LOG]
,D/PhoneMonitor( 7278): Register our PhoneStateListener
,W/IInputConnectionWrapper( 6166): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1411): onFinishInput()
,V/SetupWizard( 7278): Connected to Gservices successfully
,I/ActivityManager(  878): Killing 7101:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7101/cgroup.procs: No such file or directory
,I/LaunchCheckinHandler(  878): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,303
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  878): Explicit concurrent mark sweep GC freed 18987(952KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.684ms total 128.653ms
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7302 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7325 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7137:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10081/pid_7137/cgroup.procs: No such file or directory
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7348 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7365 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7208:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.069ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 25.214ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.494ms
,I/ActivityManager(  878): Killing 7227:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10052/pid_7208/cgroup.procs: No such file or directory
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7227/cgroup.procs: No such file or directory
,W/ResourcesManager( 7365): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7365): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7365): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7365): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7365): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7365): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7365): MmsConfig.loadFromResources
,E/Babel_SMS( 7365): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7365): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7365): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7365): startup - clean
,I/Babel   ( 7365): deleted: false for 0
,W/art     ( 7365): Suspending all threads took: 6.656ms
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7400 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7278:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/VideoCapabilities( 7365): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7365): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7365): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7365): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7365): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7365): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7365): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7365): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7278/cgroup.procs: No such file or directory
,W/asset   ( 7400): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7400): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7400): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6004): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1566): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@384ea7c2 new=com.google.android.velvet.VelvetApplication@384ea7c2
,I/UpdateIcingCorporaServi( 7325): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7429 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7365): onServiceConnected
W/Babel   ( 7365): Attempted to change video mute state without an active call.
,I/PackageBroadcastService( 6004): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 7429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7365): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7365): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 6004): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 7365): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 7325): UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,W/System  ( 7365): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7365): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7465 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7302:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7302/cgroup.procs: No such file or directory
,D/Finsky  ( 7465): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  878): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 7465): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7465): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7465): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7465): Skipping gmscore version check
,D/Finsky  ( 7465): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7465): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  878): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7511 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7348:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_7348/cgroup.procs: No such file or directory
,D/Finsky  ( 7465): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7465): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  878): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7543 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7400:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_7400/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7543): Register our PhoneStateListener
,I/Icing   ( 6004): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  878): Killing 7325:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_7325/cgroup.procs: No such file or directory
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015263063 min interval config: 0 actual interval: 11424
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6004): Checking schedule, now: 1452015274531 next: 1452015293031
I/CheckinService( 6004): active receiver: disabled
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Icing   ( 6004): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6004): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 7247:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_7247/cgroup.procs: No such file or directory
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311874, SEQNUM=4464, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-347, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ActivityManager(  878): Killing 7429:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7429/cgroup.procs: No such file or directory
,I/CheckinService( 6004): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311035, SEQNUM=4468, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-361, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1736): disconnect managed GoogleApiClient
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {9830492, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  878): send {2a565f7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  878): done {9830492, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [16ms]
V/AlarmManager(  878): done {2a565f7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [17ms]
,I/CheckinService( 6004): Checkin interval check for package: unspecified last checkin: 1452015263063 min interval config: 0 actual interval: 36522
,I/CheckinService( 6004): Checking schedule, now: 1452015299596 next: 1452015293031
I/CheckinService( 6004): active receiver: enabled
,I/CheckinService( 6004): Preparing to send checkin request
I/EventLogService( 6004): Accumulating logs since 1452015259078
,I/CheckinRequestBuilder( 6004): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6004): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  878): Explicit concurrent mark sweep GC freed 14253(748KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.568ms total 113.547ms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  878): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7598 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7598): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7598): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7598): VM with version 2.1.0 has multidex support
,I/MultiDex( 7598): install
I/MultiDex( 7598): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7598): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7598): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7598): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37d954a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7598): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,E/MDM     ( 1736): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6004): Restart initialization of location
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,I/art     ( 7598): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7598): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7598): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb13cf960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb814bb58, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8149200, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8216790, idLength=0xbec5c2b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2649665292
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81caed8
D/DrmWidevineDash(  295): message_length=1591, signature=0xb80e3ba8, signature_length=3200631444
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7630): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7630): dex2oat took 88.958ms (threads: 4)
,I/Adreno-EGL( 7598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7598): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7598): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7598): Local Branch: 
I/Adreno-EGL( 7598): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7598): Local Patches: NONE
I/Adreno-EGL( 7598): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7598): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7598): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7598): Local Branch: 
I/Adreno-EGL( 7598): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7598): Local Patches: NONE
I/Adreno-EGL( 7598): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fde000
D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
,D/DrmWidevineDash(  295): tz api version =  8
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb13cf960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb814ba98, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8149200, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb82167b0, idLength=0xb54b9730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=2845763121
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb81caed8
D/DrmWidevineDash(  295): message_length=1626, signature=0xb80e3bc8, signature_length=3041629972
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  295): L3 Terminate.
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7598): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7598): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7598): Local Branch: 
I/Adreno-EGL( 7598): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7598): Local Patches: NONE
I/Adreno-EGL( 7598): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7598): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7598): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7598): Local Branch: 
I/Adreno-EGL( 7598): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7598): Local Patches: NONE
I/Adreno-EGL( 7598): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6004): Classify the device as Phone.
,I/CheckinTask( 6004): Sending checkin request (9513 bytes)
,I/CheckinRequestBuilder( 6004): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6004): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6004): Classify the device as Phone.
,I/CheckinTask( 6004): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6004): Checking schedule, now: 1452015304233 next: 1452616441228
I/CheckinService( 6004): active receiver: disabled
,D/CheckinService( 6004): Recording last checkin time for package unspecified as 1452015304245
,V/SetupWizard( 7543): Connected to Gservices successfully
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  878): Killing 7465:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_7465/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7686 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  878): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  878): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  878): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@161ccf69
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1566): Deferring update until onResume
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 106790(5MB) AllocSpace objects, 31(519KB) LOS objects, 40% free, 15MB/25MB, paused 1.119ms total 123.353ms
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6e8c459)
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@12c4e81e)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21c428ff)
E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@193d56cc)
,E/DataBuffer( 1736): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d584d15)
,I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7727 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7746 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7511:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10088/pid_7511/cgroup.procs: No such file or directory
,W/ResourcesManager( 7365): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7365): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ContactLocale( 7746): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7772 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  878): Killing 7543:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10035/pid_7543/cgroup.procs: No such file or directory
,W/asset   ( 7772): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7772): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7772): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7772): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6004): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6004): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6004): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1566): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@384ea7c2 new=com.google.android.velvet.VelvetApplication@384ea7c2
,I/UpdateIcingCorporaServi( 7686): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  878): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7798 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 26.222ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 19.707ms
,W/ResourcesManager( 7798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.923ms
,I/UpdateIcingCorporaServi( 7686): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
,I/art     (  878): Explicit concurrent mark sweep GC freed 17635(909KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.546ms total 120.986ms
,I/ActivityManager(  878): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7830 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 7598:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_7598/cgroup.procs: No such file or directory
,D/Finsky  ( 7830): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7830): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7830): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7830): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7830): Skipping gmscore version check
D/Finsky  ( 7830): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7830): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7830): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7830): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  878): Killing 7727:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10019/pid_7727/cgroup.procs: No such file or directory
,I/Icing   ( 6004): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6004): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  878): Killing 7772:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10027/pid_7772/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  878): Killing 7365:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10070/pid_7365/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1411): run()
I/Keyboard.Facilitator( 1411): flushDynamicLanguageModels()
,I/ConfigService( 1736): onCreate
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310910, SEQNUM=4494, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-379, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ConfigService( 1736): onDestroy
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311110, SEQNUM=4496, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-418, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=247, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311387, SEQNUM=4499, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-447, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): TAP version 13
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # multiplex can send data
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 1 String should be length:200
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # basic
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 2 sane
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # another
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 3 sane
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 4 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 5 null
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 6 (unnamed assert)
I/jxcore-log( 6166): 
I/jxcore-log( 6166): ok 7 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 8 should not throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 9 (unnamed assert)
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 10 (unnamed assert)
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 11 should not throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 12 should be equal
I/jxcore-log( 6166): 
I/jxcore-log( 6166): ok 13 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 14 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # failed to get mobile documents path
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 15 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 16 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 17 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 18 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # #init should register the networkChanged event
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 19 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on null device name
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 20 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 21 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 22 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 23 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on negative port
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 24 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should throw on too large port
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 25 should throw
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 26 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 27 should be equal
I/jxcore-log( 6166): 
I/jxcore-log( 6166): ok 28 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 29 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 30 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 31 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 32 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 33 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 34 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 35 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 36 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 37 should be equal
I/jxcore-log( 6166): 
I/jxcore-log( 6166): ok 38 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 39 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 40 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 41 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 42 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6166): ok 43 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): ok 44 should be equal
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6166): 
,I/jxcore-log( 6166): # teardown
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606751.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606751.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606751.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606751.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606751.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015606751.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a1bfd46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a1bfd46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
,D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  878): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6166): start: OK
,I/jxcore-log( 6166): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
,D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
,D/WifiP2pService(  878): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
,D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
,I/jxcore-log( 6166): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606940.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606940.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606940.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606940.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606940.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015606940.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2843b6c6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2843b6c6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  878): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
,I/jxcore-log( 6166): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
,I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
,D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/WifiP2pService(  878): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
I/jxcore-log( 6166): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606991.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606991.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015606991.6166
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606991.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015606991.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015606991.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@faaab8ba target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@faaab8ba target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 6166): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
,D/WifiP2pService(  878): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
D/WifiP2pService(  878): remove client information from framework
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6166): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607016.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/WifiP2pService(  878): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607016.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607016.6166
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607016.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607016.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607016.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd4f2f90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cd4f2f90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  878): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
,I/jxcore-log( 6166): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
,I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
,D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
,D/WifiP2pService(  878): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  878): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
D/WifiP2pService(  878): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
,I/jxcore-log( 6166): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607054.6166
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607054.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607054.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607054.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607054.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607054.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f6f2640c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f6f2640c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  878): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
,I/jxcore-log( 6166): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
,I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
,D/WifiP2pService(  878): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState clear service request
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
I/jxcore-log( 6166): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607084.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607084.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607084.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607084.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607084.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607084.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  878): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@232f3946 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@232f3946 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  878): discovery change broadcast true
,I/jxcore-log( 6166): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
D/WifiP2pService(  878): remove client information from framework
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6166): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
D/WifiP2pService(  878): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607108.6166
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607108.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607108.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607108.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607108.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607108.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2ab24a8c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2ab24a8c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
,D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  878): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
I/jxcore-log( 6166): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/WifiP2pService(  878): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
D/WifiP2pService(  878): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
I/jxcore-log( 6166): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607133.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607133.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607133.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607133.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607133.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607133.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ab91b190 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ab91b190 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
I/jxcore-log( 6166): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
D/WifiP2pService(  878): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/WifiP2pService(  878): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/WifiP2pService(  878): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
,I/jxcore-log( 6166): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607174.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607174.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607174.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607174.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607174.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607174.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  878): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6f39c1c6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6f39c1c6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
D/WifiP2pService(  878): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  293): Event received = P2P: Reject scan trigger 
,I/jxcore-log( 6166): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
D/WifiP2pService(  878): discovery change broadcast true
D/TCMD    (  509): NL - Read 56 bytes from update socket.
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,I/wpa_supplicant( 1433): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-80
,I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 9e
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 1 9e
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/WifiP2pService(  878): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
D/WifiP2pService(  878): remove client information from framework
D/WifiP2pService(  878): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6166): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607201.6166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): bind: Binding a new listener
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607201.6166","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6166): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): start: OK
I/io.jxcore.node.ConnectionHelper( 6166): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1452015607201.6166
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6166): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607201.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): start: {"pi":"44:80:EB:7B:5A:05","pn":"1452015607201.6166","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1452015607201.6166","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): start: OK
I/jxcore-log( 6166): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6166): 
I/io.jxcore.node.ConnectionHelper( 6166): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6166): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6166): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6166): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6166): stop: Stopping services
I/wpa_supplicant( 1433): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6166): release: No more listeners, de-initializing...
D/WifiP2pService(  878): InactiveState{ when=-23ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-23ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: null
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 0
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 0
D/WifiP2pService(  878):  status: 4
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: null
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 0
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 0
D/WifiP2pService(  878):  status: 4
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
D/WifiP2pService(  878): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c8c5c418 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c8c5c418 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState add service
D/WifiP2pService(  878): add a new client
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6166): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6166): setState: NOT_STARTED
D/WifiP2pService(  878): InactiveState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6166): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6166): 
I/wpa_supplicant( 1433): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
D/WifiP2pService(  878): discovery change broadcast true
D/WifiP2pService(  878): InactiveState{ when=-3ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service
D/WifiP2pService(  878): remove client information from framework
D/WifiP2pService(  878): InactiveState{ when=-5ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1433): P2P-FIND-STOPPED 
D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  293): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6166): # setup
I/jxcore-log( 6166): 
D/WifiP2pService(  878): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
D/WifiP2pService(  878): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  878): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.,btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 6166): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6166): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6166): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6166): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6166): Service requests cleared successfully
,D/TCMD    (  509): NL - Read 56 bytes from update socket.,
D/TCMD    (  509): NL - message type is RTM_NEWLINK
D/TCMD    (  509): Listening for incoming client connection request
,I/wpa_supplicant( 1433): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1 level=-80
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/MDMCTBK (  293): Event received = P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2
D/WifiP2pService(  878): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=-1ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: 3-0050F204-5
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 128
D/WifiP2pService(  878):  grpcapab: 9
D/WifiP2pService(  878):  devcapab: 4
D/WifiP2pService(  878):  status: 3
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: -80 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC,
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1433): P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e:3e:3a:c5
,D/MDMCTBK (  293): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/MDMCTBK (  293): Event received = P2P-DEVICE-LOST p2p_dev_addr=9e:93:4e
,D/WifiP2pService(  878): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: null
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 0
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 0
D/WifiP2pService(  878):  status: 4
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  878): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  878):  deviceAddress: 9e:93:4e:3e:3a:c5
D/WifiP2pService(  878):  primary type: null
D/WifiP2pService(  878):  secondary type: null
D/WifiP2pService(  878):  wps: 0
D/WifiP2pService(  878):  grpcapab: 0
D/WifiP2pService(  878):  devcapab: 0
D/WifiP2pService(  878):  status: 4
D/WifiP2pService(  878):  wfdInfo: null
D/WifiP2pService(  878):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=239, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310985, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-686, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1d26472e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  878): send {16931c9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  878): done {1d26472e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [23ms]
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  878): done {16931c9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [55ms]
,I/EventLogService( 6004): Aggregate from 1452015299622 (log), 1452013885871 (data)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {c24fbda, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  878): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7972 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [92ms]
,I/GAv4    ( 7972): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7972):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7972):   adb logcat -s GAv4
,W/GAv4    ( 7972): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7972): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7972): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  878): done {c24fbda, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [381ms]
,I/ActivityManager(  878): Killing 7686:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10039/pid_7686/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1517d80b, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  878): done {1517d80b, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [29ms]
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/UsageStatsService(  878): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {273740e9, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  878): done {273740e9, *walarm*:android.content.syncmanager.SYNC_ALARM} [8ms]
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311193, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-525, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311500, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-555, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {227c86e8, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  878): done {227c86e8, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [26ms]
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [104ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=232, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311487, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-571, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2533): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {1d26472e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,I/ProcessStatsService(  878): Prepared write state in 12ms
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  878): send {14f1b136, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  878): done {1d26472e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [40ms]
,I/ProcessStatsService(  878): Prepared write state in 20ms
,V/AlarmManager(  878): done {14f1b136, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [75ms]
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [91ms]
,I/ProcessStatsService(  878): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-19-14.bin
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
,V/AlarmManager(  878): send {3bc4420f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {10e6fba6, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  878): send {1b69e9e7, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  878): send {1072994, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  878): send {1b2ffc3d, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  878): done {3bc4420f, *alarm*:android.intent.action.TIME_TICK} [52ms]
,V/AlarmManager(  878): done {10e6fba6, *walarm*:com.motorola.ccc.cce.alarmintent} [113ms]
,V/AlarmManager(  878): done {1b69e9e7, *walarm*:com.motorola.ccc.cce.alarmintent} [127ms]
,V/AlarmManager(  878): done {1072994, *walarm*:com.motorola.ccc.cce.alarmintent} [141ms]
,V/AlarmManager(  878): done {1b2ffc3d, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [147ms]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8028): 
D/AndroidRuntime( 8028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8028): CheckJNI is OFF
D/AndroidRuntime( 8028): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10413 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 6166:com.test.thalitest/u0a413 (adj 9): stop com.test.thalitest
W/PackageSettings(  878): Skipping PackageSetting{1efcb0a9 com.example.hello/10406} due to missing metadata
I/WindowState(  878): WIN DEATH: Window{37f113d6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  878): Client connection lost with reason: 4
I/ActivityManager(  878):   Force finishing activity ActivityRecord{326cfd13 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  878): Spurious death for ProcessRecord{e121fc4 6166:com.test.thalitest/u0a413}, curProc for 6166: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10413 user=0: pkg removed
I/ActivityManager(  878):   Force finishing activity ActivityRecord{326cfd13 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  878): Duplicate finish request for ActivityRecord{326cfd13 u0 com.test.thalitest/.MainActivity t3 f}
I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3132): Explicit concurrent mark sweep GC freed 6735(1459KB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 7MB/12MB, paused 761us total 75.908ms
I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
D/VoicemailCleanupService( 7746): Cleaning up data for package: com.test.thalitest
I/ThermalEngine(  304): Sensor:xo_therm_pu2:26000 mC
I/art     ( 1566): Explicit concurrent mark sweep GC freed 6828(453KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 498us total 108.972ms
I/Decoder ( 1411): createOrResetDecoder
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8059 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  878): Explicit concurrent mark sweep GC freed 33331(2MB) AllocSpace objects, 11(264KB) LOS objects, 33% free, 20MB/30MB, paused 1.430ms total 175.544ms
I/art     (  878): WaitForGcToComplete blocked for 175.097ms for cause Explicit
W/asset   ( 8059): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8059): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8059): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8059): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ConfigService( 1736): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8083 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
D/TaskPersister(  878): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  878): Killing 7798:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1566): Deferring update until onResume
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
I/art     (  878): Explicit concurrent mark sweep GC freed 7368(390KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.829ms total 208.938ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_7798/cgroup.procs: No such file or directory
W/ContextImpl( 8083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6004): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6004): Reading stored module config
D/AccountUtils( 6004): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6004): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6004): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6004): App measurement is starting up, version: 8489
I/GMPM-SVC( 6004): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8115 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 6004): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6004): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6004): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6004): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6004): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6004): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/AndroidRuntime( 8028): Shutting down VM
D/gH_CompatibleDatabase( 6004): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6004): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6004): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6004): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6004): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6004): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6004): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ChimeraCfgMgr( 6004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6004): Module APK com.google.android.play.games already loaded
I/Icing   ( 6004): doRemovePackageData com.test.thalitest
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
E/BaseAppContext( 6004): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/Launcher( 1566): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@384ea7c2 new=com.google.android.velvet.VelvetApplication@384ea7c2
I/ActivityManager(  878): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8154 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 6004): cleanUpNonGplusAccounts done.
D/ConnectivityService(  878): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  878): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  878): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6004): CM callback handler got msg 524290
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/BaseAppContext( 6004): Using Auth Proxy for data requests.
W/DriveInitializer( 6004): Awaiting to be initialized
W/DriveInitializer( 6004): Background init thread started
I/ActivityManager(  878): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8182 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8115): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  878): Killing 7830:com.android.vending/u0a32 (adj 15): empty #7
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6004): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
W/libprocessgroup(  878): failed to open /acct/uid_10032/pid_7830/cgroup.procs: No such file or directory
I/art     ( 5976): Explicit concurrent mark sweep GC freed 1695(61KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 335us total 24.070ms
W/DriveInitializer( 6004): Background init thread ended
I/UpdateIcingCorporaServi( 8115): UpdateCorporaTask done [took 350 ms] updated apps [took 350 ms] 
I/ActivityManager(  878): Killing 7972:com.google.android.deskclock/u0a55 (adj 15): empty #7
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
