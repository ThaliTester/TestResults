#### Test 506502781a07ac8_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/qtaguid ( 2392): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2392): Untagging socket 52 failed errno=-22
W/NetworkManagementSocketTagger( 2392): untagSocket(52) failed with errno -22
D/Finsky  ( 2392): [1] 5.onFinished: Installation state replication succeeded.
,D/AndroidRuntime( 2944): 
D/AndroidRuntime( 2944): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2944): CheckJNI is OFF
D/dalvikvm( 2944): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2944): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2944): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2944): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2944): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm(  774): GC_CONCURRENT freed 25968K, 51% free 27940K/56048K, paused 3ms+4ms, total 126ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 108ms
D/dalvikvm( 2944): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2944): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  774): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2944
D/PermissionCache(  183): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (108 us)
D/AndroidRuntime( 2944): Shutting down VM
D/dalvikvm( 2944): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+1ms, total 2ms
I/ActivityManager(  774): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2957 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
D/dalvikvm(  184): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 2ms+1ms, total 16ms
D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 14ms
I/SearchController( 1204): #onHotwordDetectorStopped(false)
D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 0ms+1ms, total 12ms
I/MicrophoneInputStream( 1204): mic_close
I/MicroHotwordRecognitionRunner( 1204): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1204): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2957): Binding Chromium to main looper Looper (main, tid 1) {42b09818}
I/LibraryLoader( 2957): Expected native library version number "",actual native library version number ""
I/chromium( 2957): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2957): Initializing chromium process, renderers=0
D/BluetoothManagerService(  774): Message: 20
D/BluetoothManagerService(  774): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e5b598:true
I/Adreno-EGL( 2957): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2957): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/Icing   ( 1308): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
I/dalvikvm( 2957): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2957): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2957): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2957): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2957): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2957): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2957): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2957): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2957): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2957): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2957): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2957): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2957): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2957): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2957): CordovaWebView is running on device made by: LGE
,I/Icing   ( 1308): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
D/OpenGLRenderer( 2957): Enabling debug mode 0
W/AwContents( 2957): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  774): Displayed com.test.thalitest/.MainActivity: +322ms
I/Icing   ( 1308): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm(  774): GC_CONCURRENT freed 1678K, 49% free 29079K/56048K, paused 3ms+8ms, total 114ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 55ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 63ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 105ms
I/Icing   ( 1308): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/ActivityManager(  774): Killing 1839:com.google.android.deskclock/u0a33 (adj 15): empty #17
D/dalvikvm(  774): GC_CONCURRENT freed 3063K, 49% free 29118K/56048K, paused 4ms+6ms, total 79ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 70ms
D/dalvikvm( 2957): GC_CONCURRENT freed 232K, 2% free 16859K/17120K, paused 2ms+2ms, total 18ms
D/JsMessageQueue( 2957): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2957): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42b0db30
D/dalvikvm( 2957): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42b0db30
D/jxcore_app_log( 2957): JniHelper::setJavaVM(0x41aa2ed0), pthread_self() = 1981661768
D/JX-Cordova( 2957): jxcore cordova android initializing
D/dalvikvm(  774): GC_CONCURRENT freed 3107K, 49% free 29115K/56048K, paused 3ms+4ms, total 61ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/dalvikvm( 2957): GC_CONCURRENT freed 226K, 2% free 17144K/17400K, paused 2ms+1ms, total 11ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 2957): GC_CONCURRENT freed 158K, 2% free 17490K/17688K, paused 2ms+1ms, total 11ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2957): GC_CONCURRENT freed 155K, 2% free 17834K/18032K, paused 1ms+1ms, total 11ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2957): GC_CONCURRENT freed 151K, 2% free 18178K/18376K, paused 1ms+1ms, total 13ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2957): GC_CONCURRENT freed 157K, 2% free 18513K/18720K, paused 1ms+2ms, total 18ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm(  774): GC_CONCURRENT freed 3062K, 48% free 29159K/56048K, paused 3ms+5ms, total 62ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/dalvikvm( 2957): GC_CONCURRENT freed 175K, 2% free 18923K/19152K, paused 1ms+1ms, total 14ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2957): GC_CONCURRENT freed 215K, 2% free 19423K/19696K, paused 1ms+1ms, total 20ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2957): GC_CONCURRENT freed 274K, 2% free 20027K/20364K, paused 1ms+1ms, total 16ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm(  774): GC_CONCURRENT freed 3102K, 48% free 29177K/56048K, paused 3ms+4ms, total 76ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 68ms
D/dalvikvm( 2957): GC_CONCURRENT freed 319K, 2% free 20777K/21168K, paused 1ms+2ms, total 24ms
D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 394K, 3% free 21697K/22168K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm(  774): GC_CONCURRENT freed 3101K, 48% free 29202K/56048K, paused 3ms+5ms, total 70ms
,D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 951K, 5% free 22376K/23396K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm(  774): GC_CONCURRENT freed 3112K, 48% free 29220K/56048K, paused 3ms+4ms, total 66ms
,D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 1631K, 8% free 22519K/24300K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 184K, 8% free 22506K/24300K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2957): Grow heap (frag case) to 22.705MB for 733480-byte allocation
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 491K, 10% free 22730K/25020K, paused 20ms, total 20ms
,I/ActivityManager(  774): Force stopping com.google.android.youtube appid=10071 user=-1: replace sys pkg
,W/PackageManager(  774): Trying to update system app code path from /data/app/com.google.android.youtube-1.apk to /data/app/com.google.android.youtube-2.apk
,I/PackageManager(  774): Running dexopt on: com.google.android.youtube
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 808K, 10% free 22745K/25020K, paused 22ms, total 23ms
,I/dalvikvm-heap( 2957): Grow heap (frag case) to 23.288MB for 1100216-byte allocation
,D/dalvikvm( 2957): GC_FOR_ALLOC freed <1K, 9% free 23819K/26096K, paused 23ms, total 23ms
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 1959K, 12% free 23154K/26096K, paused 23ms, total 27ms
,I/dalvikvm-heap( 2957): Grow heap (frag case) to 24.211MB for 1650320-byte allocation
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 36K, 11% free 24729K/27708K, paused 21ms, total 21ms
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 3018K, 15% free 23791K/27708K, paused 25ms, total 29ms
,I/dalvikvm-heap( 2957): Grow heap (frag case) to 25.621MB for 2475476-byte allocation
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 26K, 14% free 26182K/30128K, paused 24ms, total 24ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 1776K, 19% free 24592K/30128K, paused 6ms+1ms, total 28ms
,D/dalvikvm( 3022): GC_FOR_ALLOC freed 35K, 2% free 2012K/2048K, paused 4ms, total 4ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 2565K, 19% free 24660K/30128K, paused 1ms+4ms, total 31ms
,D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 498K, 19% free 24492K/30128K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2957): Grow heap (frag case) to 27.485MB for 3713210-byte allocation
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 3K, 17% free 28114K/33756K, paused 22ms, total 22ms
,D/dalvikvm( 2957): GC_CONCURRENT freed 2740K, 24% free 25713K/33756K, paused 6ms+3ms, total 36ms
,D/dalvikvm( 2957): GC_FOR_ALLOC freed 510K, 25% free 25634K/33756K, paused 19ms, total 19ms
,W/jxcore-log( 2957): Initializing JXcore engine
,W/jxcore-log( 2957): JXcore engine is ready
,D/dalvikvm( 2957): GC_CONCURRENT freed 5350K, 32% free 23239K/33756K, paused 0ms+1ms, total 16ms
,D/dalvikvm( 2957): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/jxcore-log( 2957): Starting JXcore engine
,W/jxcore-log( 2957): Platform android
W/jxcore-log( 2957): 
,W/jxcore-log( 2957): Process ARCH arm
W/jxcore-log( 2957): 
,I/jxcore-log( 2957): JXcore Cordova bridge is ready!
I/jxcore-log( 2957): 
,W/jxcore-log( 2957): JXcore engine is started
,I/chromium( 2957): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  774): Killing 1796:com.google.android.calendar/u0a28 (adj 15): empty #17
,D/dalvikvm( 3022): DexOpt: load 314ms, verify+opt 1959ms, 7350316 bytes
,I/jxcore-log( 2957): Toggling radios to true
I/jxcore-log( 2957): 
,D/BluetoothAdapter( 2957): enable(): BT is already enabled..!
,I/jxcore-log( 2957): Radios toggled
I/jxcore-log( 2957): 
,D/BluetoothManagerService(  774): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiService(  774): setWifiEnabled: true pid=2957, uid=10108
I/jxcore-log( 2957): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2957): 
I/jxcore-log( 2957): Perf Test app loaded loaded
I/jxcore-log( 2957): 
I/Choreographer( 2957): Skipped 65 frames!  The application may be doing too much work on its main thread.
I/wpa_supplicant(  882): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  774): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  774): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  774): Attempting to switch to mobile
,D/ConnectivityService(  774): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  774): android_net_utils_resetConnections in env=0x770d3928 clazz=0x5d800001 iface=wlan0 mask=0x3
,D/ConnectivityService(  774): resetConnections(wlan0, 3)
,I/chromium( 2957): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2957): check test folder
I/jxcore-log( 2957): 
,I/jxcore-log( 2957): found test : ./testFindPeers.js
I/jxcore-log( 2957): 
I/ActivityManager(  774): Force stopping com.google.android.youtube appid=10071 user=-1: update pkg
,W/PackageManager(  774): Code path for pkg : com.google.android.youtube changing from /data/app/com.google.android.youtube-1.apk to /data/app/com.google.android.youtube-2.apk
,I/jxcore-log( 2957): found test : ./testSendData.js
I/jxcore-log( 2957): 
W/PackageManager(  774): Resource path for pkg : com.google.android.youtube changing from /data/app/com.google.android.youtube-1.apk to /data/app/com.google.android.youtube-2.apk
,V/NativeCrypto( 1131): Read error: ssl=0x7874f748: I/O error during system call, Connection timed out
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1131): SSL shutdown failed: ssl=0x7874f748: I/O error during system call, Broken pipe
D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=false
,W/PackageSettings(  774): Skipping PackageSetting{42c064f0 com.example.hello/10116} due to missing metadata
,W/PackageManager(  774): Unknown permission com.android.smspush.WAPPUSH_MANAGER_BIND in package com.android.phone
,W/PackageManager(  774): Unknown permission com.android.nfc.permission.NFCEE_ADMIN in package com.google.android.apps.walletnfcrel
,W/PackageManager(  774): Unknown permission com.android.vending.billing.IBillingAccountService.BIND2 in package com.google.android.gsf.login
W/PackageManager(  774): Unknown permission com.android.gallery3d.permission.GALLERY_PROVIDER in package com.android.bluetooth
,W/PackageManager(  774): Unknown permission android.permission.MMS_SEND_OUTBOX_MSG in package com.android.bluetooth
W/PackageManager(  774): Not granting permission android.permission.BROADCAST_PACKAGE_REMOVED to package com.google.android.marvin.talkback (protectionLevel=2 flags=0x40c9be45)
W/PackageManager(  774): Not granting permission android.permission.DEVICE_POWER to package com.google.android.deskclock (protectionLevel=2 flags=0xc8be45)
W/PackageManager(  774): Unknown permission android.permission.OBSERVE_GRANT_REVOKE_PERMISSIONS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.RECOVERY in package com.google.android.gms
W/PackageManager(  774): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gms (protectionLevel=2 flags=0x40c83ec5)
W/PackageManager(  774): Unknown permission android.permission.PROVIDE_TRUST_AGENT in package com.google.android.gms
W/PackageManager(  774): Unknown permission com.google.android.apps.enterprise.dmagent.permission.AutoSyncPermission in package com.google.android.gms
W/PackageManager(  774): Not granting permission android.permission.PACKAGE_USAGE_STATS to package com.google.android.gms (protectionLevel=18 flags=0x40c83ec5)
W/PackageManager(  774): Unknown permission com.google.android.googlequicksearchbox.permission.PAUSE_HOTWORD in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.MANAGE_VOICE_KEYPHRASES in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.REAL_GET_TASKS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.READ_WIFI_CREDENTIAL in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.SCORE_NETWORKS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.CONTROL_INCALL_EXPERIENCE in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.USER_ACTIVITY in package com.google.android.gms
,W/PackageManager(  774): Unknown permission android.permission.MODIFY_AUDIO_ROUTING in package com.google.android.gms
W/PackageManager(  774): Unknown permission com.google.android.wearable.READ_SETTINGS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.INTENT_FILTER_VERIFICATION_AGENT in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.LOCAL_MAC_ADDRESS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.CHANGE_DEVICE_IDLE_TEMP_WHITELIST in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.BODY_SENSORS in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.NOTIFY_PENDING_SYSTEM_UPDATE in package com.google.android.gms
W/PackageManager(  774): Unknown permission com.google.android.launcher.permission.RECEIVE_LAUNCH_BROADCASTS in package com.google.android.gms
,W/PackageManager(  774): Unknown permission com.android.voicemail.permission.READ_VOICEMAIL in package com.google.android.gms
W/PackageManager(  774): Unknown permission android.permission.READ_OWNER_DATA in package com.google.android.setupwizard
,W/PackageManager(  774): Unknown permission android.permission.WRITE_OWNER_DATA in package com.google.android.setupwizard
W/PackageManager(  774): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.android.settings
W/PackageManager(  774): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.android.settings
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.redbend.vdmc
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.redbend.vdmc
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.redbend.vdmc
,W/PackageManager(  774): Unknown permission com.sprint.internal.permission.PLATFORM in package com.redbend.vdmc
W/PackageManager(  774): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.googlequicksearchbox
,W/PackageManager(  774): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  774): Unknown permission com.google.android.voicesearch.SHORTCUTS_ACCESS in package com.google.android.googlequicksearchbox
W/PackageManager(  774): Unknown permission com.google.android.voicesearch.ACCESS_SETTINGS in package com.google.android.googlequicksearchbox
W/PackageManager(  774): Unknown permission com.android.browser.permission.PRELOAD in package com.google.android.googlequicksearchbox
W/PackageManager(  774): Unknown permission com.google.android.apps.googlevoice.permission.AUTO_SEND in package com.google.android.googlequicksearchbox
,W/PackageManager(  774): Unknown permission com.android.chrome.PRERENDER_URL in package com.google.android.googlequicksearchbox
,W/PackageManager(  774): Unknown permission com.google.android.gms.permission.CAR_SPEED in package com.google.android.apps.maps
W/PackageManager(  774): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.launcher
W/PackageManager(  774): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.launcher
,W/PackageManager(  774): Unknown permission android.permission.WRITE_SYNC_STATS in package com.google.android.apps.docs
W/PackageManager(  774): Unknown permission com.android.launcher.permission.READ_SETTINGS in package com.google.android.onetimeinitializer
,W/PackageManager(  774): Unknown permission com.android.launcher.permission.WRITE_SETTINGS in package com.google.android.onetimeinitializer
W/PackageManager(  774): Unknown permission com.android.launcher.permission.PRELOAD_WORKSPACE in package com.google.android.partnersetup
,W/PackageManager(  774): Unknown permission android.permission.REGISTER_CONNECTION_MANAGER in package com.google.android.talk
,W/PackageManager(  774): Not granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS to package com.android.vending (protectionLevel=2 flags=0x408abe45)
,W/PackageManager(  774): Unknown permission android.permission.SEND_SMS_NO_CONFIRMATION in package com.android.vending
,W/PackageManager(  774): Not granting permission android.permission.BIND_WALLPAPER to package com.google.android.GoogleCamera (protectionLevel=18 flags=0xd83cc5)
,W/PackageManager(  774): Not granting permission android.permission.READ_DREAM_STATE to package com.google.android.gsf (protectionLevel=2 flags=0x40883e45)
W/PackageManager(  774): Unknown permission com.chrome.permission.DEVICE_EXTRAS in package com.android.chrome
,W/PackageManager(  774): Unknown permission com.sec.enterprise.knox.MDM_CONTENT_PROVIDER in package com.android.chrome
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES in package com.lge.SprintHiddenMenu
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.SYSTEMPROPERTIES_WRITE in package com.lge.SprintHiddenMenu
,W/PackageManager(  774): Unknown permission com.sprint.internal.permission.CONNECTIONMANAGER in package com.lge.SprintHiddenMenu
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.PLATFORM in package com.lge.SprintHiddenMenu
W/PackageManager(  774): Unknown permission com.sprint.internal.permission.OMADM in package com.lge.SprintHiddenMenu
W/PackageManager(  774): Unknown permission android.permission.FACTORY in package com.lge.SprintHiddenMenu
W/PackageManager(  774): Unknown permission com.lge.permission.LGHIDDEN in package com.lge.SprintHiddenMenu
,W/PackageManager(  774): Unknown permission android.permission.MMS_PUSH in package com.lge.SprintHiddenMenu
,W/PackageManager(  774): Not granting permission android.permission.MANAGE_DOCUMENTS to package com.google.android.youtube (protectionLevel=2 flags=0x583ec5)
,W/PackageSettings(  774): Skipping PackageSetting{42c064f0 com.example.hello/10116} due to missing metadata
,D/ConnectivityService(  774): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  774): Killing 1882:com.google.android.gm/u0a41 (adj 15): empty #17
,I/ActivityManager(  774): Force stopping com.google.android.youtube appid=10071 user=0: pkg removed
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  774): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 1053): GC_EXPLICIT freed 1342K, 8% free 26151K/28288K, paused 1ms+3ms, total 22ms
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  774): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.google.android.youtube flg=0x4000010 (has extras) }
,I/InputReader(  774): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/BackupManagerService(  774): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.google.android.youtube flg=0x4000010 (has extras) }
,V/BackupManagerService(  774): removePackageParticipantsLocked: uid=10071 #1
,V/BackupManagerService(  774): addPackageParticipantsLocked: #1
,D/dalvikvm(  774): GC_CONCURRENT freed 3056K, 48% free 29302K/56048K, paused 6ms+16ms, total 87ms
,D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 59ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 59ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 49ms
D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 59ms
,D/dalvikvm(  774): WAIT_FOR_CONCURRENT_GC blocked 59ms
,I/Launcher( 1053): Deferring update until onResume
,I/InputReader(  774): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Launcher( 1053): Deferring update until onResume
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "mmsto"
,D/dalvikvm(  774): GC_EXPLICIT freed 2962K, 53% free 26570K/56048K, paused 5ms+5ms, total 94ms
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Launcher( 1053): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42b0ed80 new=com.google.android.velvet.VelvetApplication@42b0ed80
,D/Finsky  ( 2392): [164] 1.packageInstalled: Package install status for "com.google.android.youtube" is 1
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/ContextImpl( 2598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/Finsky  ( 2392): [1] InstallerImpl.kick: Installer kick null - starting com.google.android.apps.books
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
,D/PackageBroadcastService( 1308): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.google.android.youtube
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  774): Delay finish: com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  774): Resuming delayed broadcast
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1308): Module APK com.google.android.play.games already loaded
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/NetworkScheduler.SchedulerReceiver( 1131): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1131): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ElegantRequestDirector( 2392): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0x76b029e0: I/O error during system call, Broken pipe
,I/ElegantRequestDirector( 2392): Retrying request
,I/qtaguid ( 2392): Failed write_ctrl(u 52) res=-1 errno=22
I/qtaguid ( 2392): Untagging socket 52 failed errno=-22
,W/NetworkManagementSocketTagger( 2392): untagSocket(52) failed with errno -22
W/SocketClient(  180): write error (Broken pipe)
,D/Finsky  ( 2392): [1] 2.onErrorResponse: Received VolleyError 923 (null)
,D/Finsky  ( 2392): [1] InstallerTask.cancelCleanup: Cancel running installation of com.google.android.apps.books
D/ConnectivityService(  774): handleInetConditionChange: no active default network - ignore
,I/Icing.InternalIcingCorporaProvider( 1204): Updating corpora: A: com.google.android.youtube, C: MAYBE
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1308): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1308): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.google.android.youtube
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1308): Module APK com.google.android.play.games already loaded
I/ActivityManager(  774): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/dalvikvm( 1308): GC_CONCURRENT freed 772K, 5% free 19141K/20004K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 1308): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 1308): WAIT_FOR_CONCURRENT_GC blocked 6ms
,I/Icing.InternalIcingCorporaProvider( 1204): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1308): Submit a task: k
I/ActivityManager(  774): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1308): Processing package: com.google.android.youtube
I/ActivityManager(  774): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/b       ( 1308): Look up (com.google.android.youtube:108959634) returned no result
,D/k       ( 1308): Starting Hash for package com.google.android.youtube:10.49.59
,D/k       ( 1308): Package com.google.android.youtube's hash: a2bf43955f938661019ff9c62ea12e80144cb4f65ec299ac89b27bfadabf8481
,D/b       ( 1308): Look up (com.google.android.youtube:108959634) returned no result
,D/k       ( 1308): Saved the app info in cache for package:com.google.android.youtube.
,I/wpa_supplicant(  882): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  882): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/ActivityManager(  774): Resuming delayed broadcast
I/wpa_supplicant(  882): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  882): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/GCM     ( 1131): GcmService start Intent { act=com.google.android.gms.gcm.PACKAGE_REPLACED cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gms.gcm.PACKAGE_REPLACED
,I/ActivityManager(  774): Delay finish: com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  774): Resuming delayed broadcast
,W/Launcher( 1053): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42b0ed80 new=com.google.android.velvet.VelvetApplication@42b0ed80
,D/PackageBroadcastService( 1308): Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.google.android.youtube
I/ActivityManager(  774): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,E/WifiStateMachine(  774): scanCount==0 - aborting
,D/dalvikvm( 1308): GC_FOR_ALLOC freed 239K, 5% free 19105K/20004K, paused 28ms, total 28ms
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1308): Submit a task: k
,D/ChimeraCfgMgr( 1308): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1308): Processing package: com.google.android.youtube
,I/ActivityManager(  774): Resuming delayed broadcast
D/GassUtils( 1308): Found app info for package com.google.android.youtube:108959634. Hash: a2bf43955f938661019ff9c62ea12e80144cb4f65ec299ac89b27bfadabf8481
D/k       ( 1308): Found info for package com.google.android.youtube in db.
,E/NetworkScheduler.SchedulerReceiver( 1131): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1131): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  774): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3114 uid=10071 gids={50071, 3003, 1028, 1015}
I/ActivityManager(  774): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
,W/MultiDex( 3114): Trying to delete old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-1.apk.classes2.dex of size 613080
W/MultiDex( 3114): Deleted old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-1.apk.classes2.dex
W/MultiDex( 3114): Trying to delete old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-1.apk.classes2.zip of size 266748
,W/MultiDex( 3114): Deleted old file /data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-1.apk.classes2.zip
,D/dalvikvm( 3114): GC_CONCURRENT freed 202K, 2% free 16963K/17196K, paused 2ms+2ms, total 13ms
,D/dalvikvm( 3114): GC_CONCURRENT freed 127K, 1% free 17290K/17460K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 3114): DexOpt: --- BEGIN 'com.google.android.youtube-2.apk.classes2.zip' (bootstrap=0) ---
,I/Icing   ( 1308): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1204): GC_CONCURRENT freed 1304K, 8% free 17913K/19404K, paused 2ms+2ms, total 15ms
,I/Icing   ( 1308): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1308): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/ActivityManager(  774): Resuming delayed broadcast
,I/Icing   ( 1308): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/dalvikvm( 3142): DexOpt: load 24ms, verify+opt 79ms, 1037372 bytes
,D/dalvikvm( 3114): DexOpt: --- END 'com.google.android.youtube-2.apk.classes2.zip' (success) ---
,D/dalvikvm( 3114): DEX prep '/data/data/com.google.android.youtube/files/secondary-dexes/com.google.android.youtube-2.apk.classes2.zip': unzip in 10ms, rewrite 185ms
,I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method epz.a
,W/dalvikvm( 3114): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 3114): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3114): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3114): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3114): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3114): VFY: unable to resolve instance field 36
,D/dalvikvm( 3114): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3114): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3114): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3114): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3114): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3114): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3114): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bdda30
D/dalvikvm( 3114): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bdda30
,D/dalvikvm( 3114): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bdda30, skipping init
,D/dalvikvm( 3114): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bdda30
D/dalvikvm( 3114): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bdda30
,V/JNIHelp ( 3114): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 3114): GC_CONCURRENT freed 334K, 2% free 17511K/17816K, paused 2ms+4ms, total 25ms
,D/dalvikvm( 3114): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42bdda30
,D/dalvikvm( 3114): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42bdda30
D/dalvikvm( 3114): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42bdda30
,D/dalvikvm( 3114): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42bdda30
,D/dalvikvm( 3114): GC_CONCURRENT freed 881K, 6% free 17143K/18052K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 3114): WAIT_FOR_CONCURRENT_GC blocked 7ms
,I/dalvikvm-heap( 3114): Grow heap (frag case) to 16.848MB for 79892-byte allocation
,D/dalvikvm( 3114): GC_FOR_ALLOC freed 10K, 6% free 17215K/18132K, paused 9ms, total 9ms
,I/dalvikvm( 3114): Could not find method android.app.Activity.finishAfterTransition, referenced from method cf.onBackPressed
,W/dalvikvm( 3114): VFY: unable to resolve virtual method 2379: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0012
,I/ProviderInstaller( 3114): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3114): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 3114): GC_CONCURRENT freed 282K, 5% free 17372K/18132K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 3114): GC_CONCURRENT freed 345K, 4% free 17539K/18132K, paused 2ms+1ms, total 15ms
,D/dalvikvm( 3114): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 3114): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 3114): GC_CONCURRENT freed 190K, 2% free 17820K/18132K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 3114): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/dalvikvm( 3114): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 3114): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 3114): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 3114): DexOpt: --- BEGIN 'ads-2095122182.jar' (bootstrap=0) ---
,D/dalvikvm( 3114): GC_CONCURRENT freed 308K, 2% free 18021K/18360K, paused 5ms+11ms, total 32ms
,W/InstanceID/Rpc( 3114): Found 10007
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asf.getActivityBanner
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2824: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asf.getActivityBanner
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2825: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asf.getApplicationBanner
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2832: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asf.getApplicationBanner
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2833: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method asf.getLeanbackLaunchIntentForPackage
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2849: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method asf.getPackageInstaller
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method asf.getUserBadgedDrawableForDensity
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2869: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method asf.getUserBadgedIcon
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2870: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 3114): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method asf.getUserBadgedLabel
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2871: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0002
,D/dalvikvm( 3176): DexOpt: load 2ms, verify+opt 7ms, 188892 bytes
,D/dalvikvm( 3114): DexOpt: --- END 'ads-2095122182.jar' (success) ---
,D/dalvikvm( 3114): DEX prep '/data/data/com.google.android.youtube/cache/ads-2095122182.jar': unzip in 4ms, rewrite 67ms
,I/dalvikvm( 3114): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.a
,W/dalvikvm( 3114): VFY: unable to resolve virtual method 4039: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 3114): Could not find method android.content.Context.getSystemService, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.a
W/dalvikvm( 3114): VFY: unable to resolve virtual method 2688: Landroid/content/Context;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3114): VFY: replacing opcode 0x6e at 0x0011
,D/MarketUpdateReceiver( 1053): market has installed: com.google.android.youtube
,D/dalvikvm( 3114): GC_CONCURRENT freed 298K, 2% free 18143K/18472K, paused 2ms+12ms, total 30ms
,I/Icing   ( 1308): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1308): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/MarketUpdateReceiver( 1053): market has decided not to install: com.google.android.apps.books
,D/ConnectivityService(  774): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  774): Killing 1598:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/WifiStateMachine(  774): VerifyingLinkState enter
D/WifiStateMachine(  774): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  774): CaptivePortalCheckState enter
,D/WifiStateMachine(  774): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/dalvikvm( 1131): GC_CONCURRENT freed 408K, 4% free 17988K/18676K, paused 2ms+1ms, total 14ms
D/ConnectivityService(  774): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  774): Unexpected mtu value: android.net.wifi.WifiStateTracker@42e4fae8
,D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 3114): GC_CONCURRENT freed 340K, 2% free 18209K/18580K, paused 2ms+2ms, total 17ms
,D/Tethering(  774): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  774): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2766): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@42b45fb0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2766): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1308): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1308): onCreate
,D/SystemUpdateService( 1308): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1308): active receiver: enabled
,I/SystemUpdateService( 1308): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1308): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1308): now status is 0 (complete)
I/SystemUpdateService( 1308): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1308): file has been verified
,I/SystemUpdateService( 1308): OTA package size = 2571501
,I/SystemUpdateService( 1308): showing system update notification
I/ActivityManager(  774): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3262 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1308): onDestroy
,D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3262): VFY: unable to resolve instance field 68
,D/dalvikvm( 3262): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3262): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3262): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3262): VFY: unable to resolve instance field 68
,D/dalvikvm( 3262): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3262): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3262): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3262): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3262): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  774): Killing 2766:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  774): Service ServiceRecord{439166b0 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{432b1fd0 2766:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{437bccf0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432b1fd0 2766:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{4379d460 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{432b1fd0 2766:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{4376c420 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{432b1fd0 2766:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{435c45e0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432b1fd0 2766:com.google.android.music:main/u0a58} not same as in map: null
,D/dalvikvm(  774): GC_CONCURRENT freed 2353K, 53% free 26675K/56048K, paused 2ms+6ms, total 55ms
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  774): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  774): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  774):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2957): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 2957): 
,D/dalvikvm( 1204): GC_CONCURRENT freed 404K, 8% free 17925K/19404K, paused 2ms+1ms, total 18ms
,D/Tethering(  774): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  774): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1308): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1308): onCreate
,D/SystemUpdateService( 1308): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1308): active receiver: enabled
,I/SystemUpdateService( 1308): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1308): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1308): now status is 0 (complete)
I/SystemUpdateService( 1308): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1308): file has been verified
,I/SystemUpdateService( 1308): OTA package size = 2571501
,I/SystemUpdateService( 1308): showing system update notification
,D/SystemUpdateService( 1308): onDestroy
,D/dalvikvm( 1308): GC_CONCURRENT freed 710K, 5% free 19112K/20004K, paused 2ms+2ms, total 27ms
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/InputReader(  774): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  774):   Scheme: "sms"
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
,I/Launcher( 1053): Deferring update until onResume
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
,I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1053): Deferring update until onResume
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "sms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "smsto"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mms"
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  774):   Action: "android.intent.action.SENDTO"
I/PackageManager(  774):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  774):   Scheme: "mmsto"
,I/Icing.InternalIcingCorporaProvider( 1204): Updating corpora: A: com.google.android.gms, C: MAYBE
I/PackageManager(  774): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Launcher( 1053): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42b0ed80 new=com.google.android.velvet.VelvetApplication@42b0ed80
,I/ActivityManager(  774): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  774): Resuming delayed broadcast
,D/PackageBroadcastService( 1308): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  774): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 1308): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  774): Resuming delayed broadcast
,I/GCoreNlp(  983): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 1308): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1308): GC_CONCURRENT freed 733K, 5% free 19122K/20000K, paused 1ms+2ms, total 21ms
,I/Icing.InternalIcingCorporaProvider( 1204): UpdateCorporaTask done [took 302 ms] updated apps [took 302 ms] 
,I/Icing   ( 1308): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1308): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1308): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1204): GC_CONCURRENT freed 395K, 8% free 17920K/19396K, paused 3ms+2ms, total 17ms
,I/Icing   ( 1308): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,D/CaptivePortalTracker(  774): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  774): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  774): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  774): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  774): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  774): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  774): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 2392): GC_CONCURRENT freed 983K, 6% free 19734K/20900K, paused 2ms+2ms, total 25ms
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2392): [1] 5.onFinished: Installation state replication succeeded.
,I/rmt_storage(  179): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8d9f160
I/rmt_storage(  179): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  179): wakelock acquired: 1, error no: 2
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193676256)
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193676256) wakelock released: 1, error no: 0
I/rmt_storage(  179): 
,I/rmt_storage(  179): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8d9f160
,I/EventLogService( 1308): Aggregate from 1450436224442 (log), 1450436224442 (data)
,D/dalvikvm( 1131): GC_CONCURRENT freed 449K, 4% free 18037K/18676K, paused 3ms+2ms, total 46ms
,D/dalvikvm( 1308): GC_CONCURRENT freed 687K, 5% free 19166K/20000K, paused 3ms+3ms, total 25ms
,I/VacuumService(  983): Vacuum at: now=1450438024681 tag=VacuumService
,D/dalvikvm( 1131): GC_CONCURRENT freed 461K, 4% free 17964K/18676K, paused 2ms+1ms, total 17ms
,D/dalvikvm(  983): GC_CONCURRENT freed 464K, 3% free 18852K/19408K, paused 3ms+5ms, total 26ms
,I/PhenotypeConfigurator(  983): Scheduling Phenotype for one-off execution 11951 seconds from now (1450438024920)
,D/GetConfigurationSnapshotOperation(  983): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 1131): GC_CONCURRENT freed 380K, 4% free 17971K/18676K, paused 2ms+1ms, total 18ms
,I/PhenotypeFlagCommitter(  983): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  983): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  983): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  983): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  983): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  983): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  983): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  983): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  983): GC_CONCURRENT freed 586K, 4% free 18897K/19588K, paused 8ms+3ms, total 40ms
,D/dalvikvm(  983): GC_CONCURRENT freed 645K, 4% free 18953K/19692K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  983): GC_CONCURRENT freed 460K, 3% free 19165K/19720K, paused 3ms+4ms, total 23ms
,D/dalvikvm(  983): GC_CONCURRENT freed 724K, 5% free 19191K/20008K, paused 3ms+4ms, total 22ms
,D/dalvikvm(  983): GC_CONCURRENT freed 763K, 5% free 19184K/20040K, paused 2ms+3ms, total 21ms
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1131): Read error: ssl=0x78695370: I/O error during system call, Connection timed out
,V/NativeCrypto( 1131): SSL shutdown failed: ssl=0x78695370: I/O error during system call, Broken pipe
,D/dalvikvm( 1131): GC_CONCURRENT freed 395K, 4% free 17986K/18676K, paused 3ms+2ms, total 30ms
,D/dalvikvm(  983): GC_FOR_ALLOC freed 671K, 6% free 18979K/20128K, paused 32ms, total 32ms
,I/PowerManagerService(  774): Going to sleep due to screen timeout...
,I/Adreno-EGL(  774): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  183): Screen released, type=0 flinger=0xb7035450
,D/qdhwcomposer(  183): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  183): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  774): Excessive delay in blankDisplay() while turning screen off: 294ms
,V/KeyguardServiceDelegate(  774): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@44face78)
,V/KeyguardServiceDelegate(  774): **** SHOWN CALLED ****
I/WindowManager(  774): No lock screen! windowToken=null
,D/NfcService( 1037): NFC-C OFF
,I/ActivityManager(  774): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3490 uid=10033 gids={50033, 1028}
,D/dalvikvm(  774): GC_EXPLICIT freed 1989K, 53% free 26706K/56048K, paused 2ms+6ms, total 64ms
,I/ActivityManager(  774): Killing 2538:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/jxcore-log( 2957): Connected to the server!
I/jxcore-log( 2957): 
,I/chromium( 2957): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2957): --- start :testFindPeers.js---
I/jxcore-log( 2957): 
,I/jxcore-log( 2957): testFindPeers created [object Object]
I/jxcore-log( 2957): 
,I/jxcore-log( 2957): serverPort is 8876
I/jxcore-log( 2957): 
,I/dalvikvm( 2957): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 2957): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 2957): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 2957): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2957): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 2957): Shutting down VM
,W/dalvikvm( 2957): threadid=1: thread exiting with uncaught exception (group=0x41ab4ba8)
E/AndroidRuntime( 2957): FATAL EXCEPTION: main
E/AndroidRuntime( 2957): Process: com.test.thalitest, PID: 2957
E/AndroidRuntime( 2957): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 2957): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 2957): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 2957): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 2957): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 2957): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 2957): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 2957): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 2957): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 2957): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 2957): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2957): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2957): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2957): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2957): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2957): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2957): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2957): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  774):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  774): Killing 2598:com.android.keychain/1000 (adj 15): empty #17
,I/Process ( 2957): Sending signal. PID: 2957 SIG: 9
,I/ActivityManager(  774): Process com.test.thalitest (pid 2957) has died.
,I/WindowState(  774): WIN DEATH: Window{42e99450 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/dalvikvm( 3114): GC_CONCURRENT freed 443K, 3% free 18280K/18752K, paused 2ms+6ms, total 29ms
,D/dalvikvm( 3114): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ProcessStatsService(  774): Prepared write state in 41ms
,I/ProcessStatsService(  774): Prepared write state in 4ms
,I/ProcessStatsService(  774): Pruning old procstats: /data/system/procstats/state-2015-12-17-14-09-58.bin
,I/ActivityManager(  774): Killing 2779:com.google.android.apps.cloudprint/u0a32 (adj 15): empty for 1801s
,I/ActivityManager(  774): Killing 2722:com.google.android.apps.magazines/u0a56 (adj 15): empty for 1801s
,I/ActivityManager(  774): Killing 2577:com.android.musicfx/u0a13 (adj 15): empty for 1801s
,I/ActivityManager(  774): Killing 2660:com.quickoffice.android/u0a65 (adj 15): empty for 1801s
,I/ActivityManager(  774): Killing 2620:com.google.android.apps.docs/u0a35 (adj 15): empty for 1801s
,I/ActivityManager(  774): Killing 2687:com.google.android.partnersetup/u0a11 (adj 15): empty for 1802s
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1131): GC_CONCURRENT freed 468K, 4% free 17981K/18676K, paused 3ms+1ms, total 15ms
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1800000ms)
```
