#### Test 5119382166efe78_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3205): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3205):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3205):   adb logcat -s GAv4
W/GAv4    ( 3205): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3205): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3205): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3205): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2715): [1] ExternalReferrer.access$100: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2530:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 3205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3205): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3205): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2530/cgroup.procs: No such file or directory
I/Icing   ( 1715): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2715): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Icing   ( 1715): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1715): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/DownloadManager(  913): [62] Finished with status SUCCESS
D/Finsky  ( 2715): [1] DownloadBroadcastReceiver.onReceive: Intent received at DownloadBroadcastReceiver
D/Finsky  ( 2715): [1] DownloadQueueImpl.notifyProgress: com.android.vending: onProgress 15153838/15153838 Status: 200.
D/Finsky  ( 2715): [1] DownloadImpl.setState: com.android.vending from 2 to 3.
D/Finsky  ( 2715): [1] DownloadQueueImpl.onComplete: com.android.vending: onComplete
D/Finsky  ( 2715): [1] DownloadQueueImpl.remove: Download com.android.vending removed from DownloadQueue
I/installd(  185): free_cache(0) avail 11504549888
D/Finsky  ( 2715): [1] SelfUpdateScheduler.onComplete: Self-update ready to be installed, waiting for market to close.
D/AndroidRuntime( 3263): 
D/AndroidRuntime( 3263): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3263): CheckJNI is OFF
D/AndroidRuntime( 3263): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3278 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3263): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 182us total 13.540ms
I/art     (  195): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.982ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.628ms
V/ActivityManager(  760): Display changed displayId=0
I/ActivityManager(  760): Killing 2175:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2175/cgroup.procs: No such file or directory
I/WebViewFactory( 3278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3278): Time to load native libraries: 1 ms (timestamps 9505-9506)
I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3278): Binding Chromium to main looper Looper (main, tid 1) {23a62d2a}
,I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
,I/chromium( 3278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3278): Initializing chromium process, singleProcess=true
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3278): ApplicationContext is null in ApplicationStatus
,W/chromium( 3278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3278): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@276ef7a0:true
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3278): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3278): CordovaWebView is running on device made by: LGE
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3278): Render dirty regions requested: true
,D/Atlas   ( 3278): Validating map...
,W/chromium( 3278): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3278): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3278): Enabling debug mode 0
,W/BindingManager( 3278): Cannot call determinedVisibility() - never saw a connection for the pid: 3278
,W/IInputConnectionWrapper( 3278): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +446ms (total +57s788ms)
,D/JsMessageQueue( 3278): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3278): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3278): jxcore cordova android initializing
,W/jxcore-log( 3278): Initializing JXcore engine
W/jxcore-log( 3278): JXcore engine is ready
,W/jxcore-log( 3278): Starting JXcore engine
,W/.test.thalitest( 3278): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8408]" dev="sockfs" ino=8408 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3278): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3278): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9398]" dev="sockfs" ino=9398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3278): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19879]" dev="sockfs" ino=19879 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3278): Platform android
W/jxcore-log( 3278): 
,W/jxcore-log( 3278): Process ARCH arm
W/jxcore-log( 3278): 
,I/jxcore-log( 3278): JXcore Cordova bridge is ready!
I/jxcore-log( 3278): 
W/jxcore-log( 3278): JXcore engine is started
,I/chromium( 3278): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3278): Turning radios to true
I/jxcore-log( 3278): 
,D/BluetoothAdapter( 3278): enable(): BT is already enabled..!
,I/jxcore-log( 3278): toggleBluetooth - 
I/jxcore-log( 3278): 
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3278, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3278): toggleWiFi
I/jxcore-log( 3278): 
,I/ActivityManager(  760): Killing 2678:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2678/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3278): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): my name is : LGE-Nexus 5_PT1994
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): attempting to connect to test coordinator
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): check test folder
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found test : ./testFindPeers.js
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found test : ./testReConnect.js
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found test : ./testSendData.js
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Test app app.js loaded
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3278): 
,W/ActivityManager(  760): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2715): [1] PackageVerificationReceiver.onReceive: Skipping verification because own installation
,D/Finsky  ( 2715): [1] PackageVerificationReceiver.onReceive: Verification requested, id = 0
,D/DefContainer( 3074): Copying /data/data/com.android.providers.downloads/cache/downloadfile.bin to base.apk
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/PackageManager(  760): Renaming /data/app/vmdl263875007.tmp to /data/app/com.android.vending-2
,I/ActivityManager(  760): Force stopping com.android.vending appid=10016 user=-1: replace sys pkg
I/ActivityManager(  760): Killing 2715:com.android.vending/u0a16 (adj 9): stop com.android.vending
,W/PackageManager(  760): Trying to update system app code path from /data/app/com.android.vending-1 to /data/app/com.android.vending-2
,I/art     (  760): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.android.vending-2@base.apk@classes.dex' for file location '/data/app/com.android.vending-2/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     (  760): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.android.vending-2/arm/base.odex' for file location '/data/app/com.android.vending-2/base.apk': Failed to open oat filename for reading: No such file or directory
I/PackageManager(  760): Running dexopt on: /data/app/com.android.vending-2/base.apk pkg=com.android.vending isa=arm vmSafeMode=false
,I/dex2oat ( 3348): /system/bin/dex2oat --zip-fd=6 --zip-location=/data/app/com.android.vending-2/base.apk --oat-fd=7 --oat-location=/data/dalvik-cache/arm/data@app@com.android.vending-2@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager(  760): Spurious death for ProcessRecord{1107c8a 2715:com.android.vending/u0a16}, curProc for 2715: null
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,W/ActivityManager(  760): Unable to start service Intent { flg=0x4 cmp=com.android.vending/com.google.android.finsky.services.ContentSyncService (has extras) } U=0: not found
,I/dex2oat ( 3348): dex2oat took 7.442s (threads: 4)
,I/ActivityManager(  760): Force stopping com.android.vending appid=10016 user=-1: update pkg
,W/PackageManager(  760): Code path for pkg : com.android.vending changing from /data/app/com.android.vending-1 to /data/app/com.android.vending-2
W/PackageManager(  760): Resource path for pkg : com.android.vending changing from /data/app/com.android.vending-1 to /data/app/com.android.vending-2
,W/PackageSettings(  760): Skipping PackageSetting{36ddb45d com.example.hello/10277} due to missing metadata
,W/PackageManager(  760): Not granting permission android.permission.REAL_GET_TASKS to package com.android.vending (protectionLevel=18 flags=0x404abec5)
W/PackageManager(  760): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x404abec5)
W/PackageManager(  760): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.USE_FINGERPRINT in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.GET_PACKAGE_IMPORTANCE in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.GET_ACCOUNTS_PRIVILEGED in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.INSTALL_GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.GRANT_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.REVOKE_RUNTIME_PERMISSIONS in package com.android.vending
W/PackageManager(  760): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.android.vending
W/PackageManager(  760): Not granting permission android.permission.BATTERY_STATS to package com.android.vending (protectionLevel=50 flags=0x404abec5)
,W/PackageSettings(  760): Skipping PackageSetting{36ddb45d com.example.hello/10277} due to missing metadata
,I/ActivityManager(  760): Force stopping com.android.vending appid=10016 user=0: pkg removed
,I/art     ( 1356): Explicit concurrent mark sweep GC freed 3952(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 222us total 17.301ms
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/Settings(  760): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,I/art     (  760): Explicit concurrent mark sweep GC freed 74983(3MB) AllocSpace objects, 6(667KB) LOS objects, 33% free, 27MB/41MB, paused 1.528ms total 87.710ms
,I/art     (  760): WaitForGcToComplete blocked for 21.322ms for cause Explicit
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.android.vending flg=0x4000010 (has extras) }
,D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,W/Launcher( 1356): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2800371b new=com.google.android.velvet.VelvetApplication@2800371b
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3431 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.android.vending flg=0x4000010 (has extras) }
,D/BackupManagerService(  760): Now staging backup of com.android.vending
,I/art     (  760): Explicit concurrent mark sweep GC freed 3764(188KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 951us total 72.739ms
,I/PackageManager(  760): Observer no longer exists.
,W/ContextImpl( 3431): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1715): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.android.vending
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1330): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1330): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3458 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Launcher( 1356): Deferring update until onResume
,W/ResourcesManager( 1356): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1356): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1356): Deferring update until onResume
,I/art     ( 1330): Explicit concurrent mark sweep GC freed 10921(633KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 951us total 42.663ms
,D/Finsky  ( 3458): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3458): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 3458): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3458): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  760): Killing 1915:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/Ads     ( 3458): Skipping gmscore version check
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1915/cgroup.procs: No such file or directory
,D/Finsky  ( 3458): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3458): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3458): [1] InstallerImpl.access$500: Attempt recovery of content://downloads/my_downloads/62 200
D/Finsky  ( 3458): [1] InstallerImpl.access$500: Releasing content://downloads/my_downloads/62 200
,D/Finsky  ( 3458): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/UpdateIcingCorporaServi( 1464): Updating corpora: APPS=com.android.vending, CONTACTS=MAYBE
,D/Finsky  ( 3458): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/UpdateIcingCorporaServi( 1464): UpdateCorporaTask done [took 22 ms] updated apps [took 22 ms] 
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1715): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.android.vending
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1715): Submit a task: h
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 1715): CP2 sync disabled
,D/h       ( 1715): Processing package: com.android.vending
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/a       ( 1715): Look up (com.android.vending:80430000) returned no result
D/h       ( 1715): Starting Hash for package com.android.vending:6.0.0
D/GCM     ( 1330): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,W/Launcher( 1356): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2800371b new=com.google.android.velvet.VelvetApplication@2800371b
,D/PackageBroadcastService( 1715): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.android.vending
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1715): Submit a task: h
,I/PeopleContactsSync( 1715): CP2 sync disabled
,D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.vision from APK com.google.android.gms
,E/NetworkScheduler.SchedulerReceiver( 1330): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1330): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  760): Start proc com.google.android.apps.cloudprint for broadcast com.google.android.apps.cloudprint/.printdialog.receivers.UpgradeBroadcastReceiver: pid=3534 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,D/h       ( 1715): Package com.android.vending's hash: a80a3da06e5c7fea12cf0f54f8fe7d0f960b40d9e28060f84b1a4c3989562ad7
,D/a       ( 1715): Look up (com.android.vending:80430000) returned no result
,D/h       ( 1715): Saved the app info in cache for package:com.android.vending.
D/h       ( 1715): Processing package: com.android.vending
,D/GassUtils( 1715): Found app info for package com.android.vending:80430000. Hash: a80a3da06e5c7fea12cf0f54f8fe7d0f960b40d9e28060f84b1a4c3989562ad7
D/h       ( 1715): Found info for package com.android.vending in db.
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=3556 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAv4    ( 3556): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3556):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3556):   adb logcat -s GAv4
,W/GAv4    ( 3556): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3556): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3556): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3556): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3556): Time to load native libraries: 1 ms (timestamps 9871-9872)
I/LibraryLoader( 3556): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3556): Binding Chromium to main looper Looper (main, tid 1) {ca3ac8c}
,I/LibraryLoader( 3556): Expected native library version number "",actual native library version number ""
,I/chromium( 3556): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3556): Initializing chromium process, singleProcess=true
,W/art     ( 3556): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3556): ApplicationContext is null in ApplicationStatus
,W/chromium( 3556): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3556): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3556): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3556): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3556): Starting up...
I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/ActivityManager(  760): Killing 2768:com.android.settings/1000 (adj 15): empty #17
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,W/AudioManagerAndroid( 3556): Requires BLUETOOTH permission
,D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760): Killing 2790:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #18
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2768/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2790/cgroup.procs: No such file or directory
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@13539
,W/Launcher( 1356): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2800371b new=com.google.android.velvet.VelvetApplication@2800371b
,I/UpdateIcingCorporaServi( 1464): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1715): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1715): Null package name or gms related package.  Ignoreing.
,V/GmsNetworkLocationProvi( 1672): DISABLE
,I/GCoreNlp( 1672): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 1715): updateResources: need to parse f{com.google.android.gms}
,I/Launcher( 1356): Deferring update until onResume
,W/ResourcesManager( 1356): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1356): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1356): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1464): UpdateCorporaTask done [took 262 ms] updated apps [took 262 ms] 
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  760): Explicit concurrent mark sweep GC freed 22201(1102KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 929us total 62.616ms
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo,
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/Finsky  ( 3458): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 1 successful.
D/Finsky  ( 3458): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1330): Vacuum at: now=1447923181365 tag=VacuumService
,D/GetConfigurationSnapshotOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1330): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1330): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/UdcCache:FPQuery( 1715): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1330):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1330): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1330): disconnect managed GoogleApiClient
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1672): disconnect managed GoogleApiClient
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): printNetworkInfo,
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3278): DBG, CoordinatorConnector connect called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Coordinator is now connected to the server!
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): printNetworkInfo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): found interfaceName: lo
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): found interfaceName: wlan0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3278): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): DBG, CoordinatorConnector command called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"500000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"1000000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":15,"addressList":[{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0}]}
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Start now : testSendData.js
I/jxcore-log( 3278): 
I/jxcore-log( 3278): stop tests now !
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): testSendData created {"timeout":"500000","rounds":"1","dataTimeout":"10000","dataAmount":"1000000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 15
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): check server
I/jxcore-log( 3278): 
I/jxcore-log( 3278): serverPort is 35939
I/jxcore-log( 3278): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3278): Stoping All
I/        ( 3278): Stopping services
I/        ( 3278): Stop Bluetooth
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3278): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3278):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1994","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3278): All stuff available and enabled
I/        ( 3278): Stoping All
I/        ( 3278): Stopping services
I/        ( 3278): Stop Bluetooth
I/        ( 3278): Starting All
I/        ( 3278): Stopping services
I/        ( 3278): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1994","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@29ef74c5
I/        ( 3278): Stopping services
,I/        ( 3278): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1994","ra":"34:FC:EF:11:AE:67"}
I/        ( 3278): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1994","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3278): peerDiscoveryTimer timeout value:5410
,I/        ( 3278): Stop Bluetooth
I/        ( 3278): StartBluetooth listener
I/        ( 3278): StartBluetooth listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): StartBroadcasting started ok
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server  is bound to : undefined
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3278): We already were running, thus doing nothing
I/        ( 3278): Added local service
I/        ( 3278): Cleared service requests
I/        ( 3278): Stopped peer discovery
I/        ( 3278): Started peer discovery
I/        ( 3278): Discovery state changed to Started.
,I/BTListenerThread( 3278): starting to listen
I/BTListenerThread( 3278): waiting to accept incoming Connection
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3278): Found 3 peers.
I/SS      ( 3278): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(3): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3278): Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3278): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3278): Starting to connect
,W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3744 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f99f13:true
,I/ActivityManager(  760): Killing 2646:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2646/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-XT1039_PT3406
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-XT1039_PT3406
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-XT1039_PT3406
,I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 58636
I/BtConnectorHelper( 3278): Request socket is using : 58636
,I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :58636
,I/jxcore-log( 3278): CLIENT connected to 58636, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 58636
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74136
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67342
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77650
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73826
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69012
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71400
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73652
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69964
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71226
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68528
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68936
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77264
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72450
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69752
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75964
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70160
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66472
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69850
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72102
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69404
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73772
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67968
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68376
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70764
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71036
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69328
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71716
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69018
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76356
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73522
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73794
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67000
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70378
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68670
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70068
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73310
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74572
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71738
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68050
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77368
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74534
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71700
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72962
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71254
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71526
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72788
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70090
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69372
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66827
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57917
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:50987
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44057
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33167
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:27227
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18317
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6437
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3467
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-XT1039_PT3406
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
,I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
,I/BtToSocketBase( 3278): Close localHostSocket
,I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
,W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17f5c349:true
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1039
,I/jxcore-log( 3278): Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3278): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-XT1039_PT3406
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-XT1039_PT3406
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-XT1039_PT3406
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 41467
I/BtConnectorHelper( 3278): Request socket is using : 41467
,I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :41467
I/jxcore-log( 3278): CLIENT connected to 41467, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 41467
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 70000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:13667
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6737
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 42134 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-XT1039_PT3406
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
,I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1039
,I/jxcore-log( 3278): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3278): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT507","ra":"44:80:EB:7B:5A:05"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-XT1072_PT507
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-XT1072_PT507
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-XT1072_PT507
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 39517
I/BtConnectorHelper( 3278): Request socket is using : 39517
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :39517
,I/jxcore-log( 3278): CLIENT connected to 39517, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 39517
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70176
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69458
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74816
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68022
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76350
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71536
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67130
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72488
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73750
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66956
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73304
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71596
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69888
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71150
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71422
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71694
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72956
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71248
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74490
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71656
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72918
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74180
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74316
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69502
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74860
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71036
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68338
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76666
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70862
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72124
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71406
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68708
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72086
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70378
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68670
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70068
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71330
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67642
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73000
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74262
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71428
,I/art     (  760): Explicit concurrent mark sweep GC freed 25932(1305KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.049ms total 80.884ms
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68730
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74088
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71254
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68556
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70944
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69236
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67817
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57917
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:47027
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:39107
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:34157
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23267
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18317
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6437
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3467
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 10 peers.
,I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(10): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
,W/bt-btif ( 2201): proc dm_pm_timer expires
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-XT1072_PT507
,I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1072
,I/jxcore-log( 3278): Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 3278): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT507","ra":"44:80:EB:7B:5A:05"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-XT1072_PT507
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-XT1072_PT507
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-XT1072_PT507
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 54583
I/BtConnectorHelper( 3278): Request socket is using : 54583
,I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :54583
I/jxcore-log( 3278): CLIENT connected to 54583, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 54583
,I/BtToRequestSocket( 3278): Set local streams
,I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 10000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 42481 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-XT1072_PT507
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1072
,I/jxcore-log( 3278): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3278): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : HTC-HTC Desire 820_PT9037
I/HS      ( 3278): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9037
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 33356
I/BtConnectorHelper( 3278): Request socket is using : 33356
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :33356
I/jxcore-log( 3278): CLIENT connected to 33356, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 33356
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70312
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67614
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68022
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70818
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61190
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74740
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68936
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58454
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71014
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68316
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59814
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72374
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69676
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57078
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72744
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72026
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58438
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69018
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71406
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59798
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68398
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73756
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57062
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:77678
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70884
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:54326
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73952
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68148
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55686
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:53277
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44367
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24567
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17637
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7737
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3278): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3278): Peer(3): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/jxcore-log( 3278): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3278): Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3278): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3278): Starting to connect
,W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
,I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : HTC-HTC Desire 820_PT9037
I/HS      ( 3278): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9037
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 44930
I/BtConnectorHelper( 3278): Request socket is using : 44930
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :44930
I/jxcore-log( 3278): CLIENT connected to 44930, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 44930
I/BtToRequestSocket( 3278): Set local streams
,I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 340000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69322
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72700
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67797
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:49977
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43047
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:32157
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10377
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2457
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,W/bt-btif ( 2201): invalid rfc slot id: 10
,I/BtToSocketBase( 3278): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3278): Disconnect outgoing peer: HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3278): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : HTC-HTC Desire 820_PT9037
I/HS      ( 3278): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9037
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 54243
,I/BtConnectorHelper( 3278): Request socket is using : 54243
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :54243
,I/jxcore-log( 3278): CLIENT connected to 54243, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 54243
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 70000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): ---- round done--------,
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 75177 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: HTC-HTC Desire 820_PT9037
I/BtToSocketBase( 3278): Stop ReceivingThread
,I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3278): Connect (retry count 0) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3278): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 12
,I/BTConnectToThread( 3278): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3278): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3278): CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3278): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 13
I/BTConnectToThread( 3278): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3278): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3278): CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 6 peers.
I/SS      ( 3278): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3278): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3278): re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/jxcore-log( 3278): Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3278): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(4): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,W/bt-rfcomm( 2201): PORT_StartCnf failed result:5
E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2201): invalid rfc slot id: 14
,I/BTConnectToThread( 3278): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3278): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3278): CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3278): re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/        ( 3278): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 15
I/BTConnectToThread( 3278): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3278): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3278): CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 6 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/        ( 3278): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT8568, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT8568, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3902, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3902, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 3278): re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3278): 
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3278): Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 90:E7:C4:F6:69:77, name: HTC One M8s
,I/        ( 3278): Connecting to HTC One M8s, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,W/bt-sdp  ( 2201): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2201): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2201): invalid rfc slot id: 16
I/BTConnectToThread( 3278): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3278): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3278): CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 71270 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3278): Connect (retry count 0) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3278): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N910C_PT4320
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N910C_PT4320
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N910C_PT4320
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 48404
I/BtConnectorHelper( 3278): Request socket is using : 48404
I/BtToRequestSocket( 3278): Now accepting connections
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :48404
,I/jxcore-log( 3278): CLIENT connected to 48404, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 48404
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70312
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68604
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66450
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70818
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60200
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3278): Found 7 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71770
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71052
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57464
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72004
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69306
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58824
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70394
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70666
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56088
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71754
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68066
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61544
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70008
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67310
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58808
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68398
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71776
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67098
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67506
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71874
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63236
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75660
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68866
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56404
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59217
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:49317
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:32487
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19617
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13677
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3866 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/EventLogService( 1715): Aggregate from 1447922701121 (log), 1447921997234 (data)
,I/GAv4    ( 3866): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3866):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3866):   adb logcat -s GAv4
,W/GAv4    ( 3866): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3866): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3866): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2105:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2105/cgroup.procs: No such file or directory
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N910C_PT4320
,I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3278): Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3278): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
,I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N910C_PT4320
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N910C_PT4320
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N910C_PT4320
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 35287
I/BtConnectorHelper( 3278): Request socket is using : 35287
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :35287
I/jxcore-log( 3278): CLIENT connected to 35287, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 35287
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 360000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68332
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71710
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65052
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71536
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70818
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57997
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:51067
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43147
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15427
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7507
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N910C_PT4320
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3278): Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3278): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
,I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N910C_PT4320
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N910C_PT4320
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N910C_PT4320
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 53811
I/BtConnectorHelper( 3278): Request socket is using : 53811
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :53811
I/jxcore-log( 3278): CLIENT connected to 53811, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 53811
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 90000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 72144 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N910C_PT4320
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 6 peers.
I/SS      ( 3278): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3278): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4320, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4320, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3278): Connect (retry count 0) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3278): Connecting to null, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-Nexus 6_PT9059
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-Nexus 6_PT9059
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-Nexus 6_PT9059
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 38578
I/BtConnectorHelper( 3278): Request socket is using : 38578
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :38578
,I/jxcore-log( 3278): CLIENT connected to 38578, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 38578
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70176
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70448
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72700
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70992
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68294
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70682
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68974
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74332
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68528
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71906
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69208
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70606
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74838
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70024
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66336
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68724
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74082
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74218
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71384
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72646
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73908
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70084
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69366
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75714
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70900
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72162
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76394
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71580
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72842
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72124
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73386
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:79598
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71678
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70960
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76182
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68398
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72766
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73038
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72320
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68632
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73000
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75252
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71428
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71700
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/SS      ( 3278): Found 3 peers.
I/SS      ( 3278): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3278): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72962
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76204
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69410
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74768
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69954
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68246
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66827
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,I/        ( 3278): Started service discovery
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57917
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:47027
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:40097
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/art     ( 2201): Explicit concurrent mark sweep GC freed 30892(1494KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 15MB/26MB, paused 530us total 33.344ms
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:25247
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18317
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9407
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2477
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/art     (  760): Explicit concurrent mark sweep GC freed 26413(1434KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.023ms total 95.828ms
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
,W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-Nexus 6_PT9059
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3278): Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3278): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : motorola-Nexus 6_PT9059
I/HS      ( 3278): Hand Shake finished outgoing for : motorola-Nexus 6_PT9059
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, motorola-Nexus 6_PT9059
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 42264
I/BtConnectorHelper( 3278): Request socket is using : 42264
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :42264
I/jxcore-log( 3278): CLIENT connected to 42264, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 42264
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 120000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:38667
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:27777
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18867
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7977
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3278): 
I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 36729 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3278): Disconnect outgoing peer: motorola-Nexus 6_PT9059
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
,I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3278): Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3278): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3278): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : LGE-Nexus 5_PT3902
I/HS      ( 3278): Hand Shake finished outgoing for : LGE-Nexus 5_PT3902
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, LGE-Nexus 5_PT3902
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 50273
I/BtConnectorHelper( 3278): Request socket is using : 50273
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :50273
I/jxcore-log( 3278): CLIENT connected to 50273, error: null
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 50273
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:76970
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70176
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69458
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71846
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69148
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72526
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68120
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69518
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72896
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71188
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67500
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:76818
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71014
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68316
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73674
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:79886
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69986
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72238
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70530
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66842
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70220
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72472
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71754
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:75986
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70182
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71444
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71716
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72978
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72260
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70552
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67854
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70242
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73484
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72766
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74028
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70204
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66516
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70884
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68186
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74534
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71700
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70982
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71254
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:74496
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73642
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69954
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72206
,I/jxcore-log( 3278): CLIENT is data received : 800000,
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72478
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62867
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55937
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48017
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38117
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:30197
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23267
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18317
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8417
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 1000000
I/jxcore-log( 3278): 
I/jxcore-log( 3278): got all data for this round
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ---- round done--------
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do fake peer & start
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback round[0] time: 16158 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: LGE-Nexus 5_PT3902
I/BtToSocketBase( 3278): Stop ReceivingThread
,I/BtToSocketBase( 3278): Stop SendingThread
,I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3278): we got incoming connection
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
I/BTListenerThread( 3278): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTListenerThread( 3278): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3278): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3278): MESSAGE_WRITE 77 bytes.
I/HS      ( 3278): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT3902
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : true, LGE-Nexus 5_PT3902
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BTConnectedThread
I/BtConnectorHelper( 3278): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3278): --DoOneRunRound started
,I/BtToRequestSocket( 3278): LocalHost address: localhost/127.0.0.1, port: 35939
,I/jxcore-log( 3278): TCP/IP server connected
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): --DoOneRunRound ended
,I/jxcore-log( 3278): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 100980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 102960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 104940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 114840 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 116820 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 128700 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 130680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 132660 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 146520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 148500 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 164340 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 170280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 172260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 174240 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 182160 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 186120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 198000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 199980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 205920 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 207900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 213840 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 215820 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 217800 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 227700 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 229680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 241560 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 243540 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 245520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 255420 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 257400 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 263340 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 265320 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 273240 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 275220 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 287100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 289080 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 297000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 300960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 302940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 304920 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 316800 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 318780 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 328680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 332640 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 338580 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 354420 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 360360 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 364320 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 368280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 376200 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 382140 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 386100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 396000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 397980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 405900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 407880 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 409860 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 417780 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 419760 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 421740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 423720 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 425700 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 427680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 435600 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 437580 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 439560 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 443520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 445500 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 447480 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 465300 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 469260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 471240 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 475200 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 483120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 485100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 500940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 502920 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 504900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 518760 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 520740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 522720 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 526680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 538560 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 540540 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 542520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 544500 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 560340 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 564300 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 568260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 580140 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 582120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 584100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 595980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 597960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 613800 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 615780 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 619740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 627660 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 629640 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 641520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 647460 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 651420 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 653400 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 657360 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 665280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 667260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 673200 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 675180 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 683100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 689040 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 693000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 694980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 702900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 704880 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 708840 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 710820 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 714780 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 718740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 724680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 726660 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 732600 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 734580 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 738540 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 740520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 744480 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 752400 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 754380 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 758340 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 760320 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 762300 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 764280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 768240 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 772200 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 774180 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 782100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 784080 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 788040 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 790020 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 792000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 793980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 797940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 805860 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 809820 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 819720 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 821700 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 823680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 833580 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 837540 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 843480 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 845460 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 847440 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 855360 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 857340 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 863280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 869220 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 877140 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 879120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 883080 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 885060 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Connect (retry count 0) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3278): Connecting to null, at E0:DB:10:1F:C9:5E
,I/jxcore-log( 3278): TCP/IP server has received 889020 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 892980 bytes of data
I/jxcore-log( 3278): 
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3278): TCP/IP server has received 894960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 902880 bytes of data
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): TCP/IP server has received 904860 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 916740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 918720 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 924660 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 926640 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 938520 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 940500 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 942480 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 944460 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 946440 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 948420 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 958320 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 960300 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 962280 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 964260 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 978120 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 980100 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 982080 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 984060 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 986040 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 990000 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 995940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 997920 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 999900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 1000002 bytes of data
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): invalid rfc slot id: 4
,I/BtToSocketBase( 3278): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3278): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3278): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT3902
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3278): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3278): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT3902
I/BtToSocketBase( 3278): Close LocalOutputStream
,I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
,I/BtToSocketBase( 3278): Close bt in
I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3278): TCP/IP server is ended
I/jxcore-log( 3278): 
I/jxcore-log( 3278): TCP/IP server is close
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2201): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2201): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2201): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2201): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2201): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2201): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2201): StableState(): Entering Off State
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N9005_PT3513
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N9005_PT3513
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 40998
I/BtConnectorHelper( 3278): Request socket is using : 40998
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :40998
I/jxcore-log( 3278): CLIENT connected to 40998, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 40998
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 1000000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 10000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 20000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70312
,I/jxcore-log( 3278): CLIENT is data received : 30000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 40000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67614
,I/jxcore-log( 3278): CLIENT is data received : 50000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 60000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3278): CLIENT is data received : 70000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 80000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68430
,I/jxcore-log( 3278): CLIENT is data received : 90000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 100000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3278): CLIENT is data received : 110000
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60200
,I/jxcore-log( 3278): CLIENT is data received : 120000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73750
,I/jxcore-log( 3278): CLIENT is data received : 130000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 140000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:68936
,I/jxcore-log( 3278): CLIENT is data received : 150000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57464
,I/jxcore-log( 3278): CLIENT is data received : 160000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 170000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72004
,I/jxcore-log( 3278): CLIENT is data received : 180000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 190000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69306
,I/jxcore-log( 3278): CLIENT is data received : 200000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57834
,I/jxcore-log( 3278): CLIENT is data received : 210000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 220000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71384
,I/jxcore-log( 3278): CLIENT is data received : 230000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 240000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70666
,I/jxcore-log( 3278): CLIENT is data received : 250000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55098
,I/jxcore-log( 3278): CLIENT is data received : 260000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 270000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73734
,I/jxcore-log( 3278): CLIENT is data received : 280000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 290000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67930
,I/jxcore-log( 3278): CLIENT is data received : 300000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56458
,I/jxcore-log( 3278): CLIENT is data received : 310000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 320000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72124
,I/jxcore-log( 3278): CLIENT is data received : 330000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 340000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72396
,I/jxcore-log( 3278): CLIENT is data received : 350000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57818
,I/jxcore-log( 3278): CLIENT is data received : 360000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 370000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70378
,I/jxcore-log( 3278): CLIENT is data received : 380000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 390000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69660
,I/jxcore-log( 3278): CLIENT is data received : 400000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3278): Found 1 peers.
I/SS      ( 3278): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:55082
,I/jxcore-log( 3278): CLIENT is data received : 410000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 420000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72728
,I/jxcore-log( 3278): CLIENT is data received : 430000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3278): CLIENT is data received : 440000
I/jxcore-log( 3278): 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70030
,I/jxcore-log( 3278): CLIENT is data received : 450000
I/jxcore-log( 3278): 
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3513, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3513, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56442
,I/jxcore-log( 3278): CLIENT is data received : 460000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 470000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:73098
,I/jxcore-log( 3278): CLIENT is data received : 480000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 490000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71390
,I/jxcore-log( 3278): CLIENT is data received : 500000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 510000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:57802
,I/jxcore-log( 3278): CLIENT is data received : 520000
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28102
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3278): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/jxcore-log( 3278): CLIENT is data received : 530000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 540000
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): Stop ReceivingThread
,I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3278): Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3278): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:1f:c9:5e]: 6, f, 6109
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
,I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N9005_PT3513
,I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N9005_PT3513
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 58930
I/BtConnectorHelper( 3278): Request socket is using : 58930
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :58930
I/jxcore-log( 3278): CLIENT connected to 58930, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 58930
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 460000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:71030
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66352
,I/jxcore-log( 3278): CLIENT is data received : 550000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 560000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:70720
,I/jxcore-log( 3278): CLIENT is data received : 570000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 580000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3278): CLIENT is data received : 590000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:44670
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14970
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:50806
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:21106
,I/jxcore-log( 3278): CLIENT is data received : 600000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 610000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3278): Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3278): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N9005_PT3513
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N9005_PT3513
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N9005_PT3513
,I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 53588
I/BtConnectorHelper( 3278): Request socket is using : 53588
,I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :53588
I/jxcore-log( 3278): CLIENT connected to 53588, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 53588
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 390000 bytes of data
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:72020
,I/jxcore-log( 3278): CLIENT is data received : 620000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67342
,I/jxcore-log( 3278): CLIENT is data received : 630000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:72700
,I/jxcore-log( 3278): CLIENT is data received : 640000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 650000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67032
,I/jxcore-log( 3278): CLIENT is data received : 660000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 670000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66450
,I/jxcore-log( 3278): CLIENT is data received : 680000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 690000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:69828
,I/jxcore-log( 3278): CLIENT is data received : 700000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60200
,I/jxcore-log( 3278): CLIENT is data received : 710000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:67057
,I/jxcore-log( 3278): CLIENT is data received : 720000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:56167
,I/jxcore-log( 3278): CLIENT is data received : 730000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 740000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:35377
,I/jxcore-log( 3278): CLIENT is data received : 750000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29437
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15577
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 760000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 770000
I/jxcore-log( 3278): 
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): CLIENT is data received : 780000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 790000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 800000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 810000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 820000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 830000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 840000
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): info:x10
,D/        ( 2201): remote version info [44:80:eb:7b:5a:05]: 7, f, 6109
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1072
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 6 peers.
I/SS      ( 3278): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2201): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3278): we got incoming connection
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3278): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
,W/bt-btif ( 2201): proc dm_pm_timer expires
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 3278): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3278): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT507","ra":"44:80:EB:7B:5A:05"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3278): MESSAGE_WRITE 77 bytes.
I/HS      ( 3278): Incoming connection Hand Shake finished for : motorola-XT1072_PT507
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : true, motorola-XT1072_PT507
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BTConnectedThread
I/BtConnectorHelper( 3278): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3278): --DoOneRunRound started
,I/BtToRequestSocket( 3278): LocalHost address: localhost/127.0.0.1, port: 35939
,I/jxcore-log( 3278): TCP/IP server connected
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): --DoOneRunRound ended
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2201): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3278): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 100088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 102068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 108008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 109988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 111968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 113948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 115928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 117908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 119888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 121868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 123848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 129788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 131768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 133748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 139688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 141668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 143648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 145628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 147608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 149588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 155528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 157508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 159488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 161468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 163448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 165428 bytes of data
I/jxcore-log( 3278): 
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3278): TCP/IP server has received 169388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 171368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 173348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 175328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 177308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
,I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 179288 bytes of data
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 181268 bytes of data
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): TCP/IP server has received 183248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 187208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 189188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 191168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 193148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 197108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 199088 bytes of data
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3278): TCP/IP server has received 201068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 203048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 205028 bytes of data
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): TCP/IP server has received 207008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 208988 bytes of data
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3278): TCP/IP server has received 210968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 212948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 214928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 216908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 218888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 220868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 222848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 224828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 226808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 228788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 230768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 232748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 234728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 236708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 238688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 240668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 242648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 244628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 246608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 248588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 250568 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 252548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 254528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 256508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 260468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 262448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 264428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 266408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 268388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 270368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 272348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 274328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 276308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 278288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 280268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 282248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 284228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 286208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 288188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 290168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 292148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 294128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 296108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 298088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 300068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 302048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 304028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 306008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 307988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 309968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 311948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 313928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 317888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 319868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 321848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 323828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 325808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 327788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 329768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 331748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 333728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 335708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 337688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 339668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 341648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 343628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 345608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 347588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 351548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 353528 bytes of data
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/jxcore-log( 3278): TCP/IP server has received 355508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 359468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 361448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 363428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 365408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 367388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 371348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 373328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 375308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 381248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 383228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 385208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 387188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 391148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 393128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 395108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 397088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 401048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 403028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 405008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 406988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 410948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 412928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 414908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 416888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 418868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 420848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 424808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 426788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 428768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 430748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 432728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 434708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 436688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 438668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 442628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 444608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 446588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 448568 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 450548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 452528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 454508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 456488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 460448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 462428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 464408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 466388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 468368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 470348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 472328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 474308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 476288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 478268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 482228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 484208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 488168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 490148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 492128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 494108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 496088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 498068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 500048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 502028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 504008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 505988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 507968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 509948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 511928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3278): 
I/jxcore-log( 3278): do connect now
I/jxcore-log( 3278): 
,I/        ( 3278): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 3278): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): TCP/IP server has received 513908 bytes of data
I/jxcore-log( 3278): 
,I/BTConnectToThread( 3278): Starting to connect
W/BluetoothAdapter( 3278): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2201): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3278): TCP/IP server has received 517868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 519848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 521828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 523808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 525788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 527768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 529748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 531728 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3278): Found 1 peers.
I/SS      ( 3278): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/jxcore-log( 3278): TCP/IP server has received 533708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 541628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 543608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 549548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 551528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 553508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 555488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 557468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 559448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 561428 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3278): TCP/IP server has received 563408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 569348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 571328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 573308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 575288 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/jxcore-log( 3278): TCP/IP server has received 577268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 581228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 583208 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3278): TCP/IP server has received 585188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 587168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 589148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 591128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 593108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 597068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 599048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 601028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 603008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 604988 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3278): TCP/IP server has received 608948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 610928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 612908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 614888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 618848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 620828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 622808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 624788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 626768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 628748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 632708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 634688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 638648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 640628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 642608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 644588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 646568 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 648548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 650528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 652508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 654488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 656468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 660428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 662408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 664388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 666368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 668348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 670328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 672308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 676268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 678248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 680228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 682208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 684188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 686168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 688148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 690128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 692108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 694088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 696068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 698048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 700028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 702008 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 703988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 705968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 707948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 709928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 711908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 713888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 717848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 719828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 721808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 723788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 725768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 727748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 729728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 731708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 733688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 735668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 737648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 739628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 741608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 743588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 745568 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 749528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 751508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 753488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 757448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 759428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 761408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 763388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 765368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 767348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 771308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 773288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 777248 bytes of data
I/jxcore-log( 3278): 
I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3278): TCP/IP server has received 779228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 781208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 783188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 785168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 787148 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 789128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 791108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 793088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 795068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 797048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 799028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 804968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 806948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 810908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 812888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 814868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 818828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 822788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 824768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 826748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 828728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 830708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 832688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 834668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 836648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 838628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 840608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 842588 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 846548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 848528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 850508 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 856448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 858428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 860408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 862388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 864368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 866348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 868328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 870308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 872288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 876248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 878228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 880208 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 882188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 884168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 888128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 890108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 892088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 894068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 896048 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 898028 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 901988 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 903968 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 905948 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 907928 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 909908 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 911888 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 913868 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 915848 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 917828 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 919808 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 921788 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 923768 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 925748 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 927728 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 929708 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 931688 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 933668 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 935648 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 937628 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 939608 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 945548 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 947528 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 951488 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 953468 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 955448 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 957428 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 959408 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 961388 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 963368 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 965348 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 967328 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 969308 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 971288 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 973268 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 975248 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 977228 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 981188 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 983168 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 987128 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 989108 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 991088 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 993068 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server has received 995048 bytes of data
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): invalid rfc slot id: 23
,I/BtToSocketBase( 3278): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3278): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3278): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT507
I/BtToSocketBase( 3278): Stop ReceivingThread
,I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3278): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3278): TCP/IP server has received 1000002 bytes of data
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): TCP/IP server is ended
I/jxcore-log( 3278): 
I/jxcore-log( 3278): TCP/IP server is close
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2201): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2201): RFCOMM_DisconnectInd LCID:0x4f
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: XT1072
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(4): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,E/bt-btm  ( 2201): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2201): bta_dm_check_av:0
,W/bt-btif ( 2201): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2201): process_service_search_attr_rsp
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2201): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3278): Starting to Handshake
I/BTHandshakeSocketThread( 3278): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3278): MESSAGE_WRITE 77 bytes.
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread started
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 3278): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3278): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3278): HandshakeOk : samsung-SM-N9005_PT3513
I/HS      ( 3278): Hand Shake finished outgoing for : samsung-SM-N9005_PT3513
I/BTHandshakeSocketThread( 3278): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3278): Starting the connected thread incoming : false, samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3278): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3278): mHTTPPort  set to : 33253
I/BtConnectorHelper( 3278): Request socket is using : 33253
I/BtToRequestSocket( 3278): Now accepting connections
,I/BtConnectorHelper( 3278): Calling ConnectionStatusUpdate with port :33253
I/jxcore-log( 3278): CLIENT connected to 33253, error: null
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT starting client 
I/jxcore-log( 3278): 
,I/BtToRequestSocket( 3278): incoming data from: /127.0.0.1, port: 33253
I/BtToRequestSocket( 3278): Set local streams
I/BtToRequestSocket( 3278): rin ended ---------------------------;
,I/jxcore-log( 3278): CLIENT now sending 160000 bytes of data
I/jxcore-log( 3278): 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:33237
,I/jxcore-log( 3278): CLIENT is data received : 850000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 860000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23337
,I/jxcore-log( 3278): CLIENT is data received : 870000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 880000
I/jxcore-log( 3278): 
,D/        ( 2201): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12447
,I/jxcore-log( 3278): CLIENT is data received : 890000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 900000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 910000
I/jxcore-log( 3278): 
,I/        ( 3278): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT9059, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT9059, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3278): CLIENT is data received : 920000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 930000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 940000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 950000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 960000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 970000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 980000
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): CLIENT is data received : 990000
I/jxcore-log( 3278): 
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 2201): dm_pm_timer expires
W/bt-btif ( 2201): dm_pm_timer expires 0
W/bt-btif ( 2201): proc dm_pm_timer expires
,I/        ( 3278): Cleared service requests
,I/        ( 3278): Started peer discovery
,I/jxcore-log( 3278): Receiving data timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT closeClientSocket
I/jxcore-log( 3278): 
,I/BtToSocketBase( 3278): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3278): Disconnect outgoing peer: samsung-SM-N9005_PT3513
I/BtToSocketBase( 3278): Stop ReceivingThread
I/BtToSocketBase( 3278): Stop SendingThread
I/BtToSocketBase( 3278): Close local in
,I/BtToSocketBase( 3278): Close LocalOutputStream
I/BtToSocketBase( 3278): Close localHostSocket
I/BtToSocketBase( 3278): Close bt in
,I/BtToSocketBase( 3278): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3278): Close bt out
I/BtToSocketBase( 3278): Close bt socket
I/BtToRequestSocket( 3278): Close server socket
,I/jxcore-log( 3278): tryAgain afer: 5000 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): ----------------- closeClientSocket
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT is closed
I/jxcore-log( 3278): 
,W/bt-btif ( 2201): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 5 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3278): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3278): re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3278): 
,E/bt-btm  ( 2201): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2201): onReceive
,I/BTConnectionReceiver( 1464): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1464): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3278): timeout now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): dun
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): weAreDoneNow , resultArray.length: 6
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): done, now sending data to server
I/jxcore-log( 3278): 
I/jxcore-log( 3278): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): -- RESULT DATA {"name:":"LGE-Nexus 5_PT1994","time":500081,"result":"TIMEOUT","sendList":[{"name":"F4:F1:E1:5C:3B:E2","time":42134,"result":"OK","connections":2,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":42481,"result":"OK","connections":2,"tryCount":1},{"name":"B4:CE:F6:AB:A4:6A","time":75177,"result":"OK","connections":3,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":72144,"result":"OK","connections":3,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":36729,"result":"OK","connections":2,"tryCount":1},{"name":"34:FC:EF:11:B1:66","time":16158,"result":"OK","connections":1,"tryCount":1},{"connections":1,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"c
I/jxcore-log( 3278): sendList : 100% : 75177 ms, 99% : 75177 ms, 95 : 75177 ms, 90% : 72144 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Result count 6, range 16158 ms to  75177 ms.
I/jxcore-log( 3278): 
I/jxcore-log( 3278): sendList failed peers count : 2 [25 %]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 90:E7:C4:F6:69:77, Tried : 1
I/jxcore-log( 3278): 
I/jxcore-log( 3278): sendList never tried peers count : 7 [46.666666666666664 %]
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3278): 
,I/jxcore-log( 3278): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 3278): 
I/jxcore-log( 3278): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3278): 
I/jxcore-log( 3278): CLIENT Stop now
I/jxcore-log( 3278): 
I/jxcore-log( 3278): Stop data retrieving timer
I/jxcore-log( 3278): 
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3278): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3278): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9059","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT9059, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT9059, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3278): Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3278): 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3278): Found 9 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Cleared service requests
,I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
,I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
,I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(11): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 6 peers.
I/SS      ( 3278): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
,I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT8568, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT8568, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3902, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3902, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 9 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT8568, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT8568, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3902, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3902, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3278): Found 9 peers.
,I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 3278): Cleared service requests
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 4 peers.
I/SS      ( 3278): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT3902"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT3902, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT3902, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 7 peers.
I/SS      ( 3278): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 8 peers.
I/SS      ( 3278): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3513, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3513, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4320, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4320, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3278): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6180","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6180","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6180, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6180, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3278): Found 5 peers.
I/SS      ( 3278): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3513, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3513, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3278): Found 7 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3278): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
,I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3513, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3513, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 9 peers.
,I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT8568, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT8568, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3278): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT9037"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT9037, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT9037, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3278): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3406"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3406, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3406, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3278): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3513","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3513, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3513, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3278): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1625","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1625, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1625, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/bt-smp  ( 2201): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2201): Plain text(LSB ~ MSB) = 79 df 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2201): Encrypted text(LSB ~ MSB) = ff 09 42 cd 06 39 ca 04 89 f9 71 b2 19 c6 d9 b2 
,W/bt-btm  ( 2201): Stopping oneshot timer
,I/        ( 3278): Cleared service requests
,I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3278): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3278): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2469","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2469","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT2469, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT2469, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3278): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT507","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT507","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT507, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT507, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 10 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3278): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 8 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  982): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/ProcessStatsService(  760): Prepared write state in 27ms
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-11-18-13-36-42.bin
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=4035 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4035): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4035): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 4035): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4079): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1629749677.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-1629749677.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4079): dex2oat took 47.727ms (threads: 4)
,W/InstanceID/Rpc( 4035): Found 10008
,I/ActivityManager(  760): Killing 2816:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2816/cgroup.procs: No such file or directory
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3278): Found 9 peers.
I/SS      ( 3278): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3278): Started service discovery
,I/        ( 3278): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4320","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT4320, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT4320, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3278): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8651"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8651, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8651, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3278): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT8568","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT8568, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT8568, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3278): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6180","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6180","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6180, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6180, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3278): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4971"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4971, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4971, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3278): Cleared service requests
I/        ( 3278): Started peer discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3278): Found 11 peers.
I/SS      ( 3278): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3278): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3278): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3278): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3278): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3278): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3278): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3278): Peer(8): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3278): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3278): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3278): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3278): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3278): Added service request
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  982): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3278): Started service discovery
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  982): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  982): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3278): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4242","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT4242, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT4242, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3278): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3278): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8675","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8675, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3278): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8675, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,TIME-OUT KILL (timeout was 1800000ms)
```
