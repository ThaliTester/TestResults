#### Test 50242285ae22b3b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4120): 
D/AndroidRuntime( 4120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4120): CheckJNI is OFF
D/dalvikvm( 4120): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4120): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4120): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4120): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4120): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4120): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4120): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4120): failed to load memtrack module: -2
D/AndroidRuntime( 4120): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4120
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4136 uid=10523 gids={50523, 3003, 3001, 3002}
D/AndroidRuntime( 4120): Shutting down VM
D/dalvikvm( 4120): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4136): Binding Chromium to main looper Looper (main, tid 1) {41f8b910}
I/LibraryLoader( 4136): Expected native library version number "",actual native library version number ""
I/chromium( 4136): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4136): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422e0558:true
I/Adreno-EGL( 4136): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4136): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4136): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4136): Local Branch: 
I/Adreno-EGL( 4136): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4136): Local Patches: NONE
I/Adreno-EGL( 4136): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4136): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4136): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4136): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4136): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4136): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4136): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4136): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4136): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4136): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4136): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4136): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4136): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4136): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4136): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4136): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4136): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4136): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4136): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4136): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4136): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4136): Enabling debug mode 0
,W/AwContents( 4136): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4136): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.example.hello/.MainActivity,cp,ca,320
I/ActivityManager( 1017): Displayed com.example.hello/.MainActivity: +290ms (total +320ms)
,I/chromium( 4136): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 4136): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 4136): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4136): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f900d0
,D/dalvikvm( 4136): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f900d0
,D/jxcore_app_log( 4136): JniHelper::setJavaVM(0x415ddfa8), pthread_self() = 1609693432
,D/JX-Cordova( 4136): jxcore cordova android initializing
,W/jxcore-log( 4136): Initializing JXcore engine
,W/jxcore-log( 4136): JXcore engine is ready
,W/jxcore-log( 4136): Starting JXcore engine
,F/libc    ( 4136): Fatal signal 11 (SIGSEGV) at 0x00000000 (code=1), thread 4181 (Thread-365)
,I/DEBUG   (  271): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
I/DEBUG   (  271): Build fingerprint: 'motorola/peregrine_reteu/peregrine:4.4.4/KXB21.14-L1.46/42:user/release-keys'
I/DEBUG   (  271): Revision: 'p2d0'
I/DEBUG   (  271): pid: 4136, tid: 4181, name: Thread-365  >>> com.example.hello <<<
,I/DEBUG   (  271): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 00000000
,I/DEBUG   (  271):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
,I/DEBUG   (  271):     r4 626bcfb0  r5 626bcf70  r6 6245af10  r7 626bcf70
I/DEBUG   (  271):     r8 00000000  r9 626bcfac  sl 626be508  fp 626bcf54
I/DEBUG   (  271):     ip 635cfba0  sp 626bcf38  lr 632d6308  pc 400de4ac  cpsr 600d0030
I/DEBUG   (  271):     d0  5701003a0f000000  d1  0000008851030000
,I/DEBUG   (  271):     d2  563e0a0000003502  d3  000000b80c030000
I/DEBUG   (  271):     d4  0061007400530065  d5  0073002e00650074
I/DEBUG   (  271):     d6  003d0063006e0079  d7  0073006c00610066
I/DEBUG   (  271):     d8  0000000000000000  d9  0000000000000000
,I/DEBUG   (  271):     d10 0000000000000000  d11 0000000000000000
I/DEBUG   (  271):     d12 0000000000000000  d13 0000000000000000
I/DEBUG   (  271):     d14 0000000000000000  d15 0000000000000000
I/DEBUG   (  271):     d16 0088000000560a10  d17 0a00000035020000
I/DEBUG   (  271):     d18 1b0000004549ffd7  d19 00b80c0200005651
,I/DEBUG   (  271):     d20 01003a3e0a0d0000  d21 0007490c0000003d
I/DEBUG   (  271):     d22 0c00000088490000  d23 3d0a0e000000b80c
I/DEBUG   (  271):     d24 3f56c16c16c76a94  d25 3f81111111185da8
I/DEBUG   (  271):     d26 3fa555555555551c  d27 3fc55555555554db
,I/DEBUG   (  271):     d28 3fe0000000000000  d29 0000000000000001
I/DEBUG   (  271):     d30 fff0000000000000  d31 0000000000000000
I/DEBUG   (  271):     scr 88000012
,I/DEBUG   (  271): 
I/DEBUG   (  271): backtrace:
I/DEBUG   (  271):     #00  pc 000234ac  /system/lib/libc.so (strlen+83)
I/DEBUG   (  271):     #01  pc 007da304  /data/app-lib/com.example.hello-1/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
I/DEBUG   (  271): 
I/DEBUG   (  271): stack:
,I/DEBUG   (  271):          626bcef8  6382b040  
I/DEBUG   (  271):          626bcefc  626c8ee0  
I/DEBUG   (  271):          626bcf00  62786a78  
I/DEBUG   (  271):          626bcf04  00000001  
I/DEBUG   (  271):          626bcf08  63849160  
I/DEBUG   (  271):          626bcf0c  6245af10  
,I/DEBUG   (  271):          626bcf10  6384f1c0  
I/DEBUG   (  271):          626bcf14  00000000  
I/DEBUG   (  271):          626bcf18  00000000  
I/DEBUG   (  271):          626bcf1c  00000000  
I/DEBUG   (  271):          626bcf20  00000003  
,I/DEBUG   (  271):          626bcf24  000000aa  
I/DEBUG   (  271):          626bcf28  0000006b  
I/DEBUG   (  271):          626bcf2c  0001416e  
I/DEBUG   (  271):          626bcf30  e3a070ad  
I/DEBUG   (  271):          626bcf34  ef9000ad  
,I/DEBUG   (  271):     #00  626bcf38  00000000  
I/DEBUG   (  271):          ........  ........
I/DEBUG   (  271):     #01  626bcf38  00000000  
I/DEBUG   (  271):          626bcf3c  626bcf94  [stack:4181]
I/DEBUG   (  271):          626bcf40  626bcfb0  [stack:4181]
I/DEBUG   (  271):          626bcf44  626bcf94  [stack:4181]
,I/DEBUG   (  271):          626bcf48  626bcf80  [stack:4181]
I/DEBUG   (  271):          626bcf4c  00000000  
I/DEBUG   (  271):          626bcf50  626bdfcc  [stack:4181]
I/DEBUG   (  271):          626bcf54  632ad3f0  /data/app-lib/com.example.hello-1/libjxcore.so
I/DEBUG   (  271):          626bcf58  626bcf88  [stack:4181]
,I/DEBUG   (  271):          626bcf5c  00000000  
I/DEBUG   (  271):          626bcf60  626bcf7c  [stack:4181]
I/DEBUG   (  271):          626bcf64  630df184  /data/app-lib/com.example.hello-1/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
I/DEBUG   (  271):          626bcf68  00000000  
I/DEBUG   (  271):          626bcf6c  00000000  
,I/DEBUG   (  271):          626bcf70  40109394  
I/DEBUG   (  271):          626bcf74  00000000  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near r4:
I/DEBUG   (  271):     626bcf90 63851d80 63853b00 6245af10 00000000  
I/DEBUG   (  271):     626bcfa0 62786968 62786978 00000001 4010002f  
I/DEBUG   (  271):     626bcfb0 00001000 40109394 00001000 6245af10  
I/DEBUG   (  271):     626bcfc0 62786a10 626bcfd8 626bd354 631bbab0  
,I/DEBUG   (  271):     626bcfd0 00000002 00000000 62786a10 00000000  
I/DEBUG   (  271):     626bcfe0 635c1f28 00000001 63853b00 626bcfd8  
I/DEBUG   (  271):     626bcff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626bd000 00000000 00000000 00000002 626bc861  
I/DEBUG   (  271):     626bd010 63900100 ffffffff 00000040 626bd450  
I/DEBUG   (  271):     626bd020 40109200 626bd450 6369ebb8 400cc03b  
I/DEBUG   (  271):     626bd030 00000040 d0000220 400caf9d 00000001  
I/DEBUG   (  271):     626bd040 626bd450 00000040 62468fb8 6382b940  
,I/DEBUG   (  271):     626bd050 0000000c 6369ebb8 626bd450 00000040  
I/DEBUG   (  271):     626bd060 0000000c 63114a20 626bd548 00000001  
I/DEBUG   (  271):     626bd070 639006d0 00000068 00000000 00000000  
I/DEBUG   (  271):     626bd080 00000000 00000000 626bd098 00000000  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near r5:
,I/DEBUG   (  271):     626bcf50 626bdfcc 632ad3f0 626bcf88 00000000  
I/DEBUG   (  271):     626bcf60 626bcf7c 630df184 00000000 00000000  
I/DEBUG   (  271):     626bcf70 40109394 00000000 626bd304 631bbb34  
I/DEBUG   (  271):     626bcf80 6245af10 6245af10 62786a78 00000001  
I/DEBUG   (  271):     626bcf90 63851d80 63853b00 6245af10 00000000  
,I/DEBUG   (  271):     626bcfa0 62786968 62786978 00000001 4010002f  
I/DEBUG   (  271):     626bcfb0 00001000 40109394 00001000 6245af10  
I/DEBUG   (  271):     626bcfc0 62786a10 626bcfd8 626bd354 631bbab0  
I/DEBUG   (  271):     626bcfd0 00000002 00000000 62786a10 00000000  
I/DEBUG   (  271):     626bcfe0 635c1f28 00000001 63853b00 626bcfd8  
,I/DEBUG   (  271):     626bcff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626bd000 00000000 00000000 00000002 626bc861  
I/DEBUG   (  271):     626bd010 63900100 ffffffff 00000040 626bd450  
I/DEBUG   (  271):     626bd020 40109200 626bd450 6369ebb8 400cc03b  
I/DEBUG   (  271):     626bd030 00000040 d0000220 400caf9d 00000001  
I/DEBUG   (  271):     626bd040 626bd450 00000040 62468fb8 6382b940  
,I/DEBUG   (  271): 
I/DEBUG   (  271): memory near r6:
I/DEBUG   (  271):     6245aef0 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     6245af00 00000000 00000000 00000000 000000ab  
I/DEBUG   (  271):     6245af10 626c8ee0 627b8978 62468fb8 626be898  
I/DEBUG   (  271):     6245af20 00000000 626c8f2c 62468fd4 00000000  
,I/DEBUG   (  271):     6245af30 00000001 626ca334 626ca334 00000000  
I/DEBUG   (  271):     6245af40 00000000 ffffff82 00000000 00000000  
I/DEBUG   (  271):     6245af50 00000003 00000000 00000000 00000000  
I/DEBUG   (  271):     6245af60 6245af70 00000000 00000001 00000000  
I/DEBUG   (  271):     6245af70 00000000 00000000 6245af10 636b38d8  
,I/DEBUG   (  271):     6245af80 00000003 00000000 1e000000 63260ef8  
I/DEBUG   (  271):     6245af90 6241bfcc 00000000 00000001 00000000  
I/DEBUG   (  271):     6245afa0 00000002 ffffff84 00000000 00000000  
I/DEBUG   (  271):     6245afb0 00000000 0000001b 627b9008 00000005  
I/DEBUG   (  271):     6245afc0 00000680 14000000 00000000 00000013  
I/DEBUG   (  271):     6245afd0 63716d20 00000000 00000010 0000001b  
,I/DEBUG   (  271):     6245afe0 62456000 00005000 62441fe0 00000001  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near r7:
I/DEBUG   (  271):     626bcf50 626bdfcc 632ad3f0 626bcf88 00000000  
I/DEBUG   (  271):     626bcf60 626bcf7c 630df184 00000000 00000000  
,I/DEBUG   (  271):     626bcf70 40109394 00000000 626bd304 631bbb34  
I/DEBUG   (  271):     626bcf80 6245af10 6245af10 62786a78 00000001  
I/DEBUG   (  271):     626bcf90 63851d80 63853b00 6245af10 00000000  
I/DEBUG   (  271):     626bcfa0 62786968 62786978 00000001 4010002f  
I/DEBUG   (  271):     626bcfb0 00001000 40109394 00001000 6245af10  
,I/DEBUG   (  271):     626bcfc0 62786a10 626bcfd8 626bd354 631bbab0  
I/DEBUG   (  271):     626bcfd0 00000002 00000000 62786a10 00000000  
I/DEBUG   (  271):     626bcfe0 635c1f28 00000001 63853b00 626bcfd8  
I/DEBUG   (  271):     626bcff0 00000000 00000000 00000000 00000000  
,I/DEBUG   (  271):     626bd000 00000000 00000000 00000002 626bc861  
I/DEBUG   (  271):     626bd010 63900100 ffffffff 00000040 626bd450  
I/DEBUG   (  271):     626bd020 40109200 626bd450 6369ebb8 400cc03b  
I/DEBUG   (  271):     626bd030 00000040 d0000220 400caf9d 00000001  
I/DEBUG   (  271):     626bd040 626bd450 00000040 62468fb8 6382b940  
,I/DEBUG   (  271): 
I/DEBUG   (  271): memory near r9:
I/DEBUG   (  271):     626bcf8c 00000001 63851d80 63853b00 6245af10  
I/DEBUG   (  271):     626bcf9c 00000000 62786968 62786978 00000001  
I/DEBUG   (  271):     626bcfac 4010002f 00001000 40109394 00001000  
,I/DEBUG   (  271):     626bcfbc 6245af10 62786a10 626bcfd8 626bd354  
I/DEBUG   (  271):     626bcfcc 631bbab0 00000002 00000000 62786a10  
I/DEBUG   (  271):     626bcfdc 00000000 635c1f28 00000001 63853b00  
I/DEBUG   (  271):     626bcfec 626bcfd8 00000000 00000000 00000000  
,I/DEBUG   (  271):     626bcffc 00000000 00000000 00000000 00000002  
I/DEBUG   (  271):     626bd00c 626bc861 63900100 ffffffff 00000040  
I/DEBUG   (  271):     626bd01c 626bd450 40109200 626bd450 6369ebb8  
I/DEBUG   (  271):     626bd02c 400cc03b 00000040 d0000220 400caf9d  
I/DEBUG   (  271):     626bd03c 00000001 626bd450 00000040 62468fb8  
,I/DEBUG   (  271):     626bd04c 6382b940 0000000c 6369ebb8 626bd450  
I/DEBUG   (  271):     626bd05c 00000040 0000000c 63114a20 626bd548  
I/DEBUG   (  271):     626bd06c 00000001 639006d0 00000068 00000000  
I/DEBUG   (  271):     626bd07c 00000000 00000000 00000000 626bd098  
,I/DEBUG   (  271): 
I/DEBUG   (  271): memory near sl:
I/DEBUG   (  271):     626be4e8 626be8c8 626be500 626be87c 631bbab0  
I/DEBUG   (  271):     626be4f8 00000008 6383dd90 626be8c8 00000001  
I/DEBUG   (  271):     626be508 635c1f28 00000001 6382f680 626be500  
,I/DEBUG   (  271):     626be518 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be528 00000000 00000000 00000101 00000000  
I/DEBUG   (  271):     626be538 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be548 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be558 00000000 00000000 00000000 00000000  
,I/DEBUG   (  271):     626be568 00000000 00000000 00000000 00000000  
,I/DEBUG   (  271):     626be578 00000000 00000000 00000000 00000000  
,I/DEBUG   (  271):     626be588 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be598 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be5a8 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be5b8 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be5c8 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626be5d8 00000000 00000000 00000000 00000000  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near fp:
I/DEBUG   (  271):     626bcf34 ef9000ad 00000000 626bcf94 626bcfb0  
I/DEBUG   (  271):     626bcf44 626bcf94 626bcf80 00000000 626bdfcc  
I/DEBUG   (  271):     626bcf54 632ad3f0 626bcf88 00000000 626bcf7c  
,I/DEBUG   (  271):     626bcf64 630df184 00000000 00000000 40109394  
I/DEBUG   (  271):     626bcf74 00000000 626bd304 631bbb34 6245af10  
I/DEBUG   (  271):     626bcf84 6245af10 62786a78 00000001 63851d80  
I/DEBUG   (  271):     626bcf94 63853b00 6245af10 00000000 62786968  
I/DEBUG   (  271):     626bcfa4 62786978 00000001 4010002f 00001000  
I/DEBUG   (  271):     626bcfb4 40109394 00001000 6245af10 62786a10  
I/DEBUG   (  271):     626bcfc4 626bcfd8 626bd354 631bbab0 00000002  
I/DEBUG   (  271):     626bcfd4 00000000 62786a10 00000000 635c1f28  
I/DEBUG   (  271):     626bcfe4 00000001 63853b00 626bcfd8 00000000  
I/DEBUG   (  271):     626bcff4 00000000 00000000 00000000 00000000  
,I/DEBUG   (  271):     626bd004 00000000 00000002 626bc861 63900100  
I/DEBUG   (  271):     626bd014 ffffffff 00000040 626bd450 40109200  
I/DEBUG   (  271):     626bd024 626bd450 6369ebb8 400cc03b 00000040  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near ip:
I/DEBUG   (  271):     635cfb80 400c8a48 400c8a28 5d44dab5 5d44dbb9  
I/DEBUG   (  271):     635cfb90 400c8d29 5d44dbe7 400c8d15 5d44db8b  
I/DEBUG   (  271):     635cfba0 400de459 5d44da39 400cfaf9 400e0a31  
I/DEBUG   (  271):     635cfbb0 400cfcdd 400e110d 400e107d 400cf665  
I/DEBUG   (  271):     635cfbc0 400dd3a8 400dd19d 400d7a15 400e0679  
,I/DEBUG   (  271):     635cfbd0 400d7b89 400dd34c 400cf619 400cf70d  
I/DEBUG   (  271):     635cfbe0 400e09b5 400e15ef 400e39bd 400e07b9  
I/DEBUG   (  271):     635cfbf0 400e09cd 400de111 400ddcb9 400ce5e5  
I/DEBUG   (  271):     635cfc00 400e6315 400c9aa8 400c9b94 400c99a4  
I/DEBUG   (  271):     635cfc10 400ceebd 400db07c 400db95c 400e8bcd  
I/DEBUG   (  271):     635cfc20 400e8119 400dbfe8 400eaa31 40093dfd  
I/DEBUG   (  271):     635cfc30 40093e81 40093f31 400dcd40 400f52d1  
I/DEBUG   (  271):     635cfc40 400c9e30 400dc1e4 400c9674 400c96cc  
,I/DEBUG   (  271):     635cfc50 400c9780 400c9688 400dd6c5 400d1091  
I/DEBUG   (  271):     635cfc60 40093dad 400c8d51 400db91c 400db5c8  
I/DEBUG   (  271):     635cfc70 400d9d65 400e3f39 400db560 400dbd8c  
I/DEBUG   (  271): 
I/DEBUG   (  271): memory near sp:
I/DEBUG   (  271):     626bcf18 00000000 00000000 00000003 000000aa  
I/DEBUG   (  271):     626bcf28 0000006b 0001416e e3a070ad ef9000ad  
I/DEBUG   (  271):     626bcf38 00000000 626bcf94 626bcfb0 626bcf94  
,I/DEBUG   (  271):     626bcf48 626bcf80 00000000 626bdfcc 632ad3f0  
I/DEBUG   (  271):     626bcf58 626bcf88 00000000 626bcf7c 630df184  
I/DEBUG   (  271):     626bcf68 00000000 00000000 40109394 00000000  
I/DEBUG   (  271):     626bcf78 626bd304 631bbb34 6245af10 6245af10  
I/DEBUG   (  271):     626bcf88 62786a78 00000001 63851d80 63853b00  
I/DEBUG   (  271):     626bcf98 6245af10 00000000 62786968 62786978  
I/DEBUG   (  271):     626bcfa8 00000001 4010002f 00001000 40109394  
I/DEBUG   (  271):     626bcfb8 00001000 6245af10 62786a10 626bcfd8  
I/DEBUG   (  271):     626bcfc8 626bd354 631bbab0 00000002 00000000  
,I/DEBUG   (  271):     626bcfd8 62786a10 00000000 635c1f28 00000001  
I/DEBUG   (  271):     626bcfe8 63853b00 626bcfd8 00000000 00000000  
I/DEBUG   (  271):     626bcff8 00000000 00000000 00000000 00000000  
I/DEBUG   (  271):     626bd008 00000002 626bc861 63900100 ffffffff  
I/DEBUG   (  271): 
I/DEBUG   (  271): code around pc:
I/DEBUG   (  271):     400de48c b31a2b01 0f04f013 800af000 3b04f851  
I/DEBUG   (  271):     400de49c 3c01f1a3 0c03ea2c 3c80f01c 8033f040  
I/DEBUG   (  271):     400de4ac 2302e8f1 f040f891 3c01f1a2 0c02ea2c  
,I/DEBUG   (  271):     400de4bc 3c80f01c 800ff040 3c01f1a3 0c03ea2c  
I/DEBUG   (  271):     400de4cc 3c80f01c 801ff040 bfeaf7ff 0000eba1  
I/DEBUG   (  271):     400de4dc 0001f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  271):     400de4ec f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  271):     400de4fc 47700005 0008f1a0 f1a04770 47700007  
I/DEBUG   (  271):     400de50c 0006f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  271):     400de51c f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  271):     400de52c 47700001 0004f1a0 f1a04770 47700003  
,I/DEBUG   (  271):     400de53c 0002f1a0 bf004770 1e0cb510 4807da02  
I/DEBUG   (  271):     400de54c e0034478 d904429c 44784805 f7ef2100  
I/DEBUG   (  271):     400de55c e8bdfb43 f7f14010 bf00ba0f 0001f06d  
I/DEBUG   (  271):     400de56c 0001f081 b508429a 4805d904 44784903  
I/DEBUG   (  271):     400de57c fb32f7ef 4008e8bd b89ef7ff 000138ee  
I/DEBUG   (  271): 
I/DEBUG   (  271): code around lr:
,I/DEBUG   (  271):     632d62e8 e24dd008 e1a08002 e1a07000 e1a06001  
I/DEBUG   (  271):     632d62f8 11a02003 1a000002 e1a00008 ebe8a1f5  
I/DEBUG   (  271):     632d6308 e1a02000 e3520000 da00000a e1d830d0  
,I/DEBUG   (  271):     632d6318 e3530000 ba000012 e288c001 e0884002  
I/DEBUG   (  271):     632d6328 ea000002 e0dce0d1 e35e0000 ba00000c  
I/DEBUG   (  271):     632d6338 e15c0004 1afffffa e1a01008 e1a00006  
I/DEBUG   (  271):     632d6348 ebf76630 e1a02006 e3a03000 e1a01000  
,I/DEBUG   (  271):     632d6358 e1a00007 ebffff2b e1a00007 e24bd014  
I/DEBUG   (  271):     632d6368 e8bd89d0 e3a00000 e24b3014 e1a01008  
I/DEBUG   (  271):     632d6378 e5230004 e1a00006 ebfff958 e51b1018  
,I/DEBUG   (  271):     632d6388 e3510000 0a000006 e1a02006 e1a00007  
I/DEBUG   (  271):     632d6398 e3a03000 ebffff1b e1a00007 e24bd014  
I/DEBUG   (  271):     632d63a8 e8bd89d0 e59f0020 e59f2020 e59f3020  
I/DEBUG   (  271):     632d63b8 e3a01e3f e08f0000 e08f2002 e08f3003  
,I/DEBUG   (  271):     632d63c8 ebe8a299 e51b1018 eaffffee 001f6ed0  
,I/DEBUG   (  271):     632d63d8 002a3448 001f6ef8 e92d4878 e1a05001  
,W/ActivityManager( 1017):   Force finishing activity com.example.hello/.MainActivity
,I/ActivityManager( 1017): Killing 3902:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Process com.example.hello (pid 4136) has died.
,I/WindowState( 1017): WIN DEATH: Window{42ace380 u0 com.example.hello/com.example.hello.MainActivity}
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/SFPerfTracer(  273):      triggers: (rate: 3:34) (compose: 0:5) (post: 0:1) (render: 0:5) (0:106 frames) (1:546)
,D/SFPerfTracer(  273):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:209)* (NavigationBar: 0:39)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:19)* (ElectronBeam: 0:27)* (com.example.hello/com.example.hello.MainActivity: 1:4)* 
,W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/Zygote  (  275): Process 4136 terminated by signal (11)
,I/OtaApp  ( 1585): [info] > Updatetime from metadata: 10
,D/Checkin ( 1585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1585): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1585): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1585): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1585): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1585): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 4136 uid 10523
W/Binder  ( 1235): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1235): java.lang.NullPointerException
W/Binder  ( 1235): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1235): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1235): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1235): 	at dalvik.system.NativeStart.run(Native Method)
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42abf0d0 type 3 android}
,E/global frequency( 1585): no tags to log
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1585): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1585): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 1585): BcsDSCheckin.events found events 121
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1585): BcsDSDropBox.events found events 16
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 1585): doRequest(): url: https://api.svcmot.com:443/v1/cs/checkin.pb/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1585): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 1585): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1585): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 1585): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider( 1017): 121 events delete 0 left
,I/global frequency( 1585): BcsDSCheckin.events found events 0
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1585): BcsDSDropBox.events found events 0
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/dalvikvm( 1585): GC_CONCURRENT freed 1935K, 38% free 10688K/17224K, paused 4ms+3ms, total 29ms
,I/global frequency( 1585): BcsTimer.onReceive checkin completed (0:ERROR_OK)
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{42aed700 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2 9e:93:4e
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 2 9e:93:4e
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3 0c:bd:51
D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 3 0c:bd:51
D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4 fe:94:e3
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 4 fe:94:e3
,D/MDMCTBK (  272): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5 fc:94:e3
,D/MDMCTBK (  272): Event received = CTRL-EVENT-BSS-REMOVED 5 fc:94:e3
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{428a65f8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 4220): 
D/AndroidRuntime( 4220): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4220): CheckJNI is OFF
D/dalvikvm( 4220): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4220): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4220): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4220): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4220): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4220): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4220): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4220): failed to load memtrack module: -2
D/AndroidRuntime( 4220): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.example.hello appid=10523 user=-1: uninstall pkg
W/PackageSettings( 1017): Skipping PackageSetting{42253bf0 com.test.thalitest/10522} due to missing metadata
I/ActivityManager( 1017): Force stopping com.example.hello appid=10523 user=0: pkg removed
D/dalvikvm( 2250): GC_EXPLICIT freed 5088K, 44% free 9668K/17224K, paused 4ms+15ms, total 49ms
D/dalvikvm( 1017): GC_EXPLICIT freed 2585K, 13% free 18102K/20744K, paused 4ms+9ms, total 114ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
W/GeofencerStateMachine( 1250): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/LatinIME:LogUtils( 1235): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1326): GC_EXPLICIT freed 3241K, 33% free 11594K/17224K, paused 1ms+16ms, total 144ms
I/LatinIME:LogUtils( 1235): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1417): GC_EXPLICIT freed 1291K, 31% free 11959K/17224K, paused 52ms+51ms, total 153ms
W/SQLiteConnectionPool( 1417): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 3566): Cleaning up data for package: com.example.hello
I/Launcher( 1326): Deferring update until onResume
D/dalvikvm( 2296): GC_EXPLICIT freed 4070K, 42% free 10093K/17224K, paused 2ms+17ms, total 147ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1235): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452261267
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/Launcher( 1326): Deferring update until onResume
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10523 #1
I/InternalIcingCorporaPro( 2296): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4248 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/LatinIME:LogUtils( 1235): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452261267
D/dalvikvm( 1017): GC_EXPLICIT freed 746K, 14% free 18043K/20744K, paused 9ms+18ms, total 161ms
W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3626): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3626): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3626): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1417): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1417): Clearing selected account for com.example.hello
I/LocationSettingsChecker( 1417): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1417): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1417): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1417): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1417): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1417): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1417): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ChimeraCfgMgr( 1417): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1417): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1417): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1417): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1417): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
E/NetworkScheduler.SchedulerReceiver( 1384): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1384): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1417): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1417): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/Icing   ( 1417): doRemovePackageData com.example.hello
D/gH_CompatibleDatabase( 1417): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1417): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1417): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1417): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4274 uid=10058 gids={50058}
D/AndroidRuntime( 4220): Shutting down VM
D/dalvikvm( 4220): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
I/InternalIcingCorporaPro( 2296): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
D/Documents( 4274): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4289 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1017): Killing 3994:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017): Killing 3971:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 4274): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 4289): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f95360, skipping init
I/openssl ( 4289): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4289): Crypto mode 0 already enabled
I/ActivityManager( 1017): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4306 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1017): Killing 3566:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1301): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4306): After updating volumes, found 1 active roots
D/Documents( 4274): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4274): Loading roots for com.android.providers.media.documents
D/Documents( 4274): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4274): Update found 7 roots in 186ms
D/Documents( 4274): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4274): Loading roots for com.android.externalstorage.documents
D/Documents( 4274): Used cached roots for com.android.providers.media.documents
D/Documents( 4274): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4274): Update found 7 roots in 6ms

```
