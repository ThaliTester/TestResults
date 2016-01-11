#### Test 55613145dd493c6_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2552): no tags to log
D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
I/art     (  887): Explicit concurrent mark sweep GC freed 34928(1680KB) AllocSpace objects, 2(214KB) LOS objects, 33% free, 20MB/30MB, paused 6.429ms total 154.578ms
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1477): Explicit concurrent mark sweep GC freed 55381(3MB) AllocSpace objects, 37(1245KB) LOS objects, 39% free, 7MB/12MB, paused 881us total 44.700ms
D/AndroidRuntime( 6446): 
D/AndroidRuntime( 6446): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 6446): CheckJNI is OFF
I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1546): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2552): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2552): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2552): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2552): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2552): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2552): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2552): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2552): publish the event [tag = MOT_CHECKIN event name = LOG]
D/AndroidRuntime( 6446): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  887): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  887): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6470 uid=10434 gids={50434, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6446): Shutting down VM
V/ActivityManager(  887): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6470): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6470): Time to load native libraries: 2 ms (timestamps 5030-5032)
I/LibraryLoader( 6470): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6470): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 6470): Expected native library version number "",actual native library version number ""
,I/chromium( 6470): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6470): Initializing chromium process, singleProcess=true
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6470): ApplicationContext is null in ApplicationStatus
,W/chromium( 6470): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6470): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6470): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6470): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6470): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6470): Local Branch: 
I/Adreno-EGL( 6470): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6470): Local Patches: NONE
I/Adreno-EGL( 6470): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@166c6666:true
,W/ActivityManager(  887): Activity pause timeout for ActivityRecord{d93c953 u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6470): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6470): CordovaWebView is running on device made by: motorola
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6470): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6470): Render dirty regions requested: true
,D/Atlas   ( 6470): Validating map...
,W/chromium( 6470): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6470): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6470): Enabling debug mode 0
,I/Keyboard.Facilitator( 1422): onFinishInput()
,I/LaunchCheckinHandler(  887): Displayed com.test.thalitest/.MainActivity,cp,ca,1008
,I/ActivityManager(  887): Displayed com.test.thalitest/.MainActivity: +941ms (total +1s8ms)
W/IInputConnectionWrapper( 6470): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6470): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6470): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6470): Cannot call determinedVisibility() - never saw a connection for the pid: 6470
,D/JsMessageQueue( 6470): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  887): send {5486d33, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  887): done {5486d33, *walarm*:com.google.android.intent.action.SEND_IDLE} [10ms]
,D/jxcore_app_log( 6470): JniHelper::setJavaVM(0xb8821310), pthread_self() = -1195698240
D/JX-Cordova( 6470): jxcore cordova android initializing
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/art     (  887): Explicit concurrent mark sweep GC freed 8430(406KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.542ms total 110.518ms
,I/PhenotypeConfigurator( 1779): Scheduling Phenotype for one-off execution 12354 seconds from now (1452517050660)
,D/GetConfigurationSnapshotOperation( 1779): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1779): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1779): Using platform SSLCertificateSocketFactory
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
,W/jxcore-log( 6470): Initializing JXcore engine
,W/jxcore-log( 6470): JXcore engine is ready
,W/jxcore-log( 6470): Starting JXcore engine
,W/.test.thalitest( 6470): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10434 path="socket:[7537]" dev="sockfs" ino=7537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6470): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10434 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6470): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10434 path="socket:[8490]" dev="sockfs" ino=8490 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6470): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10434 path="socket:[27361]" dev="sockfs" ino=27361 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6470): Platform android
W/jxcore-log( 6470): 
,W/jxcore-log( 6470): Process ARCH arm
W/jxcore-log( 6470): 
,I/jxcore-log( 6470): JXcore Cordova bridge is ready!
I/jxcore-log( 6470): 
W/jxcore-log( 6470): JXcore engine is started
,I/chromium( 6470): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6470): Toggling radios to true
I/jxcore-log( 6470): 
,D/BluetoothAdapter( 6470): enable(): BT is already enabled..!
,D/WifiService(  887): New client listening to asynchronous messages
,D/WifiService(  887): setWifiEnabled: true pid=6470, uid=10434
E/WifiService(  887): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6470): Radios toggled
I/jxcore-log( 6470): 
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6470): Received device characteristics:
I/jxcore-log( 6470): Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6470): Bluetooth name: XT1072
I/jxcore-log( 6470): Device name: motorola-XT1072
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Perf Test app loaded loaded
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): check test folder
I/jxcore-log( 6470): 
I/jxcore-log( 6470): found test : ./testFindPeers.js
I/jxcore-log( 6470): 
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  887): InitialState.processMessage what=4
I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1443): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
V/NativeCrypto( 1779): Read error: ssl=0xb8b96848: I/O error during system call, Connection timed out
,V/NativeCrypto( 1779): SSL shutdown failed: ssl=0xb8b96848: I/O error during system call, Broken pipe
,I/jxcore-log( 6470): found test : ./testSendData.js
I/jxcore-log( 6470): 
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-7ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-7ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6565 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 22.820ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 18.905ms
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 20.404ms
,D/WifiMetrics(  887): connected time updated 131059
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1443): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  887): Start Disconnecting Watchdog 1
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  887): ConnectModeState: Network connection lost 
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1443): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1969): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524292
D/Uploader( 1779): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/chromium( 6470): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 6565): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6565): MmsConfig.loadMmsSettings
I/Babel_SMS( 6565): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6565): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6565): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6565): MmsConfig.loadFromResources
,E/Babel_SMS( 6565): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6565): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6565): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6565): startup - clean
,I/Babel   ( 6565): deleted: false for 0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): wlan0: Trying to associate with SSID 'NG700'
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6606 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/wpa_supplicant( 1443): DSDS: eapol_sm_notify_config config->sim_num = 1
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  887): [1,452,517,056,223 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6606): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6565): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6565): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6565): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 6241:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 192 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1443): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1443): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
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
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221780064
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
,W/libprocessgroup(  887): failed to open /acct/uid_10057/pid_6241/cgroup.procs: No such file or directory
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,W/art     ( 6565): Suspending all threads took: 10.015ms
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 2
I/vclib   ( 6565): onServiceConnected
W/Babel   ( 6565): Attempted to change video mute state without an active call.
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 1443): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1443): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  887): Killing 6013:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_6013/cgroup.procs: No such file or directory
,E/DHCPCD  ( 6631): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6631): version 5.5.6 starting
E/DHCPCD  ( 6631): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6631): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6631): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6631): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6631): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6631): wlan0: sending REQUEST (xid 0x3be8c8e), next in 4.11 seconds
,I/DHCPCD  ( 6631): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6631): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6631): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6631): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6631): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6631): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
D/TCMD    (  472): Listening for incoming client connection request
,D/DHCPCD  ( 6631): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  887): Setting Dns servers for network 101 to [/192.168.1.1]
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  887):    accepting network in place of null
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1969): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 12:57:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452517058504], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452517058483]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1969): CM callback handler got msg 524290
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6703 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2552): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2552): [debug] > CusSM.onRadioDown
,I/MusicStore( 6703): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6703): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6703): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6703): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6703): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6703): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6703): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6703): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6703): GMSCore installation verified
,I/ConfigStore( 6703): Config Database version: 1
,I/MediaRouter( 6703): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6703): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NetworkMonitor( 6703): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6703): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6756 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6703): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6703): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 6284:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6284/cgroup.procs: No such file or directory
,V/Mms     ( 6756): mnc/mcc: 
,V/Mms     ( 6756): tag: int value: recipientLimit - 20
V/Mms     ( 6756): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6756): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6756): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6756): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6756): tag: bool value: enableGroupMms - false
,V/Mms     ( 6756):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6756): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6788 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6316:com.android.vending/u0a32 (adj 15): empty #7
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_6316/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6788): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6788): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6788): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 6565:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6565/cgroup.procs: No such file or directory
,I/CheckinService( 1969): Checkin interval check for package: unspecified last checkin: 1452516968856 min interval config: 0 actual interval: 91145
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6813 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1969): Checking schedule, now: 1452517060061 next: 1452516998784
I/CheckinService( 1969): active receiver: enabled
,I/CheckinService( 1969): Preparing to send checkin request
I/EventLogService( 1969): Accumulating logs since 1452516964567
,I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  887): Explicit concurrent mark sweep GC freed 46879(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 2.062ms total 126.592ms
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6831 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6848 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6831): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6848): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MultiDex( 6848): VM with version 2.1.0 has multidex support
I/MultiDex( 6848): install
I/MultiDex( 6848): VM has multidex support, MultiDex support library is disabled.
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6470): BLE is supported
I/jxcore-log( 6470): 
,V/JNIHelp ( 6848): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6848): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6848): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6848): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6831): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6831): MmsConfig.loadMmsSettings
I/Babel_SMS( 6831): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6831): MmsConfig.loadFromDatabase
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1969): CM callback handler got msg 524295
,I/art     ( 6848): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6848): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6831): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6831): MmsConfig.loadFromResources
E/Babel_SMS( 6831): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6831): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6831): startup - clean
,D/NativeLibraryUtils( 6848): Install completed successfully. count=14 extracted=0
,I/Babel   ( 6831): deleted: false for 0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6889 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54d9960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb758a3e0, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7659798, idLength=0xb1414730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=3289730682
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7510430
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7512498, signature_length=2973845268
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6831): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6831): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6831): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6831): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6831): onServiceConnected
,W/Babel   ( 6831): Attempted to change video mute state without an active call.
,I/Babel   ( 6831): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 6606:com.motorola.context/u0a8 (adj 15): empty #7
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
,W/libprocessgroup(  887): failed to open /acct/uid_10008/pid_6606/cgroup.procs: No such file or directory
,V/AlarmManager(  887): send {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): now: 207348 ,futureTime: 9223372036854775807
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): now: 207348 ,futureTime: 9223372036854775807
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): now: 207350 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2552): [debug] > PollingManagerService, now: 207359 ,futureTime: 11910134
D/OtaApp  ( 2552): [debug] > Polling alarm set to expire at: 11910134 Current Time: 207361
D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2552): [debug] > CusSM.onRadioUp
,D/Central_PollingManager( 1477): now: 207366 ,futureTime: 86474097
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86474097 Current Time: 207366
,D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/NetworkMonitor( 6703): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2552): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6889): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6889): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6889): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6889): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/dex2oat ( 6912): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/GAv4    ( 6889): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6889):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6889):   adb logcat -s GAv4
,I/art     ( 2552): Explicit concurrent mark sweep GC freed 30725(1879KB) AllocSpace objects, 4(87KB) LOS objects, 39% free, 11MB/19MB, paused 1.377ms total 100.257ms
,W/GAv4    ( 6889): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,W/GAv4    ( 6889): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 6912): dex2oat took 76.408ms (threads: 4)
,W/GAv4    ( 6889): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Adreno-EGL( 6848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6848): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6848): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6848): Local Branch: 
I/Adreno-EGL( 6848): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6848): Local Patches: NONE
I/Adreno-EGL( 6848): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 4879(227KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 711us total 34.471ms
,D/MMApiProvisionService( 2552): set mOutstandingReq to true.
I/ Nonce  ( 2552):  Nonce getNonce 
I/ Nonce  ( 2552):  Nonce Request 
I/ Nonce  ( 2552):  Nonce execute Request 
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2552): generating token using payload instead of using session token
,I/Adreno-EGL( 6848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6848): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6848): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6848): Local Branch: 
I/Adreno-EGL( 6848): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6848): Local Patches: NONE
I/Adreno-EGL( 6848): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/ Nonce  ( 2552):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2552): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/WebViewFactory( 6889): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6889): Time to load native libraries: 2 ms (timestamps 7874-7876)
I/LibraryLoader( 6889): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6889): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 6889): Expected native library version number "",actual native library version number ""
I/chromium( 6889): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6889): Initializing chromium process, singleProcess=true
,W/art     ( 6889): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6889): ApplicationContext is null in ApplicationStatus
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/chromium( 6889): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
E/libEGL  ( 6889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6889): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6889): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6889): Local Branch: 
I/Adreno-EGL( 6889): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6889): Local Patches: NONE
I/Adreno-EGL( 6889): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb55d9960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb758a3e0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597d8, idLength=0xb54d9730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=599594600
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb756df68
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7512498, signature_length=3041761044
,I/NSApplication( 6889): Starting up...
,W/AudioManagerAndroid( 6889): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6968 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6703:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_6703/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6848): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6848): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6848): Local Branch: 
I/Adreno-EGL( 6848): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6848): Local Patches: NONE
I/Adreno-EGL( 6848): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6848): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6848): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6848): Local Branch: 
I/Adreno-EGL( 6848): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6848): Local Patches: NONE
I/Adreno-EGL( 6848): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6995 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6756:com.android.mms/u0a23 (adj 15): empty #7
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_6756/cgroup.procs: No such file or directory
,I/ Nonce  ( 2552):  Nonce Reponse 
D/        ( 2552): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"d6b8a43a-a888-4d37-89cb-4b76fabbe242"}
D/MMApiWSBase( 2552): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2552):  Nonce Handle Reponse 
D/MMApiProvisionService( 2552): mOutstandingReq set to false
,W/ResourcesManager( 6995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinTask( 1969): Sending checkin request (9518 bytes)
,I/art     (  887): Explicit concurrent mark sweep GC freed 14184(658KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.900ms total 116.747ms
,D/MMApiProvisionService( 2552):  pTime 1452467391223 sExp 172742 cTime 1452517062880 tTime 1452640133223
D/MMApiProvisionService( 2552):  No login Required 
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7024 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.779ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 18.930ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 19.978ms
,I/ActivityManager(  887): Killing 6813:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/DataUsage( 2552): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/ContactLocale( 7024): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 6788:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_6813/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_6788/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2552): onServiceConnected()
D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7048 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2552): started with background data enabled, making sure notification mechanism is enabled
,I/MusicStore( 7048): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinRequestBuilder( 1969): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7048): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,I/CheckinTask( 1969): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1969): Checking schedule, now: 1452517063679 next: 1453118200674
I/CheckinService( 1969): active receiver: disabled
,D/CheckinService( 1969): Recording last checkin time for package unspecified as 1452517063689
,I/ActivityManager(  887): Killing 6831:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ActivityThread( 7048): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7048): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7048): GMSCore installation verified
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_6831/cgroup.procs: No such file or directory
,I/ConfigStore( 7048): Config Database version: 1
,I/MediaRouter( 7048): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7048): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7048): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Killing 6889:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_6889/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7048): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7083 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7048): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7048): Using platform SSLCertificateSocketFactory
,I/art     ( 6337): Explicit concurrent mark sweep GC freed 1807(80KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 339us total 35.550ms
,I/ActivityManager(  887): Killing 6968:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7083): mnc/mcc: 
,V/Mms     ( 7083): tag: int value: recipientLimit - 20
V/Mms     ( 7083): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7083): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7083): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7083): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7083): tag: bool value: enableGroupMms - false
V/Mms     ( 7083):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_6968/cgroup.procs: No such file or directory
,W/ResourcesManager( 7083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7114 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7024:android.process.acore/u0a7 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7024/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7114): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7114): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7114): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 6995:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_6995/cgroup.procs: No such file or directory
,I/CheckinService( 1969): Checkin interval check for package: unspecified last checkin: 1452517063689 min interval config: 0 actual interval: 637
,I/CheckinService( 1969): Checking schedule, now: 1452517064332 next: 1452517093674
,I/CheckinService( 1969): active receiver: disabled
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7133 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7153 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7048:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7048/cgroup.procs: No such file or directory
,W/ResourcesManager( 7153): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7153): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7153): MmsConfig.loadMmsSettings
I/Babel_SMS( 7153): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7153): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7153): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7153): MmsConfig.loadFromResources
,E/Babel_SMS( 7153): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7153): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7153): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7153): startup - clean
,I/Babel   ( 7153): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7180 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7153): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7153): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7153): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7153): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7153): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7153): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7153): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7153): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7153): onServiceConnected
,W/Babel   ( 7153): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7180): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7180): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7180):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7180):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7180): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7180): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7180): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7180): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7153): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 7083:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7180): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7180): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7083/cgroup.procs: No such file or directory
,I/WebViewFactory( 7180): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7180): Time to load native libraries: 2 ms (timestamps 1627-1629)
I/LibraryLoader( 7180): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7180): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7180): Expected native library version number "",actual native library version number ""
,I/chromium( 7180): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7180): Initializing chromium process, singleProcess=true
,W/art     ( 7180): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7180): ApplicationContext is null in ApplicationStatus
,W/chromium( 7180): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7180): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7180): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7180): Local Branch: 
I/Adreno-EGL( 7180): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7180): Local Patches: NONE
I/Adreno-EGL( 7180): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7180): Requires BLUETOOTH permission
,I/art     (  887): Explicit concurrent mark sweep GC freed 10961(557KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.474ms total 116.043ms
,I/NSApplication( 7180): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7253 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7114:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7114/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7275 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7133:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7133/cgroup.procs: No such file or directory
,W/ResourcesManager( 7275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7295 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7314 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7180:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7295): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  887): failed to kill 1 processes for processgroup 7180
I/ActivityManager(  887): Killing 7153:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7153/cgroup.procs: No such file or directory
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
,E/MDM     ( 1779): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1969): Restart initialization of location
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  887): done {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5805ms]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7357 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1779): No location to return for getLastLocation()
W/FusedLocationProvider( 1779): location=null
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.453ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.582ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.019ms
,I/MusicStore( 7357): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7357): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7357): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7357): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7357): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7357): GMSCore installation verified
,I/ConfigStore( 7357): Config Database version: 1
,I/MediaRouter( 7357): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7357): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7357): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7357): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7393 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7357): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7357): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 7253:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7393): mnc/mcc: 
,V/Mms     ( 7393): tag: int value: recipientLimit - 20
V/Mms     ( 7393): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7393): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7393): tag: int value: maxSubjectLength - 80
V/Mms     ( 7393): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7393): tag: bool value: enableGroupMms - false
V/Mms     ( 7393):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7253/cgroup.procs: No such file or directory
,W/ResourcesManager( 7393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7419 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7275:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7419): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7275/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7419): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7419): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 7295:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7295/cgroup.procs: No such file or directory
,I/CheckinService( 1969): Checkin interval check for package: unspecified last checkin: 1452517063689 min interval config: 0 actual interval: 4270
I/CheckinService( 1969): Checkin interval check for package: unspecified last checkin: 1452517063689 min interval config: 0 actual interval: 4272
,I/CheckinService( 1969): Checking schedule, now: 1452517067978 next: 1452517093674
I/CheckinService( 1969): active receiver: disabled
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7439 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1969): Checking schedule, now: 1452517068011 next: 1452517093674
,I/CheckinService( 1969): active receiver: disabled
,W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7439): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7439): MmsConfig.loadMmsSettings
I/Babel_SMS( 7439): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7439): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7439): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7439): MmsConfig.loadFromResources
,E/Babel_SMS( 7439): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7439): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7439): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7439): startup - clean
,I/Babel   ( 7439): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7471 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7439): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7439): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7439): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7439): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7439): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7439): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7439): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7439): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7439): onServiceConnected
W/Babel   ( 7439): Attempted to change video mute state without an active call.
,I/Babel   ( 7439): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  887): Killing 7357:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/GAv4    ( 7471): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7471):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7471):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7471): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_7357/cgroup.procs: No such file or directory
,W/GAv4    ( 7471): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7471): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7471): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7471): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     (  887): Explicit concurrent mark sweep GC freed 12886(622KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.513ms total 116.322ms
,I/LibraryLoader( 7471): Time to load native libraries: 2 ms (timestamps 4970-4972)
I/LibraryLoader( 7471): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7471): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7471): Expected native library version number "",actual native library version number ""
,I/chromium( 7471): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7471): Initializing chromium process, singleProcess=true
,W/art     ( 7471): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7471): ApplicationContext is null in ApplicationStatus
,W/chromium( 7471): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7471): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7471): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7471): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7471): Local Branch: 
I/Adreno-EGL( 7471): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7471): Local Patches: NONE
I/Adreno-EGL( 7471): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7471): Starting up...
,W/AudioManagerAndroid( 7471): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7538 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 6848:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_6848/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7557 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7393:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_7393/cgroup.procs: No such file or directory
,W/ResourcesManager( 7557): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7580 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7314:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7580): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 7419:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7314/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7419/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2552): onServiceConnected()
,D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2552): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2552): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2552): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2552): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7615 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6470): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1422): onFinishInput()
,D/PhoneMonitor( 7615): Register our PhoneStateListener
,V/SetupWizard( 7615): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 7439:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/LaunchCheckinHandler(  887): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,321
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7439/cgroup.procs: No such file or directory
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2eb9f277
,I/GCoreNlp( 1779): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1575): Deferring update until onResume
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7636 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7662 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7471:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_7471/cgroup.procs: No such file or directory
,W/ResourcesManager( 7662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7662): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7662): MmsConfig.loadMmsSettings
I/Babel_SMS( 7662): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7662): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7662): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7662): MmsConfig.loadFromResources
,E/Babel_SMS( 7662): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7662): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7662): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7662): startup - clean
,I/Babel   ( 7662): deleted: false for 0
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/VideoCapabilities( 7662): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7662): Unsupported mime audio/amr-wb-plus
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7696 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 24.666ms
,W/VideoCapabilities( 7662): Unsupported mime video/mpeg2
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 18.982ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.262ms
,I/VideoCapabilities( 7662): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7662): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7662): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7662): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7662): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 7538:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_7538/cgroup.procs: No such file or directory
,I/vclib   ( 7662): onServiceConnected
,W/Babel   ( 7662): Attempted to change video mute state without an active call.
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7729 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7747 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7557:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7557/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 7636:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/asset   ( 7747): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7747): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7747): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7747): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7662): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_7636/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1969): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1969): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 7696): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1969): updateResources: need to parse f{com.google.android.gms}
,V/JNIHelp ( 7662): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7789 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/System  ( 7662): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7662): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 7696): UpdateCorporaTask done [took 165 ms] updated apps [took 164 ms] 
,I/art     (  887): Explicit concurrent mark sweep GC freed 16969(861KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.506ms total 118.148ms
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7818 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7615:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7615/cgroup.procs: No such file or directory
,D/Finsky  ( 7818): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  887): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 7818): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7818): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7818): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7818): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7818): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7818): Skipping gmscore version check
,I/ActivityManager(  887): Killing 7747:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_7747/cgroup.procs: No such file or directory
,D/Finsky  ( 7818): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7818): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1969): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/art     ( 1969): Explicit concurrent mark sweep GC freed 53686(3MB) AllocSpace objects, 17(272KB) LOS objects, 24% free, 15MB/20MB, paused 1.147ms total 106.171ms
,I/Icing   ( 1969): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 7729:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_7729/cgroup.procs: No such file or directory
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311829, SEQNUM=4479, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-490, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ActivityManager(  887): Killing 7662:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_7662/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311903, SEQNUM=4481, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-545, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312500, SEQNUM=4482, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-546, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1779): disconnect managed GoogleApiClient
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {4389f36, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  887): send {1d612683, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  887): done {4389f36, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [21ms]
,V/AlarmManager(  887): done {1d612683, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [32ms]
,I/CheckinService( 1969): Checkin interval check for package: unspecified last checkin: 1452517063689 min interval config: 0 actual interval: 40628
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [51ms]
,I/CheckinService( 1969): Checking schedule, now: 1452517104341 next: 1452517093674
I/CheckinService( 1969): active receiver: enabled
,I/CheckinService( 1969): Preparing to send checkin request
I/EventLogService( 1969): Accumulating logs since 1452517060103
,I/CheckinRequestBuilder( 1969): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings,
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7883 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7883): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7883): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7883): VM with version 2.1.0 has multidex support
,I/MultiDex( 7883): install
I/MultiDex( 7883): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7883): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7883): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
,E/MDM     ( 1779): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1969): Restart initialization of location
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 7883): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7883): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7883): Install completed successfully. count=14 extracted=0
,I/art     ( 1779): Explicit concurrent mark sweep GC freed 106022(5MB) AllocSpace objects, 26(439KB) LOS objects, 39% free, 15MB/25MB, paused 1.307ms total 134.948ms
,W/GCoreFlp( 1779): No location to return for getLastLocation()
W/FusedLocationProvider( 1779): location=null
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
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
D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbec274e0
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7602010, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597b8, idLength=0xb55d9730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=376240340
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7510430
D/DrmWidevineDash(  294): message_length=1591, signature=0xb758b5f0, signature_length=3042809620
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7919): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7919): dex2oat took 69.821ms (threads: 4)
,I/Adreno-EGL( 7883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7883): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7883): Local Branch: 
I/Adreno-EGL( 7883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7883): Local Patches: NONE
I/Adreno-EGL( 7883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7883): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7883): Local Branch: 
I/Adreno-EGL( 7883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7883): Local Patches: NONE
I/Adreno-EGL( 7883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb54d9960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7593070, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597d8, idLength=0xbec272b0
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2350438015
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb756df68
D/DrmWidevineDash(  294): message_length=1626, signature=0xb750c4d8, signature_length=3200414356
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7883): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7883): Local Branch: 
I/Adreno-EGL( 7883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7883): Local Patches: NONE
I/Adreno-EGL( 7883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7883): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7883): Local Branch: 
I/Adreno-EGL( 7883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7883): Local Patches: NONE
I/Adreno-EGL( 7883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,I/CheckinTask( 1969): Sending checkin request (9520 bytes)
,I/CheckinRequestBuilder( 1969): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1969): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1969): Classify the device as Phone.
,I/CheckinTask( 1969): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1969): Checking schedule, now: 1452517108339 next: 1453118245330
I/CheckinService( 1969): active receiver: disabled
,D/CheckinService( 1969): Recording last checkin time for package unspecified as 1452517108351
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7953 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7953): Register our PhoneStateListener
,V/SetupWizard( 7953): Connected to Gservices successfully
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  887): Killing 7580:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  887): Killing 7696:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_7580/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7696/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7980 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2f47fa48
,I/GCoreNlp( 1779): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1575): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8013 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8033 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7789:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  887): Killing 7818:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_7789/cgroup.procs: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 21380(1137KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.493ms total 115.945ms
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_7818/cgroup.procs: No such file or directory
,W/ResourcesManager( 8033): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8033): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8033): MmsConfig.loadMmsSettings
I/Babel_SMS( 8033): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8033): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8033): MmsConfig.loadFromResources
,E/Babel_SMS( 8033): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8033): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8033): startup - clean
,I/Babel   ( 8033): deleted: false for 0
,I/ActivityManager(  887): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8073 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8033): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8033): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8033): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8033): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8094 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 7953:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 22.140ms
,I/ContactLocale( 8073): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 19.824ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.572ms
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_7953/cgroup.procs: No such file or directory
,W/asset   ( 8094): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8094): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8094): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8094): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1969): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1969): Null package name or gms related package.  Ignoreing.
,I/vclib   ( 8033): onServiceConnected
,W/Babel   ( 8033): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7980): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/Icing   ( 1969): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8033): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8033): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8123 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 8033): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 8123): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/System  ( 8033): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8033): Installed default security provider GmsCore_OpenSSL
I/UpdateIcingCorporaServi( 7980): UpdateCorporaTask done [took 169 ms] updated apps [took 169 ms] 
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8150 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 7883:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_7883/cgroup.procs: No such file or directory
,D/Finsky  ( 8150): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8150): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8150): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8150): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8150): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8150): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8150): Skipping gmscore version check
,D/Finsky  ( 8150): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8150): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Killing 8013:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_8013/cgroup.procs: No such file or directory
,I/Icing   ( 1969): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1969): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 8094:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_8094/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  887): Killing 7980:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_7980/cgroup.procs: No such file or directory
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
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
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
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1422): run()
,I/Keyboard.Facilitator( 1422): flushDynamicLanguageModels()
,I/ConfigService( 1779): onCreate
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1779): onDestroy
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311527, SEQNUM=4506, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-677, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6470): Connected to the server!
I/jxcore-log( 6470): 
,I/chromium( 6470): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 9
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {1a259352, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  887): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8209 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [146ms]
,I/GAv4    ( 8209): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8209):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8209):   adb logcat -s GAv4
,W/GAv4    ( 8209): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8209): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8209): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  887): done {1a259352, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [262ms]
,I/ActivityManager(  887): Killing 8033:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8033/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  887): send {184ee623, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  887): done {184ee623, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311411, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-948, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6470): --- start :testFindPeers.js---
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): testFindPeers created [object Object]
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): serverPort is 8876
I/jxcore-log( 6470): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): bind: Binding a new listener
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6470): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): start: OK
I/io.jxcore.node.ConnectionHelper( 6470): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6470): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6470): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6470): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  887): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setState: RUNNING
,D/WifiP2pService(  887): add a new client
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/io.jxcore.node.ConnectionHelper( 6470): start: OK
I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,I/jxcore-log( 6470): StartBroadcasting started ok
I/jxcore-log( 6470): 
I/chromium( 6470): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6470): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6470): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  887):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  887):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC One M8s","peerAvailable":true}]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Found peer : 90:E7:C4:F6:69:77, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 92
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 92
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 92
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 92
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/WifiP2pService(  887): InactiveState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
,D/WifiP2pService(  887): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Start timer timeout, starting now...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 c0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): restart: Restarting...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=-10ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-11ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 6470): onPeerLost: [90:E7:C4:F6:69:77 HTC One M8s]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] removed
,D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] not available
,I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC One M8s","peerAvailable":false}]
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  887): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
,D/WifiP2pService(  887): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311662, SEQNUM=4517, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1164, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Start timer timeout, starting now...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): restart: Restarting...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 7e
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 3 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 A3-1] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 G3s-1] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerLost: [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] removed
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] not available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":false}]
I/jxcore-log( 6470): 
I/io.jxcore.node.ConnectionHelper( 6470): onPeerLost: [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] removed
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] not available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":false}]
I/jxcore-log( 6470): 
I/io.jxcore.node.ConnectionHelper( 6470): onPeerLost: [F8:95:C7:87:85:54 G3s-1]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] removed
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] not available
I/jxcore-log( 6470): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":false}]
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/jxcore-log( 6470): timeout now
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): weAreDoneNow
I/jxcore-log( 6470): 
I/jxcore-log( 6470): done, now sending data to server
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139268 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1443): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  887): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
,D/WifiP2pService(  887): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Start timer timeout, starting now...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1443): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-58
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): restart: Restarting...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/jxcore-log( 6470): teardown
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): testFindPeers stopped
I/jxcore-log( 6470): 
,I/io.jxcore.node.ConnectionHelper( 6470): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): stop: Stopping services
,D/WifiP2pService(  887): InactiveState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): stop: Stopping P2P device discovery...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1443): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1443): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  887): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: null
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 0
D/WifiP2pService(  887):  grpcapab: 0
D/Wif,iP2pService(  887):  devcapab: 0
D/WifiP2pService(  887):  status: 4
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: NOT_INITIALIZED
D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
D/WifiP2pService(  887): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6470): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setState: NOT_STARTED
I/jxcore-log( 6470): StopBroadcasting went ok
I/jxcore-log( 6470): 
I/jxcore-log( 6470): --- start :testSendData.js---
I/jxcore-log( 6470): 
I/jxcore-log( 6470): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 13
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): daya100000
I/jxcore-log( 6470): 
I/jxcore-log( 6470): check server
I/jxcore-log( 6470): 
I/jxcore-log( 6470): serverPort is 56069
I/jxcore-log( 6470): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): bind: Binding a new listener
D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6470): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6470): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): start: OK
I/io.jxcore.node.ConnectionHelper( 6470): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): start: Peer ID: 44:80:EB:7B:5A:05, peer name: XT1072
,D/BluetoothManagerService(  887): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6470): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6470): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): start: {"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6470): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  887): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fad89d50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service
D/WifiP2pService(  887): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): start: Starting P2P device discovery...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6470): start: OK
,I/jxcore-log( 6470): StartBroadcasting started ok
I/jxcore-log( 6470): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Waiting for incoming connections...
,I/jxcore-log( 6470): [ { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 6470):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 6470):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 6470):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 6470):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 6470):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 6470):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 6470):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 6470):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 6470):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 6470):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 6470):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 6470):   { address: '7C:F9:0E:51:18:22', tryCount: 0 } ]
I/jxcore-log( 6470): 
I/jxcore-log( 6470): startWithNextDevice
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): do fake peer & start
I/jxcore-log( 6470): 
I/jxcore-log( 6470): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:27.348Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:27.348Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:27.348Z SendDataConnector.js: do connect now
I/jxcore-log( 6470): 
I/io.jxcore.node.ConnectionHelper( 6470): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 6470): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 6470): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 790)
W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 6470): 2016-01-11T13:03:27.355Z SendDataTCPServer.js: TCP/IP server is bound to port: 56069
I/jxcore-log( 6470): 
I/chromium( 6470): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6470): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6470): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6470): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 6470): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6470): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6470): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1443): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6470): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/BTIF_SOCK( 2439): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,W/bt-btif ( 2439): info:x10
,D/        ( 2439): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2439): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2439): process_service_search_attr_rsp
,E/bt-btif ( 2439): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2439): invalid rfc slot id: 6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 790)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Maximum number of allowed retries (0) reached, giving up... (thread ID: 790)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Exiting thread (thread ID: 790)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 6470): 2016-01-11T13:03:28.841Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:28.842Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:28.842Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6470): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): shutdown (thread ID: 790)
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,W/bt-btif ( 2439): info:x10
,D/        ( 2439): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,D/BluetoothManagerService(  887): Message: 20
D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e08a25a:true
,I/ActivityManager(  887): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8286 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 8286): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2804d168:true
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8321 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8073:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8073/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bfc9667:true
,I/BTConnectionReceiver( 8321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothBondStateMachine( 2439): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2439): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2439): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2439): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2439): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2439): Removing bonded device:E0:DB:10:14:E2:C0
I/BluetoothBondStateMachine( 2439): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2439): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2712cc92
,D/BluetoothMetrics( 2439): btclass5a020c
,D/Checkin ( 2439): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2439): StableState(): Entering Off State
,W/bt-btif ( 2439): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2439): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2439): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Incoming connection initialized (thread ID: 792)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6470): Entering thread (ID: 792)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): onBytesRead: Read 66 bytes successfully (thread ID: 792)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Got valid identity from [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): onBytesWritten: 65 bytes successfully written (thread ID: 792)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): removeThreadFromList: Removing thread with ID 792
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Handshake thread disposed (thread ID: 792)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6470): Exiting thread (ID: 792)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnected: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6470): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/io.jxcore.node.ConnectionHelper( 6470): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 Note4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 6470): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6470): Entering thread (ID: 793)
I/jxcore-log( 6470): 2016-01-11T13:03:30.684Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6470): 
I/io.jxcore.node.IncomingSocketThread( 6470): Local host address: localhost/127.0.0.1, port: 56069
D/io.jxcore.node.IncomingSocketThread( 6470): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6470): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6470): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6470): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6470): Exiting thread (ID: 793)
,D/io.jxcore.node.StreamCopyingThread( 6470): Entering thread (ID: 794, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 6470): Entering thread (ID: 795, name: Receiver)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8355 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8321): Bluetooth Device Name: Note4-1
,I/ActivityManager(  887): Killing 8123:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8123/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8381 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8150:com.android.vending/u0a32 (adj 13): empty #7
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_8150/cgroup.procs: No such file or directory
,W/ResourcesManager( 8381): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  887): Message: 20
,D/BluetoothManagerService(  887): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@319459ac:true
,I/ActivityManager(  887): Killing 1969:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  887): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1684c675)
D/ConnectivityService(  887): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  887): Client connection lost with reason: 4
E/ConnectivityService(  887): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_1969/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/jxcore-log( 6470): 2016-01-11T13:03:31.520Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.529Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.534Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.541Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.544Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.556Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.564Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.568Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.573Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.620Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.625Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.632Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.668Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.716Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.723Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.759Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.768Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.775Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.782Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.819Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.826Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.833Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.869Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.909Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.915Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.948Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.955Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:31.988Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.028Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.061Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.099Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.103Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.108Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.114Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.148Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.188Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.213Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.256Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.288Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 6470): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Start timer timeout, starting now...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1443): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  887): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6470): 2016-01-11T13:03:32.609Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 6470): 
,E/bt-btm  ( 2439): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2439): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6470): 2016-01-11T13:03:32.620Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 6470): 
,W/bt-btif ( 2439): info:x10
,D/        ( 2439): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 8321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8321): Bluetooth Device Name: A5-1
,I/jxcore-log( 6470): 2016-01-11T13:03:32.947Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:32.978Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.035Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.040Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.045Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.050Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.055Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 6470): 
,I/BluetoothBondStateMachine( 2439): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2439): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2439): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
I/BluetoothBondStateMachine( 2439): Entering PendingCommandState State
,I/jxcore-log( 6470): 2016-01-11T13:03:33.186Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 6470): 
,I/BluetoothBondStateMachine( 2439): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2439): Removing bonded device:7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2439): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2439): StableState(): Entering Off State
,D/BluetoothMetrics( 2439): btclass5a020c
,W/bt-btif ( 2439): new conn_srvc id:26, app_id:255
W/bt-btif ( 2439): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2439): bta_dm_pm_ssr:2, lat:1200
,D/Checkin ( 2439): publish the event [tag = MOT_BT event name = PAIRING]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Incoming connection initialized (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Waiting for incoming connections...
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.282Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6470): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6470): Entering thread (ID: 796)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): onBytesRead: Read 63 bytes successfully (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): onBytesWritten: 65 bytes successfully written (thread ID: 796)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): removeThreadFromList: Removing thread with ID 796
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6470): Handshake thread disposed (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6470): Exiting thread (ID: 796)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 6470): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6470): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 6470): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6470): Entering thread (ID: 797)
,I/io.jxcore.node.IncomingSocketThread( 6470): Local host address: localhost/127.0.0.1, port: 56069
D/io.jxcore.node.IncomingSocketThread( 6470): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6470): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6470): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6470): startStreamCopyingThreads: OK
,I/jxcore-log( 6470): 2016-01-11T13:03:33.315Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6470): 
D/io.jxcore.node.IncomingSocketThread( 6470): Exiting thread (ID: 797)
,D/io.jxcore.node.StreamCopyingThread( 6470): Entering thread (ID: 798, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6470): Entering thread (ID: 799, name: Receiver)
,I/jxcore-log( 6470): 2016-01-11T13:03:33.329Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6470): 
,W/bt-btif ( 2439): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6470): Either failed to read from the output stream or write to the input stream (thread ID: 795, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6470): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6470): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 793
D/io.jxcore.node.IncomingSocketThread( 6470): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6470): doStop: Thread ID: 795
D/io.jxcore.node.IncomingSocketThread( 6470): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6470): doStop: Thread ID: 794
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6470): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6470): Exiting thread (ID: 795, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6470): Either failed to read from the output stream or write to the input stream (thread ID: 794, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6470): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6470): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6470): Exiting thread (ID: 794, name: Sender)
,I/jxcore-log( 6470): 2016-01-11T13:03:33.395Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6470): 
W/bt-rfcomm( 2439): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2439): RFCOMM_DisconnectInd LCID:0x42
,I/art     (  887): Explicit concurrent mark sweep GC freed 30682(1989KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.558ms total 139.578ms
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2439): tBTM_SEC_DEV:0xa6fa751c rs_disc_pending=0
,W/bt-btif ( 2439): bta_dm_check_av:0
W/bt-btif ( 2439): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6470): 2016-01-11T13:03:33.843Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:33.844Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  887):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,I/jxcore-log( 6470): 2016-01-11T13:03:34.504Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.509Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.513Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.517Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.522Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.526Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.531Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.537Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.540Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.591Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.594Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.598Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.644Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.694Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.762Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.769Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.778Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.819Z SendDataTCPServer.js: TCP/IP server has received 22770 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.882Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.889Z SendDataTCPServer.js: TCP/IP server has received 24750 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:34.901Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6470): 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6470): 2016-01-11T13:03:35.045Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.062Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.068Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.075Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.081Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.089Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.135Z SendDataTCPServer.js: TCP/IP server has received 32670 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.168Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.227Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.236Z SendDataTCPServer.js: TCP/IP server has received 36630 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.268Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.336Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.345Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.369Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.449Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.490Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.528Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.568Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.636Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.669Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.675Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.708Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.750Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.827Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.858Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.865Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.928Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:35.968Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 6470): 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/jxcore-log( 6470): 2016-01-11T13:03:36.009Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.049Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.053Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.090Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.128Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.245Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.418Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.448Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.474Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.479Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:36.518Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6470): 
,E/bt-btm  ( 2439): tBTM_SEC_DEV:0xa6fa735c rs_disc_pending=0
,W/bt-btif ( 2439): bta_dm_check_av:0
,W/bt-btif ( 2439): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2439): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6470): Either failed to read from the output stream or write to the input stream (thread ID: 799, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6470): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6470): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 797
,D/io.jxcore.node.IncomingSocketThread( 6470): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6470): doStop: Thread ID: 799
D/io.jxcore.node.IncomingSocketThread( 6470): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6470): doStop: Thread ID: 798
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6470): closeLocalSocketAndStreams: Closing the localhost socket...
,W/io.jxcore.node.StreamCopyingThread( 6470): Either failed to read from the output stream or write to the input stream (thread ID: 798, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6470): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6470): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 6470): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6470): Exiting thread (ID: 799, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6470): Exiting thread (ID: 798, name: Sender)
,I/jxcore-log( 6470): 2016-01-11T13:03:36.859Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6470): 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/btif_config_util( 2439): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): restart: Restarting...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139301 arg2=13 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,D/io.jxcore.node.ConnectionHelper( 6470): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6470): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 6470): 2016-01-11T13:03:38.851Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:38.851Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:38.852Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:38.852Z SendDataConnector.js: do connect now
I/jxcore-log( 6470): 
I/io.jxcore.node.ConnectionHelper( 6470): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 6470): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 6470): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6470): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2439): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139310 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,I/wpa_supplicant( 1443): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service discovery started successfully
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  887):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: S5-1 ee:1f:72:63:11:86
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,W/bt-rfcomm( 2439): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2439): RFCOMM_DisconnectInd LCID:0x44
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 7e
,W/bt-btm  ( 2439): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2439): tBTM_SEC_DEV:0xa6fa751c rs_disc_pending=2
E/bt-btm  ( 2439): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2439): bta_dm_check_av:0
,W/bt-btif ( 2439): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2439): onReceive
,I/BTConnectionReceiver( 8321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8321): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 2439): tBTM_SEC_DEV:0xa6fa735c rs_disc_pending=1
,W/bt-btif ( 2439): bta_dm_check_av:0
,W/bt-btif ( 2439): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,E/bt-btm  ( 2439): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2439): onReceive
,I/BTConnectionReceiver( 8321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8321): Bluetooth Device Name: A5-1
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6470): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 7 c0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  887):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  887):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 4488
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311744, SEQNUM=4534, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-1314, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  887): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6470): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6470): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 7 
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnectionTimeout: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 6470): 2016-01-11T13:03:53.861Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:53.862Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:03:53.862Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6470): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 8 c0
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 1443): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1443): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  887): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  887):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  887):  primary type: 10-0050F204-5
D/WifiP2pService(  887):  secondary type: null
D/WifiP2pService(  887):  wps: 392
D/WifiP2pService(  887):  grpcapab: 0
D/WifiP2pService(  887):  devcapab: 37
D/WifiP2pService(  887):  status: 3
D/WifiP2pService(  887):  wfdInfo: null
D/WifiP2pService(  887):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): restart: Restarting...
,D/WifiP2pService(  887): InactiveState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139307 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState clear service request
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,--------- beginning of crash
F/libc    ( 1443): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1443 (wpa_supplicant)
,I/libc    ( 1443): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  887): InactiveState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139301 arg2=20 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState add service request
,D/WifiP2pManager( 6470): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Service request added successfully
,E/QC-QMI  (  430): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  430): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  430): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  430): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  430): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,I/ActivityManager(  887): Waited long enough for: ServiceRecord{39b3c8d6 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/WifiP2pService(  887): InactiveState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=0 what=139310 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6470): Failed to start the service discovery, got error code: 3
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311744, SEQNUM=4536, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1338, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/jxcore-log( 6470): 2016-01-11T13:03:58.863Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:03:58.863Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/io.jxcore.node.ConnectionHelper( 6470): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6470): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6470): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 6470): 2016-01-11T13:04:03.865Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:04:03.866Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:04:03.866Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:04:03.866Z SendDataConnector.js: do connect now
I/jxcore-log( 6470): 
I/io.jxcore.node.ConnectionHelper( 6470): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6470): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 6470): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 6470): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 802)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6470): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2439): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,W/bt-sdp  ( 2439): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
,E/bt-btif ( 2439): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2439): invalid rfc slot id: 9
,W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2439): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6470): onConnectionTimeout: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 6470): 2016-01-11T13:04:18.876Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:04:18.876Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 6470): 
I/jxcore-log( 6470): 2016-01-11T13:04:18.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6470): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/Tethering(  887): InitialState.processMessage what=4
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
,D/Tethering(  887):  5
,D/Tethering(  887):  7
D/Tethering(  887):  0
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,I/jxcore-log( 6470): 2016-01-11T13:04:23.877Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,I/jxcore-log( 6470): 2016-01-11T13:04:23.878Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6470): 
,E/WifiStateMachine(  887): Connection lost, restart supplicant
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: RESTARTING
,D/WifiP2pService(  887): InactiveState{ when=0 what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  887): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  887): failed to set BSSID: any
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
,D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
,V/NativeCrypto( 1779): Read error: ssl=0xb8cb76e8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1779): SSL shutdown failed: ssl=0xb8cb76e8: I/O error during system call, Broken pipe
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
W/Settings( 1779): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8464 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  887): connected time updated 538453
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
D/WifiScanningService(  887): SCAN_AVAILABLE : 1
D/RttService(  887): SCAN_AVAILABLE : 1
D/WifiScanningService(  887): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  887): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): [1,452,517,465,754 ms] noteScanEnd no scan source
D/WifiP2pService(  887): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): discovery change broadcast false
D/WifiP2pService(  887): P2pDisablingState
D/WifiP2pService(  887): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): p2p socket connection lost
D/WifiP2pService(  887): P2pDisabledState
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): stop: Stopping services
D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139298 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-1ms what=139298 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): stop: Stopping P2P device discovery...
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139268 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6470): setState: NOT_INITIALIZED
D/WifiP2pService(  887): DefaultState{ when=0 what=139268 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6470): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6470): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 6470): Shutting down VM
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=139307 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 8464): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8464): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8464): MmsConfig.loadMmsSettings
I/Babel_SMS( 8464): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8464): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8464): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8464): MmsConfig.loadFromResources
E/Babel_SMS( 8464): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8464): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8464): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8464): startup - clean
,I/Babel   ( 8464): deleted: false for 0
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
,W/VideoCapabilities( 8464): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8464): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8464): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8464): Unsupported profile 4 for video/mp4v-es
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,W/VideoCapabilities( 8464): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8464): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8464): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8464): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8464): onServiceConnected
W/Babel   ( 8464): Attempted to change video mute state without an active call.
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 444 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 17
D/TCMD    (  472): Listening for incoming client connection request
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  887): MasterInitialState.processMessage what=3
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8510 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2552): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2552): [debug] > CusSM.onRadioDown
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,I/MusicStore( 8510): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8510): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8510): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8510): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8510): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8510): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8510): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8510): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8510): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8510): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8510): GMSCore installation verified
,I/ConfigStore( 8510): Config Database version: 1
,I/MediaRouter( 8510): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8510): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8550 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8510): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8510): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8569 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 24.226ms
,I/ActivityManager(  887): Killing 8209:com.google.android.deskclock/u0a55 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 483us total 21.486ms
,W/ResourcesManager( 8569): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8569): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 20.286ms
,V/Mms     ( 8550): mnc/mcc: 
V/Mms     ( 8550): tag: int value: recipientLimit - 20
V/Mms     ( 8550): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8550): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8550): tag: int value: maxSubjectLength - 80
V/Mms     ( 8550): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8550): tag: bool value: enableGroupMms - false
V/Mms     ( 8550):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 8569): VM with version 2.1.0 has multidex support
I/MultiDex( 8569): install
I/MultiDex( 8569): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  887): failed to open /acct/uid_10055/pid_8209/cgroup.procs: No such file or directory
,W/ResourcesManager( 8550): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8601 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8355:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_8355/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8601): Register our PhoneStateListener
,V/JNIHelp ( 8569): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MobileConnectivityChangeReceiver( 8601): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 8601): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ActivityThread( 8569): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8569): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@534c195: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8569): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  887): Killing 8381:com.android.settings/1000 (adj 15): empty #7
,D/NativeLibraryUtils( 8569): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  887): failed to open /acct/uid_1000/pid_8381/cgroup.procs: No such file or directory
,I/iu.SyncManager( 8569): SYNC; picasa accounts
,D/NetworkLogImpl( 8569): Loaded NetworkSpeedPredictor
,I/ActivityManager(  887): Killing 8321:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_8321/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8637 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8658 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 8464): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 8510:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8510/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 8658): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8658):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8658):   adb logcat -s GAv4
W/ContextImpl( 8658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8658): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8658): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8658): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/WifiP2pService(  887): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  887): Explicit concurrent mark sweep GC freed 30479(1741KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.467ms total 117.580ms
,I/WebViewFactory( 8658): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8658): Time to load native libraries: 1 ms (timestamps 7036-7037)
I/LibraryLoader( 8658): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8658): Binding Chromium to main looper Looper (main, tid 1) {de578c6}
,I/LibraryLoader( 8658): Expected native library version number "",actual native library version number ""
I/chromium( 8658): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
,D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,I/BrowserStartupController( 8658): Initializing chromium process, singleProcess=true
,W/art     ( 8658): Attempt to remove local handle scope entry from IRT, ignoring
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
E/SysUtils( 8658): ApplicationContext is null in ApplicationStatus
D/Tethering(  887): InitialState.processMessage what=4
D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
,D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  472): NL - Read 1008 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/QsoftapCmd(  289): Got softap fwreload command we are passing on
,D/SoftapController(  289): Softap fwReload - Ok
,D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring down wlan0
D/CommandListener(  289): Clearing all IP addresses on wlan0
,W/chromium( 8658): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8658): Local Branch: 
I/Adreno-EGL( 8658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8658): Local Patches: NONE
I/Adreno-EGL( 8658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/wpa_supplicant( 8722): Successfully initialized wpa_supplicant
I/wpa_supplicant( 8722): Long line in configuration file truncated
,I/wpa_supplicant( 8722): rfkill: Cannot open RFKILL control device
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
W/AudioManagerAndroid( 8658): Requires BLUETOOTH permission
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/NSApplication( 8658): Starting up...
,E/WifiStateMachine(  887): setWifiState: enabling
E/WifiStateMachine(  887): Supplicant start successful
,D/WifiMonitor(  887): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/libmdmdetect( 8722): ESOC framework not supported
E/Diag_Lib( 8722):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
E/wpa_supplicant( 8722): baseband property is set to [msm]
I/libmdmdetect( 8722): ESOC framework not supported
E/wpa_supplicant( 8722):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8722): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8722): card_info[i].card_state: 0x0
E/wpa_supplicant( 8722): card_info[i].error_code: 0x0
E/wpa_supplicant( 8722): SIM/USIM not ready
E/wpa_supplicant( 8722): Error while reading SIM card status
I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8737 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8550:com.android.mms/u0a23 (adj 15): empty #7
E/wpa_supplicant( 8722): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 8722): card_info[i].card_state: 0x0
E/wpa_supplicant( 8722): card_info[i].error_code: 0x0
E/wpa_supplicant( 8722): SIM/USIM not ready
I/wpa_supplicant( 8722): eap_proxy: Card not ready
,I/wpa_supplicant( 8722): Long line in configuration file truncated
I/wpa_supplicant( 8722): rfkill: Cannot open RFKILL control device
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8550/cgroup.procs: No such file or directory
,E/wpa_supplicant( 8722): baseband property is set to [msm]
,I/libmdmdetect( 8722): ESOC framework not supported
,E/wpa_supplicant( 8722):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8722): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8722): card_info[i].card_state: 0x0
E/wpa_supplicant( 8722): card_info[i].error_code: 0x0
E/wpa_supplicant( 8722): SIM/USIM not ready
E/wpa_supplicant( 8722): Error while reading SIM card status
,E/wpa_supplicant( 8722): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 8722): card_info[i].card_state: 0x0
E/wpa_supplicant( 8722): card_info[i].error_code: 0x0
E/wpa_supplicant( 8722): SIM/USIM not ready
I/wpa_supplicant( 8722): eap_proxy: Card not ready
,E/WifiStateMachine(  887): Supplicant connection established
,E/WifiStateMachine(  887): setWifiState: enabled
D/WifiConfigStore(  887): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  887):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  887):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  887): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  887): Setting external_sim to 1
W/Settings( 8464): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  887): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa2e8689c
D/wifi    (  887): halHandle = 0x0, mVM = 0xb8821310, mCls = 0x1a76
I/WifiNative-HAL(  887): Could not start hal
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  887): do suspend true
,D/WifiP2pService(  887): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  887): SCAN_AVAILABLE : 3
,D/RttService(  887): SCAN_AVAILABLE : 3
D/WifiScanningService(  887): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  887): startHal
E/wifi    (  887): getStaticLongField sWifiHalHandle 0xa49989cc
D/wifi    (  887): halHandle = 0x0, mVM = 0xb8821310, mCls = 0x1a6e
I/WifiNative-HAL(  887): Could not start hal
E/WifiScanningService(  887): could not start HAL
,D/RttService(  887): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring up p2p0
,D/WifiMonitor(  887): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  887): P2pEnablingState
,D/WifiP2pService(  887): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2p socket connection successful
D/WifiP2pService(  887): P2pEnabledState
D/WifiP2pService(  887): sending p2p connection changed broadcast
E/WifiStateMachine(  887): set country code US
,D/WifiNative-HAL(  887): p2pGetDeviceAddress
,E/WifiStateMachine(  887): set frequency band 2
D/WifiNative-HAL(  887): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  887): DeviceAddress: 44:80:eb:7b:5a:07
,I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiP2pService(  887): MCC mode enabled 0
,D/WifiP2pService(  887): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  887): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  887): InactiveState
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/WifiP2pService(  887): InactiveState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info0x
D/WifiP2pService(  887): P2pEnabledState{ when=-9ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  887): InactiveState{ when=-9ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-13ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8759 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8601:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 1
,I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): wifi_connect_to_supplicant, current pid is = 292
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
D/MDMCTBK (  292): wifi_ctrl_recv: Exiting
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  292): wifi_close_sockets: Exit
E/MDMCTBK (  292): Attach monitor thread
,I/MDMCTBK (  292): createWifiMonitorThread: Started the wifi monitor thread -1221795752
D/MDMCTBK (  292): wifi_wait_on_socket: Enter monitor thread
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8601/cgroup.procs: No such file or directory
,W/ResourcesManager( 8759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8786 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8805 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8464:com.google.android.talk/u0a70 (adj 15): empty #7
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/ActivityManager(  887): Killing 8637:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 8786): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8464/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8637/cgroup.procs: No such file or directory
,I/MusicStore( 8805): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8805): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8805): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8805): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8805): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8805): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8805): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8805): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8805): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8805): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8805): GMSCore installation verified
,I/ConfigStore( 8805): Config Database version: 1
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledStateupdate channel list
,I/MediaRouter( 8805): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8805): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8845 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8805): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8805): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 8658:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,V/Mms     ( 8845): mnc/mcc: 
,V/Mms     ( 8845): tag: int value: recipientLimit - 20
,V/Mms     ( 8845): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8845): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8845): tag: int value: maxSubjectLength - 80
V/Mms     ( 8845): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8845): tag: bool value: enableGroupMms - false
V/Mms     ( 8845):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8658/cgroup.procs: No such file or directory
,W/ResourcesManager( 8845): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8879 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8737:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_8737/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8879): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8879): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8879): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 8759:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_8759/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8899 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8922 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8786:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.009ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.675ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.511ms
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_8786/cgroup.procs: No such file or directory
,W/ResourcesManager( 8922): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8922): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8922): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8922): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8922): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8922): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8922): MmsConfig.loadFromResources
E/Babel_SMS( 8922): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8922): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8922): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8922): startup - clean
,I/Babel   ( 8922): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8953 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8922): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8922): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8922): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8922): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8922): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8922): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8922): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8922): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8922): onServiceConnected
W/Babel   ( 8922): Attempted to change video mute state without an active call.
I/Babel   ( 8922): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 8805:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 8953): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8953):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8953):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_8805/cgroup.procs: No such file or directory
,W/GAv4    ( 8953): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8953): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8953): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/WebViewFactory( 8953): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [29ms]
,I/LibraryLoader( 8953): Time to load native libraries: 2 ms (timestamps 505-507)
,I/LibraryLoader( 8953): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8953): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader( 8953): Expected native library version number "",actual native library version number ""
I/chromium( 8953): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8953): Initializing chromium process, singleProcess=true
,W/art     ( 8953): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8953): ApplicationContext is null in ApplicationStatus
,W/chromium( 8953): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 8953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8953): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8953): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8953): Local Branch: 
I/Adreno-EGL( 8953): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8953): Local Patches: NONE
I/Adreno-EGL( 8953): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 8953): Starting up...
,W/AudioManagerAndroid( 8953): Requires BLUETOOTH permission
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9023 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8845:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  887): Explicit concurrent mark sweep GC freed 22775(1152KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.656ms total 135.792ms
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_8845/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9052 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8879:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_8879/cgroup.procs: No such file or directory
,W/ResourcesManager( 9052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9078 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 8922:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9078): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  887): Killing 8899:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_8922/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_8899/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2552): onServiceConnected()
D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
,E/MDM     ( 1779): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 8569): Restart initialization of location
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9112 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 8569): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8569): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/IcingInternalCorpora( 8569): getNumBytesRead when not calculated.
,W/GCoreFlp( 1779): No location to return for getLastLocation()
W/FusedLocationProvider( 1779): location=null
,V/AlarmManager(  887): done {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [1420ms]
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9144 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 9144): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  292): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  887): [1,452,517,476,076 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,I/Babel_SMS( 9144): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9144): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9144): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9144): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9144): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9144): MmsConfig.loadFromResources
E/Babel_SMS( 9144): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9144): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9144): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9144): startup - clean
,I/Babel   ( 9144): deleted: false for 0
,W/VideoCapabilities( 9144): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9144): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9144): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9144): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9144): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9144): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9144): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9144): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 8953:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_8953/cgroup.procs: No such file or directory
,I/vclib   ( 9144): onServiceConnected
W/Babel   ( 9144): Attempted to change video mute state without an active call.
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 c
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 8722): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 8722): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiStateMachine(  887): [1,452,517,476,710 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiConfigStore(  887):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 192 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 8722): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 8722): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
E/MDMCTBK (  292): Not connected to wpa_supplicant - control or monitor connection not available.
E/MDMCTBK (  292): MdmCutbackHndler, error getting ASSOCFREQ, -1
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
,I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221780064
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
E/WifiStateMachine(  887): Network connection established
E/MDMCTBK (  292): Not connected to wpa_supplicant - control or monitor connection not available.
E/MDMCTBK (  292): MdmCutbackHndler, error setting TXPOWER, -1
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
,E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
E/WifiStateMachine(  887): Start Dhcp Watchdog 3
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend false
,E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 9193): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9193): version 5.5.6 starting
,E/DHCPCD  ( 9193): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 9193): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9193): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 9193): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 9193): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 9193): wlan0: sending REQUEST (xid 0x336a2704), next in 3.71 seconds
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 ee
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
,I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/DHCPCD  ( 9193): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9193): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9193): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 9193): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 9193): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9193): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9193): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
D/TCMD    (  472): Listening for incoming client connection request
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 102
,I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  887): Setting Dns servers for network 102 to [/192.168.1.1]
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524295
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 13:04:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452517478932], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452517478782]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  887): Killing 9023:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_9023/cgroup.procs: No such file or directory
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): now: 627214 ,futureTime: 9223372036854775807
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): now: 627214 ,futureTime: 9223372036854775807
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): now: 627215 ,futureTime: 9223372036854775807
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9265 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1477): now: 627274 ,futureTime: 86474097
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86474097 Current Time: 627274
,D/OtaApp  ( 2552): [debug] > PollingManagerService, now: 627286 ,futureTime: 11910134
D/OtaApp  ( 2552): [debug] > Polling alarm set to expire at: 11910134 Current Time: 627287
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2552): set mOutstandingReq to true.
I/ Nonce  ( 2552):  Nonce getNonce 
I/ Nonce  ( 2552):  Nonce Request 
I/ Nonce  ( 2552):  Nonce execute Request 
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 6146(305KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 619us total 27.507ms
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore( 9265): Database version: 120
,I/art     (  887): Explicit concurrent mark sweep GC freed 29741(1430KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.472ms total 115.157ms
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2552): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/MMApiWebService( 2552): generating token using payload instead of using session token
I/OtaApp  ( 2552): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/ Nonce  ( 2552):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2552): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9265): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9265): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9265): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9265): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9265): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9265): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9265): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9265): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9265): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 9265): GMSCore installation verified
,I/ConfigStore( 9265): Config Database version: 1
,I/MediaRouter( 9265): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9265): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9265): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9265): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9313 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9265): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9265): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 9052:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_9052/cgroup.procs: No such file or directory
,V/Mms     ( 9313): mnc/mcc: 
V/Mms     ( 9313): tag: int value: recipientLimit - 20
V/Mms     ( 9313): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9313): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9313): tag: int value: maxSubjectLength - 80
V/Mms     ( 9313): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9313): tag: bool value: enableGroupMms - false
V/Mms     ( 9313):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 9313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9339 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9078:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_9078/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9339): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9339): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9339): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 9112:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_9112/cgroup.procs: No such file or directory
,I/CheckinService( 8569): Checkin interval check for package: unspecified last checkin: 1452517108351 min interval config: 0 actual interval: 374023
,I/CheckinService( 8569): Disabling old GoogleServicesFramework version
,I/iu.Environment( 8569): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 8569): num queued entries: 0
I/iu.UploadsManager( 8569): num updated entries: 0
I/iu.SyncManager( 8569): NEXT; no task
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9365 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 8569): Checking schedule, now: 1452517482473 next: 1452517138330
I/CheckinService( 8569): active receiver: enabled
,I/CheckinService( 8569): Preparing to send checkin request
,I/EventLogService( 8569): Accumulating logs since 1452517104375
,I/ Nonce  ( 2552):  Nonce Reponse 
D/        ( 2552): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"c8fc8b26-a505-4850-9eac-75a6dc770d3d"}
D/MMApiWSBase( 2552): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2552):  Nonce Handle Reponse 
D/MMApiProvisionService( 2552): mOutstandingReq set to false
,I/CheckinRequestBuilder( 8569): Checkin reason type: 8 attempt count: 1
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread( 8569): Failed to find provider info for com.google.android.wearable.settings
,D/MMApiProvisionService( 2552):  pTime 1452467391223 sExp 172742 cTime 1452517482763 tTime 1452640133223
D/MMApiProvisionService( 2552):  No login Required 
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9393 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.992ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.469ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 21.149ms
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9421 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/Babel   ( 9144): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9393): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9393):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9393):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 9421): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9421): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 9393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9393): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9393): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9393): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9393): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 9421): VM with version 2.1.0 has multidex support
,I/MultiDex( 9421): install
I/MultiDex( 9421): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 9421): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9421): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9421): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9421): Installed default security provider GmsCore_OpenSSL
,I/art     ( 9421): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9421): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/DataUsage( 2552): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  887): Explicit concurrent mark sweep GC freed 9707(479KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.659ms total 121.304ms
,D/NativeLibraryUtils( 9421): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/bt-sdp  ( 2439): SDP - Rcvd conn cnf with error: 0x22  CID 0x46
E/bt-btif ( 2439): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 6470): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2439): invalid rfc slot id: 10
D/BTIF_SOCK( 2439): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb55d9960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb758b6e0, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7659798, idLength=0xb54d9730
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
,D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  294): PrepareKeyRequest: nonce=2061495047
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7510430
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7617390, signature_length=3041761044
,I/WebViewFactory( 9393): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9393): Time to load native libraries: 1 ms (timestamps 9402-9403)
I/LibraryLoader( 9393): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9393): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 9393): Expected native library version number "",actual native library version number ""
,I/chromium( 9393): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9393): Initializing chromium process, singleProcess=true
W/art     ( 9393): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9393): ApplicationContext is null in ApplicationStatus
,W/chromium( 9393): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 9393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9393): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9393): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9393): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9393): Local Branch: 
I/Adreno-EGL( 9393): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9393): Local Patches: NONE
I/Adreno-EGL( 9393): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 9393): Requires BLUETOOTH permission
I/NSApplication( 9393): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9482 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9265:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_9265/cgroup.procs: No such file or directory
,I/dex2oat ( 9502): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 9502): dex2oat took 76.218ms (threads: 4)
,I/Adreno-EGL( 9421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9421): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9421): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9421): Local Branch: 
I/Adreno-EGL( 9421): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9421): Local Patches: NONE
I/Adreno-EGL( 9421): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9510 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9313:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 9421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9421): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9421): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9421): Local Branch: 
I/Adreno-EGL( 9421): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9421): Local Patches: NONE
I/Adreno-EGL( 9421): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_9313/cgroup.procs: No such file or directory
,W/ResourcesManager( 9510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9531 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/ActivityManager(  887): Killing 9365:com.google.android.apps.photos/u0a88 (adj 15): empty #7
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbec274e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb758a508, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597d8, idLength=0xb1414730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
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
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3295066013
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb756df68
D/DrmWidevineDash(  294): message_length=1626, signature=0xb761a9d0, signature_length=2973845268
,I/ActivityManager(  887): Killing 9339:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 9531): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_9365/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_9339/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2552): onServiceConnected()
D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2552): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2552): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2552): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2552): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9564 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 9421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9421): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9421): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9421): Local Branch: 
I/Adreno-EGL( 9421): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9421): Local Patches: NONE
I/Adreno-EGL( 9421): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,I/Adreno-EGL( 9421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9421): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9421): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9421): Local Branch: 
I/Adreno-EGL( 9421): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9421): Local Patches: NONE
I/Adreno-EGL( 9421): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 8569): Classify the device as Phone.
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
D/LocationInitializer( 8569): Restart initialization of location
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1779): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  887): Killing 9144:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_9144/cgroup.procs: No such file or directory
,W/GCoreFlp( 1779): No location to return for getLastLocation()
,W/FusedLocationProvider( 1779): location=null
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9593 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 9593): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9593): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9593): MmsConfig.loadMmsSettings
I/Babel_SMS( 9593): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9593): MmsConfig.loadFromDatabase
,I/CheckinTask( 8569): Sending checkin request (9506 bytes)
,E/Babel_SMS( 9593): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9593): MmsConfig.loadFromResources
,E/Babel_SMS( 9593): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9593): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9593): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 9593): startup - clean
,I/Babel   ( 9593): deleted: false for 0
,W/VideoCapabilities( 9593): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9593): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9593): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9593): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9593): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9593): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9593): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9593): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Killing 9393:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  292): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
,I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_9393/cgroup.procs: No such file or directory
,I/vclib   ( 9593): onServiceConnected
,W/Babel   ( 9593): Attempted to change video mute state without an active call.
,I/ActivityManager(  887): Killing 9482:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_9482/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9630 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c6c0036
,I/GCoreNlp( 1779): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1575): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9668 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9687 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9510:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_9510/cgroup.procs: No such file or directory
,W/asset   ( 9687): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9687): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9687): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9687): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 9593): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9593): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9593): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PackageBroadcastService( 8569): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 9630): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 8569): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9717 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 9593): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9593): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 9630): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
,I/art     (  887): Explicit concurrent mark sweep GC freed 17932(895KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.505ms total 117.231ms
,I/ActivityManager(  887): Killing 9564:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 9717): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_9564/cgroup.procs: No such file or directory
,I/Icing   ( 8569): Storage manager: low false usage 1.72MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9756 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.397ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 19.814ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.408ms
,I/ActivityManager(  887): Killing 9421:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_9421/cgroup.procs: No such file or directory
,I/Icing   ( 8569): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 6337): Explicit concurrent mark sweep GC freed 2676(104KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 337us total 24.638ms
,D/Finsky  ( 9756): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 8569): Internal init done: storage state 0
,I/Icing   ( 8569): Post-init done
,I/Icing   ( 8569): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 9756): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9756): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9756): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/SQLiteConnectionPool( 8569): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Finsky  ( 9756): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 9756): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 9756): Skipping gmscore version check
,D/Finsky  ( 9756): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 9756): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Killing 9668:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_9668/cgroup.procs: No such file or directory
,D/TCMD    (  472): NL - Read 1004 bytes from update socket.
,D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
,I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  887): InitialState.processMessage what=4
,E/WifiStateMachine(  887): NETWORK_DISCONNECTION_EVENT in connected state BSSID=c0:ff:d4:d3:aa:48 RSSI=-127 freq=-1 was debouncing=false reason=0 ajst=0
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  887): ApnList is empty for checkDunConfigured()
D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
D/Tethering(  887):  0
E/WifiStateMachine(  887): Missed CTRL-EVENT-DISCONNECTED, disconnect
E/WifiStateMachine(  887): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  887): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  887): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  887): do suspend true
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  472): NL - Read 60 bytes from update socket.
,D/TCMD    (  472): NL - ignore NL message, type = 21
D/TCMD    (  472): Listening for incoming client connection request
,V/NativeCrypto( 1779): Read error: ssl=0xb8afc368: I/O error during system call, Connection timed out
,V/NativeCrypto( 1779): SSL shutdown failed: ssl=0xb8afc368: I/O error during system call, Broken pipe
,V/NativeCrypto( 8569): Read error: ssl=0xb8c47c50: I/O error during system call, Connection timed out
,E/CheckinTask( 8569): SSL error, attempting time correction: javax.net.ssl.SSLException: Read error: ssl=0xb8c47c50: I/O error during system call, Connection timed out
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  887): setDetailed state send new extra info<unknown ssid>
I/AuthdNetTimeProvider( 8569): Attempting to get network time from https://android.clients.google.com/checkin
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  887): connected time updated 554703
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  887): WifiStateMachine: Leaving Connected state
D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  887): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  887): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  887): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  887): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
E/CheckinTask( 8569): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  887): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  887): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/CheckinService( 8569): Checking schedule, now: 1452517494529 next: 1452517504516
I/CheckinService( 8569): active receiver: disabled
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  887): send {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
V/AlarmManager(  887): done {3382071e, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10ms]
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9824 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9824): Register our PhoneStateListener
,I/ActivityManager(  887): Killing 9687:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_9687/cgroup.procs: No such file or directory
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 8569): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 8569): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 8569): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 9630:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_9630/cgroup.procs: No such file or directory
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  292): , Wifi = 0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
,I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
,I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311942, SEQNUM=4659, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1531, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9860 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2552): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2552): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2552): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2552): [debug] > CusSM.onRadioDown
,I/MusicStore( 9860): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9860): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9860): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9860): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9860): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9860): GMSCore installation verified
,I/ConfigStore( 9860): Config Database version: 1
,I/MediaRouter( 9860): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9860): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9908 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9860): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9860): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 9531:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_9531/cgroup.procs: No such file or directory
,V/Mms     ( 9908): mnc/mcc: 
,V/Mms     ( 9908): tag: int value: recipientLimit - 20
V/Mms     ( 9908): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 9908): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9908): tag: int value: maxSubjectLength - 80
V/Mms     ( 9908): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9908): tag: bool value: enableGroupMms - false
,V/Mms     ( 9908):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/MobileConnectivityChangeReceiver( 9824): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9824): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ResourcesManager( 9908): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/iu.Environment( 8569): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 8569): num queued entries: 0
,I/iu.UploadsManager( 8569): num updated entries: 0
,I/iu.SyncManager( 8569): NEXT; no task
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9940 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9717:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_9717/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 9756:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_9756/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9958 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 9593): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 9860:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_9860/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 9958): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9958):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9958):   adb logcat -s GAv4
,W/ContextImpl( 9958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 9958): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 9958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9958): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9958): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9958): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9958): Time to load native libraries: 2 ms (timestamps 5211-5213)
I/LibraryLoader( 9958): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9958): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader( 9958): Expected native library version number "",actual native library version number ""
I/chromium( 9958): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9958): Initializing chromium process, singleProcess=true
W/art     ( 9958): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9958): ApplicationContext is null in ApplicationStatus
,W/chromium( 9958): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9958): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9958): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9958): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9958): Local Branch: 
I/Adreno-EGL( 9958): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9958): Local Patches: NONE
I/Adreno-EGL( 9958): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9958): Requires BLUETOOTH permission
,I/art     (  887): Explicit concurrent mark sweep GC freed 26943(1410KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.877ms total 118.648ms
,I/NSApplication( 9958): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=10025 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9908:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_9908/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=10044 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9824:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_9824/cgroup.procs: No such file or directory
,W/ResourcesManager(10044): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=10064 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 9593:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  887): Killing 9940:com.google.android.apps.photos/u0a88 (adj 15): empty #8
I/ContactLocale(10064): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_9593/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_9940/cgroup.procs: No such file or directory
,I/art     ( 2552): Explicit concurrent mark sweep GC freed 33504(1919KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 11MB/19MB, paused 1.138ms total 64.154ms
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 2552): onServiceConnected()
D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
,I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=10090 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,I/MusicStore(10090): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10090): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager(10090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10090): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (10090): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10090): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10090): GMSCore installation verified
,I/ConfigStore(10090): Config Database version: 1
,I/MediaRouter(10090): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback(10090): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=10118 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory(10090): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory(10090): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  887): Killing 9958:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_9958/cgroup.procs: No such file or directory
,V/Mms     (10118): mnc/mcc: 
,V/Mms     (10118): tag: int value: recipientLimit - 20
V/Mms     (10118): tag: int value: smsToMmsTextThreshold - 6
V/Mms     (10118): tag: int value: emergencySmsTimeout - 30
V/Mms     (10118): tag: int value: maxSubjectLength - 80
V/Mms     (10118): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     (10118): tag: bool value: enableGroupMms - false
V/Mms     (10118):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager(10118): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 1546): Explicit concurrent mark sweep GC freed 26309(1252KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 737us total 52.749ms
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=10144 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.172ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.058ms
I/ActivityManager(  887): Killing 10025:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.111ms
,D/PhoneMonitor(10144): Register our PhoneStateListener
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_10025/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver(10144): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver(10144): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  887): Killing 10044:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_10044/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=10170 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=10193 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10064:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_10064/cgroup.procs: No such file or directory
,W/ResourcesManager(10193): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS(10193): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS(10193): MmsConfig.loadMmsSettings
,I/Babel_SMS(10193): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS(10193): MmsConfig.loadFromDatabase
,E/Babel_SMS(10193): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS(10193): MmsConfig.loadFromResources
,E/Babel_SMS(10193): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS(10193): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings(10193): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash(10193): startup - clean
,I/Babel   (10193): deleted: false for 0
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=10224 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities(10193): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities(10193): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities(10193): Unsupported mime video/mpeg2
,I/VideoCapabilities(10193): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities(10193): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10193): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10193): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10193): Unrecognized profile 2130706433 for video/avc
,I/vclib   (10193): onServiceConnected
,W/Babel   (10193): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/Babel   (10193): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  887): Killing 10090:com.google.android.music:main/u0a80 (adj 15): empty #7
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    (10224): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    (10224):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10224):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10224): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_10090/cgroup.procs: No such file or directory
,W/GAv4    (10224): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10224): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10224): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinService( 8569): Done disabling old GoogleServicesFramework version
,I/WebViewFactory(10224): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader(10224): Time to load native libraries: 2 ms (timestamps 8464-8466)
,I/LibraryLoader(10224): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10224): Binding Chromium to main looper Looper (main, tid 1) {38f40ea1}
,I/LibraryLoader(10224): Expected native library version number "",actual native library version number ""
,I/chromium(10224): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10224): Initializing chromium process, singleProcess=true
,W/art     (10224): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils(10224): ApplicationContext is null in ApplicationStatus
,W/chromium(10224): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  (10224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  (10224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL(10224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10224): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10224): Build Date: 10/28/14 Tue
I/Adreno-EGL(10224): Local Branch: 
I/Adreno-EGL(10224): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10224): Local Patches: NONE
I/Adreno-EGL(10224): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid(10224): Requires BLUETOOTH permission
,I/NSApplication(10224): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=10294 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10118:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_10118/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=10313 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10144:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_10144/cgroup.procs: No such file or directory
,I/art     (  887): Explicit concurrent mark sweep GC freed 11342(593KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.853ms total 123.253ms
,W/ResourcesManager(10313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=10333 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10193:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale(10333): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_10193/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 10224:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_10224/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1546): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  292): NetlinkHandler, interfaceAdded
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
E/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  292): , Wifi = 0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=10371 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2777ffea
,I/GCoreNlp( 1779): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1575): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10409 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=10426 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  887): Killing 8569:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  887): Client connection lost with reason: 4
,I/ActivityManager(  887): Killing 10294:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_8569/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_10294/cgroup.procs: No such file or directory
,W/ResourcesManager(10426): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS(10426): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS(10426): MmsConfig.loadMmsSettings
,I/Babel_SMS(10426): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS(10426): MmsConfig.loadFromDatabase
,E/Babel_SMS(10426): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS(10426): MmsConfig.loadFromResources
E/Babel_SMS(10426): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS(10426): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings(10426): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash(10426): startup - clean
,I/Babel   (10426): deleted: false for 0
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10469 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities(10426): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities(10426): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities(10426): Unsupported mime video/mpeg2
,W/asset   (10469): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10469): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(10469): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities(10426): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities(10426): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10426): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10426): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10426): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  887): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=10493 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.402ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 18.880ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.278ms
,W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/UpdateIcingCorporaServi(10371): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager(10493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex(10493): VM with version 2.1.0 has multidex support
I/MultiDex(10493): install
I/MultiDex(10493): VM has multidex support, MultiDex support library is disabled.
,I/vclib   (10426): onServiceConnected
W/Babel   (10426): Attempted to change video mute state without an active call.
,W/ResourcesManager(10426): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10426): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10517 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi(10371): UpdateCorporaTask done [took 221 ms] updated apps [took 221 ms] 
,V/JNIHelp (10493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     (10426): Suspending all threads took: 8.242ms
,V/JNIHelp (10426): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10493): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (10493): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@534c195: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10493): Installed default security provider GmsCore_OpenSSL
,D/PackageBroadcastService(10493): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService(10493): Null package name or gms related package.  Ignoreing.
,W/System  (10426): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10426): Installed default security provider GmsCore_OpenSSL
,D/Finsky  (10517): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/art     (10493): Suspending all threads took: 16.870ms
,D/Finsky  (10517): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10517): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing   (10493): Storage manager: low false usage 1.72MB avail 3.12GB capacity 4.85GB
,W/Settings(10517): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/NativeLibraryUtils(10493): Install completed successfully. count=14 extracted=0
,W/art     (10493): Suspending all threads took: 19.468ms
,I/art     (10493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     (10493): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/Finsky  (10517): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  (10517): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     (10517): Skipping gmscore version check
,I/ActivityManager(  887): Killing 10170:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_10170/cgroup.procs: No such file or directory
,D/Finsky  (10517): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/art     (  887): Explicit concurrent mark sweep GC freed 16202(828KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.483ms total 123.238ms
,D/Finsky  (10517): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
I/ActivityManager(  887): Killing 10409:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_10409/cgroup.procs: No such file or directory
D/LocationInitializer(10493): Restart initialization of location
,E/MDM     ( 1779): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/IcingInternalCorpora(10493): getNumBytesRead when not calculated.
,I/art     ( 1779): Explicit concurrent mark sweep GC freed 67446(3MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 13MB/22MB, paused 867us total 86.557ms
,W/GCoreFlp( 1779): No location to return for getLastLocation()
,W/FusedLocationProvider( 1779): location=null
,E/DataBuffer( 1779): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@168789f4)
,E/DataBuffer( 1779): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a76451d)
,E/DataBuffer( 1779): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ed87392)
,E/DataBuffer( 1779): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a4be163)
E/DataBuffer( 1779): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@268d5160)
,I/Icing   (10493): updateResources: need to parse f{com.google.android.gms}
,I/Icing   (10493): Internal init done: storage state 0
,I/Icing   (10493): Post-init done
,I/Icing   (10493): updateResources: need to parse f{com.google.android.gms}
,I/Icing   (10493): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   (10493): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   (10493): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  887): Killing 10469:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_10469/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 10426:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_10426/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2439): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
,E/bt-btif ( 2439): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2439): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Maximum number of allowed retries (0) reached, giving up... (thread ID: 800)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Exiting thread (thread ID: 800)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): shutdown (thread ID: 800)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311195, SEQNUM=4691, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-1628, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,W/bt-sdp  ( 2439): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
,E/bt-btif ( 2439): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2439): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 802)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Maximum number of allowed retries (0) reached, giving up... (thread ID: 802)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6470): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): Exiting thread (thread ID: 802)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6470): shutdown (thread ID: 802)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/ConnectivityService(  887): Failed to find a new network - expiring NetTransition Wakelock
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311969, SEQNUM=4693, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1706, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService(  887): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): [1,452,517,586,190 ms] noteScanEnd no scan source
,E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=DISCONNECTED debouncing=false
,E/WifiStateMachine(  887): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
E/WifiStateMachine(  887): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  887): Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  887): will read network variables netId=0
,E/WifiStateMachine(  887): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  887): will read network variables netId=0
,I/wpa_supplicant( 8722): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
,D/WifiMonitor(  887): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 8722): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  887): setLastSelectedConfiguration -1
,E/wpa_supplicant( 8722): PNO: In assoc process
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/TCMD    (  472): NL - Read 312 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 192 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,I/wpa_supplicant( 8722): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 80 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/TCMD    (  472): NL - Read 68 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  887): setDetailed state send new extra info"NG700"
,D/Tethering(  887): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  887): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/Tethering(  887): ApnList is empty for checkDunConfigured()
,D/Tethering(  887):  upstream interface types: 
D/Tethering(  887):  0
D/Tethering(  887):  1
D/Tethering(  887):  5
D/Tethering(  887):  7
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 8722): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
E/MDMCTBK (  292): Not connected to wpa_supplicant - control or monitor connection not available.
E/MDMCTBK (  292): MdmCutbackHndler, error getting ASSOCFREQ, -1
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
,I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1221779896
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  292): Not connected to wpa_supplicant - control or monitor connection not available.
E/MDMCTBK (  292): MdmCutbackHndler, error setting TXPOWER, -1
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
D/TCMD    (  472): NL - Read 1004 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
D/TCMD    (  472): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 8722): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/Tethering(  887): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  887): Network connection established
E/WifiStateMachine(  887): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  887): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  887): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  887): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 3
E/WifiStateMachine(  887): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  887): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  887): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  887): Start Dhcp Watchdog 4
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  887): do suspend false
,E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  887): Unexpected BatchedScanResults :null
E/wpa_supplicant( 8722): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  887): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fb4817c target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  (10626): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  (10626): version 5.5.6 starting
,E/DHCPCD  (10626): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  (10626): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  (10626): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  (10626): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  (10626): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  (10626): wlan0: sending REQUEST (xid 0xcec32b28), next in 3.38 seconds
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 2 0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 3 3
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 06
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 06
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 2 38
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
,D/WifiP2pService(  887): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  887): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  887): [1,452,517,587,224 ms] noteScanEnd no scan source
,D/TCMD    (  472): NL - Read 56 bytes from update socket.
D/TCMD    (  472): NL - message type is RTM_NEWLINK
,D/TCMD    (  472): Listening for incoming client connection request
E/WifiStateMachine(  887): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ObtainingIpState@14b27b05 sup_state=COMPLETED debouncing=false
,I/DHCPCD  (10626): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  (10626): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  (10626): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  (10626): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  (10626): wlan0: adding default route via 192.168.1.1
D/DHCPCD  (10626): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  (10626): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  472): NL - Read 60 bytes from update socket.
D/TCMD    (  472): NL - ignore NL message, type = 20
D/TCMD    (  472): Listening for incoming client connection request
E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  887): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  887): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  887): do suspend true
,D/WifiP2pService(  887): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  887): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  887): WifiStateMachine DHCP successful
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  887): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  887): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  887): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  887): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  887): Adding iface wlan0 to network 103
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  887): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  887): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  887): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  887): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  887): Adding Route [fe80::/64 -> :: wlan0] to network 103
,D/ConnectivityService(  887): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,D/ConnectivityService(  887): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,D/ConnectivityService(  887): Setting Dns servers for network 103 to [/192.168.1.1]
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  887): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  887): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  887): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  887): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  887): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  887): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  887): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524295
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  887): MasterInitialState.processMessage what=3
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): now: 738384 ,futureTime: 9223372036854775807
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): now: 738389 ,futureTime: 9223372036854775807
,D/PollingManager( 2552): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2552): now: 738393 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2552): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/LaunchCheckinHandler(  887): cleanup(): cleared. Last call was 86612 ms ago
I/ActivityManager(  887): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=10699 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1477): now: 738458 ,futureTime: 86474097
,D/Central_PollingManager( 1477): Polling alarm set to expire at: 86474097 Current Time: 738458
,D/OtaApp  ( 2552): [debug] > PollingManagerService, now: 738455 ,futureTime: 11910134
,D/OtaApp  ( 2552): [debug] > Polling alarm set to expire at: 11910134 Current Time: 738462
,D/OtaApp  ( 2552): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2552): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2552): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: server told to :continue
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2552): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2552): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2552): set mOutstandingReq to true.
I/ Nonce  ( 2552):  Nonce getNonce 
I/ Nonce  ( 2552):  Nonce Request 
I/ Nonce  ( 2552):  Nonce execute Request 
,D/MMApiWebService( 2552): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2552): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MusicStore(10699): Database version: 120
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 4770(223KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 2.530ms total 30.762ms
,D/CCE     ( 2552): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2552): createDeviceIdOrLogin update_device
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2552): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2552): generating token using payload instead of using session token
,D/ Nonce  ( 2552):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/MMApiWSBase( 2552): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10699): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager(10699): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10699): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10699): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10699): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10699): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller(10699): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10699): GMSCore installation verified
,I/ConfigStore(10699): Config Database version: 1
,I/MediaRouter(10699): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback(10699): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor(10699): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor(10699): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  887): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=10747 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory(10699): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory(10699): Using platform SSLCertificateSocketFactory
,I/art     (  887): Explicit concurrent mark sweep GC freed 35569(1752KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.877ms total 120.926ms
,I/ActivityManager(  887): Killing 10371:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,V/Mms     (10747): mnc/mcc: 
V/Mms     (10747): tag: int value: recipientLimit - 20
,V/Mms     (10747): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     (10747): tag: int value: emergencySmsTimeout - 30
V/Mms     (10747): tag: int value: maxSubjectLength - 80
V/Mms     (10747): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     (10747): tag: bool value: enableGroupMms - false
V/Mms     (10747):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_10371/cgroup.procs: No such file or directory
,W/ResourcesManager(10747): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=10773 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10313:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor(10773): Register our PhoneStateListener
,I/ Nonce  ( 2552):  Nonce Reponse 
,D/        ( 2552): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"4d208b85-f207-496e-849b-1bcfd5d46cfc"}
D/MMApiWSBase( 2552): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2552):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2552): mOutstandingReq set to false
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_10313/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver(10773): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver(10773): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MMApiProvisionService( 2552):  pTime 1452467391223 sExp 172742 cTime 1452517593541 tTime 1452640133223
D/MMApiProvisionService( 2552):  No login Required 
,I/ActivityManager(  887): Killing 10517:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10032/pid_10517/cgroup.procs: No such file or directory
,I/CheckinService(10493): Checkin interval check for package: unspecified last checkin: 1452517108351 min interval config: 0 actual interval: 485357
,I/CheckinService(10493): Disabling old GoogleServicesFramework version
,I/iu.SyncManager(10493): SYNC; picasa accounts
,D/NetworkLogImpl(10493): Loaded NetworkSpeedPredictor
,I/CheckinService(10493): Checking schedule, now: 1452517593746 next: 1452517138330
,I/CheckinService(10493): active receiver: enabled
,I/iu.Environment(10493): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager(10493): num queued entries: 0
I/iu.UploadsManager(10493): num updated entries: 0
I/iu.SyncManager(10493): NEXT; no task
,I/CheckinService(10493): Preparing to send checkin request
,I/EventLogService(10493): Accumulating logs since 1452517482620
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=10805 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2552): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2552): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10016
,I/CheckinRequestBuilder(10493): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10016
,D/WifiService(  887): New client listening to asynchronous messages
,E/ActivityThread(10493): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  887): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10016
,I/ActivityManager(  887): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=10831 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager(10831): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  887): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=10850 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager(10850): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10850): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex(10850): VM with version 2.1.0 has multidex support
,I/MultiDex(10850): install
I/MultiDex(10850): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (10850): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10850): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (10850): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10850): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS(10831): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS(10831): MmsConfig.loadMmsSettings
I/Babel_SMS(10831): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS(10831): MmsConfig.loadFromDatabase
,I/art     (10850): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     (10850): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS(10831): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS(10831): MmsConfig.loadFromResources
E/Babel_SMS(10831): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS(10831): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 13:06:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452517594555], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452517594533]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): ValidatedState{ when=-520ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): DefaultState{ when=-520ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-498ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=-493ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1297): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Checking http://clients3.google.com/generate_204 on "NG700"
I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1297): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 13:06:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452517594572], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452517594562]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  887): Validated
,D/ConnectivityService(  887): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
D/ConnectivityService(  887): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityManager.CallbackHandler( 1297): CM callback handler got msg 524290
,W/Settings(10831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/NativeLibraryUtils(10850): Install completed successfully. count=14 extracted=0
I/Babel_Crash(10831): startup - clean
,I/Babel   (10831): deleted: false for 0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1414960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7589900, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597b8, idLength=0xb54d9730
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
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3062216408
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7510430
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7619808, signature_length=3041761044
,I/ActivityManager(  887): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=10886 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities(10831): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities(10831): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities(10831): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities(10831): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities(10831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10831): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10831): Unrecognized profile 2130706433 for video/avc
,I/vclib   (10831): onServiceConnected
W/Babel   (10831): Attempted to change video mute state without an active call.
,I/GAv4    (10886): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    (10886):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10886):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10886): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10886): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    (10886): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10886): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10886): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   (10831): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  887): Killing 10333:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    (10886): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10886): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat (10916): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_10333/cgroup.procs: No such file or directory
,I/dex2oat (10916): dex2oat took 57.627ms (threads: 4)
,I/Adreno-EGL(10850): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10850): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10850): Build Date: 10/28/14 Tue
I/Adreno-EGL(10850): Local Branch: 
I/Adreno-EGL(10850): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10850): Local Patches: NONE
I/Adreno-EGL(10850): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL(10850): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10850): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10850): Build Date: 10/28/14 Tue
I/Adreno-EGL(10850): Local Branch: 
I/Adreno-EGL(10850): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10850): Local Patches: NONE
I/Adreno-EGL(10850): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory(10886): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader(10886): Time to load native libraries: 1 ms (timestamps 1386-1387)
,I/LibraryLoader(10886): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10886): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader(10886): Expected native library version number "",actual native library version number ""
,I/chromium(10886): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10886): Initializing chromium process, singleProcess=true
,W/art     (10886): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils(10886): ApplicationContext is null in ApplicationStatus
,W/chromium(10886): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  (10886): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  (10886): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL(10886): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10886): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10886): Build Date: 10/28/14 Tue
I/Adreno-EGL(10886): Local Branch: 
I/Adreno-EGL(10886): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10886): Local Patches: NONE
I/Adreno-EGL(10886): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid(10886): Requires BLUETOOTH permission
,I/NSApplication(10886): Starting up...
,I/ActivityManager(  887): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=10958 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10699:com.google.android.music:main/u0a80 (adj 15): empty #7
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
D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ffe000
,W/libprocessgroup(  887): failed to open /acct/uid_10080/pid_10699/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1414960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7617490, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb756df68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
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
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
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
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb76597d8, idLength=0xbec272b0
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=649498305
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb756df68
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7589598, signature_length=3200414356
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=10979 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 10747:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  887): failed to open /acct/uid_10023/pid_10747/cgroup.procs: No such file or directory
,W/ResourcesManager(10979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  887): Explicit concurrent mark sweep GC freed 14061(742KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.622ms total 116.160ms
,I/Adreno-EGL(10850): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10850): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10850): Build Date: 10/28/14 Tue
I/Adreno-EGL(10850): Local Branch: 
I/Adreno-EGL(10850): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10850): Local Patches: NONE
I/Adreno-EGL(10850): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  887): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=11000 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 25.369ms
,I/ActivityManager(  887): Killing 10773:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.634ms
,I/Adreno-EGL(10850): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(10850): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(10850): Build Date: 10/28/14 Tue
I/Adreno-EGL(10850): Local Branch: 
I/Adreno-EGL(10850): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(10850): Local Patches: NONE
I/Adreno-EGL(10850): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.673ms
,D/EmailService.MarketingOptInSetter( 2552): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager(  887): Killing 10805:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinRequestBuilder(10493): Classify the device as Phone.
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_10773/cgroup.procs: No such file or directory
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_10805/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2552): bindWebServices(): registering our AIDL callback...
I/SundryService( 2552): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2552): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2552): onServiceConnected()
D/GetNotificationsWS( 2552): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2552): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2552): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2552): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2552): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2552): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  887): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2552): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2552): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2552): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2552): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  887): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=11034 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale(11000): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/CheckinTask(10493): Sending checkin request (9513 bytes)
,D/WearableService( 1779): callingUid 10016, callindPid: 1779
,D/LocationInitializer(10493): Restart initialization of location
,E/MDM     ( 1779): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1779): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1779): No location to return for getLastLocation()
W/FusedLocationProvider( 1779): location=null
,I/ActivityManager(  887): Killing 10886:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10081/pid_10886/cgroup.procs: No such file or directory
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311289, SEQNUM=4719, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-1767, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/CheckinRequestBuilder(10493): Checkin reason type: 8 attempt count: 1
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,E/ActivityThread(10493): Failed to find provider info for com.google.android.wearable.settings
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/art     ( 6337): Explicit concurrent mark sweep GC freed 2930(117KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 770us total 23.575ms
,I/CheckinRequestBuilder(10493): Classify the device as Phone.
,I/CheckinTask(10493): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService(10493): Checking schedule, now: 1452517597522 next: 1453118734512
I/CheckinService(10493): active receiver: disabled
,D/CheckinService(10493): Recording last checkin time for package unspecified as 1452517597535
,I/ActivityManager(  887): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=11076 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor(11076): Register our PhoneStateListener
,V/SetupWizard(11076): Connected to Gservices successfully
,I/ActivityManager(  887): Killing 10958:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10052/pid_10958/cgroup.procs: No such file or directory
,D/GCM     ( 1779): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  887): Killing 10979:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_10979/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 11000:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10007/pid_11000/cgroup.procs: No such file or directory
,I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=11099 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  887): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  887): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  887): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2adf8167
,I/GCoreNlp( 1779): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1575): Deferring update until onResume
,I/ActivityManager(  887): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=11137 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  887): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=11156 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 11034:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10088/pid_11034/cgroup.procs: No such file or directory
,W/ResourcesManager(10831): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10831): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10831): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=11181 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  887): Killing 11076:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  (10831): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10831): Installed default security provider GmsCore_OpenSSL
,I/ContactLocale(11156): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  887): failed to open /acct/uid_10035/pid_11076/cgroup.procs: No such file or directory
,W/asset   (11181): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(11181): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager(11181): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11181): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService(10493): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService(10493): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi(11099): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/Icing   (10493): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  887): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=11208 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(11208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(11099): UpdateCorporaTask done [took 135 ms] updated apps [took 135 ms] 
,I/art     (  887): Explicit concurrent mark sweep GC freed 17529(917KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.851ms total 117.521ms
,I/ActivityManager(  887): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=11241 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  887): Killing 10850:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10016/pid_10850/cgroup.procs: No such file or directory
,D/Finsky  (11241): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (11241): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(11241): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(11241): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (11241): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (11241): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     (11241): Skipping gmscore version check
,D/Finsky  (11241): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (11241): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  887): Killing 11137:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10019/pid_11137/cgroup.procs: No such file or directory
,I/Icing   (10493): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   (10493): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  887): Killing 11181:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10027/pid_11181/cgroup.procs: No such file or directory
,I/ActivityManager(  887): Killing 10831:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10070/pid_10831/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/CheckinService(10493): Done disabling old GoogleServicesFramework version
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311666, SEQNUM=4731, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-1858, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {2e87a10b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  887): send {2b5cc72f, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  887): done {2e87a10b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  887): done {2b5cc72f, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [57ms]
,I/EventLogService(10493): Aggregate from 1452517593958 (log), 1452515638246 (data)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=250, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311273, SEQNUM=4735, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-2197, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311554, SEQNUM=4736, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-2306, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/UsageStatsService(  887): User[0] Flushing usage stats to disk
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {245a4528, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/LaunchCheckinHandler(  887): cleanup(): cleared. Last call was 495958 ms ago
,I/ActivityManager(  887): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=11303 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [87ms]
,I/GAv4    (11303): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (11303):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (11303):   adb logcat -s GAv4
,W/GAv4    (11303): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (11303): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (11303): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  887): done {245a4528, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [199ms]
,I/ActivityManager(  887): Killing 11099:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  887): failed to open /acct/uid_10039/pid_11099/cgroup.procs: No such file or directory
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311848, SEQNUM=4744, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-44, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=246, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311818, SEQNUM=4745, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-81, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=246, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311524, SEQNUM=4746, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-96, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  887): send {2071d241, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [46ms]
,V/AlarmManager(  887): done {2071d241, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [98ms]
,V/AlarmManager(  887): send {2e87a10b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  887): done {2e87a10b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=246, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311524, SEQNUM=4747, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-16, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=245, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311226, SEQNUM=4748, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2439): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/BatteryService(  887): uevent={POWER_SUPPLY_TEMP=245, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311515, SEQNUM=4749, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  887): send {2de6ed68, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  887): send {16a34d60, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  887): send {2a286d27, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  887): Prepared write state in 13ms
,I/ProcessStatsService(  887): Prepared write state in 6ms
,V/AlarmManager(  887): done {16a34d60, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [67ms]
,V/AlarmManager(  887): done {2de6ed68, *alarm*:android.intent.action.TIME_TICK} [90ms]
,V/AlarmManager(  887): done {2a286d27, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [100ms]
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1779): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  887): Pruning old procstats: /data/system/procstats/state-2016-01-10-15-11-04.bin
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(11375): 
D/AndroidRuntime(11375): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11375): CheckJNI is OFF
D/AndroidRuntime(11375): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10434 user=-1: uninstall pkg
I/ActivityManager(  887): Killing 6470:com.test.thalitest/u0a434 (adj 9): stop com.test.thalitest
D/WifiService(  887): Client connection lost with reason: 4
I/WindowState(  887): WIN DEATH: Window{22d13516 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  887): Skipping PackageSetting{f36067b com.example.hello/10426} due to missing metadata
I/ActivityManager(  887):   Force finishing activity ActivityRecord{d93c953 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  887): Spurious death for ProcessRecord{30f593ed 6470:com.test.thalitest/u0a434}, curProc for 6470: null
I/ActivityManager(  887): Force stopping com.test.thalitest appid=10434 user=0: pkg removed
I/ActivityManager(  887):   Force finishing activity ActivityRecord{d93c953 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  887): Duplicate finish request for ActivityRecord{d93c953 u0 com.test.thalitest/.MainActivity t3 f}
I/art     ( 2995): Explicit concurrent mark sweep GC freed 14940(2MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 7MB/12MB, paused 871us total 58.594ms
W/GeofencerStateMachine( 1779): Ignoring removeGeofence because network location is disabled.
I/InputReader(  887): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1422): resetDictionaries() : en_US
D/VoicemailCleanupService(11156): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1422): run()
I/Decoder ( 1422): createOrResetDecoder
I/art     ( 1575): Explicit concurrent mark sweep GC freed 5999(357KB) AllocSpace objects, 9(465KB) LOS objects, 25% free, 13MB/17MB, paused 487us total 131.741ms
I/ActivityManager(  887): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=11406 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  887): Explicit concurrent mark sweep GC freed 22741(1588KB) AllocSpace objects, 11(262KB) LOS objects, 33% free, 20MB/30MB, paused 4.285ms total 169.491ms
I/art     (  887): WaitForGcToComplete blocked for 78.306ms for cause Explicit
I/ConfigService( 1779): onCreate
W/asset   (11406): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(11406): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(11406): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11406): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/BackupManagerService(  887): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  887): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = user
I/ActivityManager(  887): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=11434 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1422): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1422): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1422): run()
I/StatsUtilsManager( 1422): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1422): shouldRecordStats() = Too Soon
D/TaskPersister(  887): removeObsoleteFile: deleting file=3_task.xml
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.316ms
I/art     (  887): Explicit concurrent mark sweep GC freed 6174(350KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 4.714ms total 201.268ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.026ms
I/ActivityManager(  887): Killing 11208:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.237ms
D/AndroidRuntime(11375): Shutting down VM
W/libprocessgroup(  887): failed to open /acct/uid_10090/pid_11208/cgroup.procs: No such file or directory
I/Launcher( 1575): Deferring update until onResume
W/ContextImpl(11434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService(10493): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils(10493): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr(10493): Reading stored module config
D/ChimeraCfgMgr(10493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr(10493): Loading module APK com.google.android.play.games
I/LocationSettingsChecker(10493): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC(10493): App measurement is starting up, version: 8489
I/GMPM-SVC(10493): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1779): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1779): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase(10493): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase(10493): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager(  887): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=11468 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_MetricsDatabase(10493): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase(10493): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase(10493): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase(10493): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase(10493): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase(10493): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase(10493): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase(10493): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase(10493): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase(10493): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase(10493): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext(10493): Using Auth Proxy for data requests.
D/ChimeraCfgMgr(10493): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr(10493): Module APK com.google.android.play.games already loaded
W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  887): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=11503 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/BaseAppContext(10493): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext(10493): Using Auth Proxy for data requests.
W/BaseAppContext(10493): Using Auth Proxy for data requests.
W/BaseAppContext(10493): Using Auth Proxy for data requests.
D/ConnectivityService(  887): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  887): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  887): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler(10493): CM callback handler got msg 524290
W/BaseAppContext(10493): Using Auth Proxy for data requests.
I/Icing   (10493): doRemovePackageData com.test.thalitest
W/BaseAppContext(10493): Using Auth Proxy for data requests.
W/BaseAppContext(10493): Using Auth Proxy for data requests.
W/BaseAppContext(10493): Using Auth Proxy for data requests.
E/SQLiteDatabase(10493): Error inserting name=gcoreVersion value=8489236
E/SQLiteDatabase(10493): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1471)
E/SQLiteDatabase(10493): 	at android.database.sqlite.SQLiteDatabase.replace(SQLiteDatabase.java:1387)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.c.f.a(SourceFile:2539)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.c.f.b(SourceFile:2529)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.c.f.b(SourceFile:788)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.al.d(SourceFile:103)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.c.f.a(SourceFile:780)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/SQLiteDatabase(10493): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/SQLiteDatabase(10493): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10493): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase(10493): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext(10493): Using Auth Proxy for data requests.
E/SQLiteLog(10493): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime(10493): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime(10493): Process: com.google.android.gms, PID: 10493
E/AndroidRuntime(10493): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime(10493): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime(10493): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime(10493): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime(10493): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime(10493): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime(10493): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10493): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime(10493): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
E/DropBoxManagerService(  887): Can't write: system_app_crash
E/DropBoxManagerService(  887): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  887): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  887): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  887): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  887): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  887): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  887): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  887): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  887): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  887): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  887): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  887): 	... 5 more
E/native  ( 1422): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1422): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/Process (10493): Sending signal. PID: 10493 SIG: 9
E/native  ( 1422): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1422): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1422): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1422): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1422): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1422): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
D/ConnectivityService(  887): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f101f3e)
D/ConnectivityService(  887): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  887): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  887): Client connection lost with reason: 4
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
