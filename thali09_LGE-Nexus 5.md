#### Test 575312430087a60_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 2676): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2676): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 2676): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2676): GC_CONCURRENT freed 471K, 3% free 17586K/18088K, paused 2ms+1ms, total 14ms
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 5ms
I/dalvikvm-heap( 2676): Grow heap (frag case) to 17.277MB for 79892-byte allocation
D/dalvikvm( 2676): GC_FOR_ALLOC freed 5K, 3% free 17659K/18168K, paused 12ms, total 12ms
,--------- beginning of /dev/log/system
I/ActivityManager(  772): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2713 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  772): Killing 1961:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2676): GC_CONCURRENT freed 291K, 2% free 17879K/18200K, paused 2ms+1ms, total 26ms
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 14ms
D/dalvikvm( 2676): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2676): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2676): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2676): GC_CONCURRENT freed 414K, 3% free 17865K/18312K, paused 2ms+2ms, total 16ms
D/dalvikvm( 2676): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2676): VFY: unable to resolve instance field 36
D/dalvikvm( 2676): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2676): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2676): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2676): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2676): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2676): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4279b938
D/dalvikvm( 2676): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4279b938
D/dalvikvm( 2676): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4279b938, skipping init
D/dalvikvm( 2676): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4279b938
D/dalvikvm( 2676): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4279b938
V/JNIHelp ( 2676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2676): GC_CONCURRENT freed 303K, 2% free 17948K/18312K, paused 2ms+1ms, total 14ms
D/dalvikvm( 2676): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4279b938
D/dalvikvm( 2676): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4279b938
D/dalvikvm( 2676): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4279b938
D/dalvikvm( 2676): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4279b938
W/Quickoffice( 2713): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2713): Loading recent documents list
D/Quickoffice( 2713): The number of lines present in  /proc/mount 21
D/Quickoffice( 2713): Parsing the storagedefinition.xml.
D/Quickoffice( 2713): # of Storagedefinitions - 35
D/Quickoffice( 2713): The # of storage definitions available - 35
D/Quickoffice( 2713): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2713): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2713): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2713): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2713): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2713): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2713): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2713): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2713): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2713): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2713): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2713): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2713): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2713): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2713): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2713): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2713): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2713): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2713): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2713): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2713): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2713): Build properties are not configured for this storage definition.
D/Quickoffice( 2713): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2713): The # of mounts identified -  1
I/ProviderInstaller( 2676): Installed default security provider GmsCore_OpenSSL
D/com.google.android.apps.docs.quickoffice.X( 2713): Checking validity of 0 items
I/ActivityManager(  772): Killing 2382:com.android.chrome/u0a31 (adj 15): empty #17
D/dalvikvm( 2713): GC_CONCURRENT freed 204K, 2% free 16951K/17156K, paused 3ms+4ms, total 25ms
W/ActivityManager(  772): No permission grants found for com.quickoffice.android
D/ContentResolverUtil( 2713): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2713): 0 items were valid
W/Quickoffice( 2713): Could not load clipboard.
W/Quickoffice( 2713): Could not store clipboard.
D/AndroidRuntime( 2727): 
D/AndroidRuntime( 2727): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2727): CheckJNI is OFF
D/dalvikvm( 2727): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2727): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2727): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2727): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2727): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2727): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2727): Calling main entry com.android.commands.am.Am
I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2727
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (137 us)
D/AndroidRuntime( 2727): Shutting down VM
D/dalvikvm( 2727): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  772): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2758 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1170): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1170): mic_close
I/Icing   ( 1313): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/MicroHotwordRecognitionRunner( 1170): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1170): Stopping hotword detection.
I/ActivityManager(  772): Killing 966:com.google.android.keep/u0a52 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 2758): Binding Chromium to main looper Looper (main, tid 1) {4261d568}
I/LibraryLoader( 2758): Expected native library version number "",actual native library version number ""
I/chromium( 2758): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2758): Initializing chromium process, renderers=0
D/BluetoothManagerService(  772): Message: 20
D/BluetoothManagerService(  772): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43f84ff0:true
I/Adreno-EGL( 2758): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
D/dalvikvm( 1170): GC_CONCURRENT freed 396K, 3% free 18241K/18660K, paused 3ms+1ms, total 21ms
W/chromium( 2758): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2758): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2758): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2758): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2758): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2758): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2758): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2758): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2758): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2758): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2758): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2758): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2758): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2758): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2758): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2758): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2758): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2758): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2758): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2758): CordovaWebView is running on device made by: LGE
,I/Icing   ( 1313): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1313): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/OpenGLRenderer( 2758): Enabling debug mode 0
,W/AwContents( 2758): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  772): Displayed com.test.thalitest/.MainActivity: +280ms
,D/dalvikvm( 1313): GC_CONCURRENT freed 514K, 3% free 19238K/19784K, paused 3ms+4ms, total 42ms
,I/Icing   ( 1313): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/ActivityManager(  772): Killing 2410:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,D/JsMessageQueue( 2758): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2758): GC_CONCURRENT freed 268K, 2% free 16900K/17200K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2758): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42623cd0
D/dalvikvm( 2758): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42623cd0
D/jxcore_app_log( 2758): JniHelper::setJavaVM(0x41506f00), pthread_self() = 1982142696
I/chromium( 2758): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 2758): GC_CONCURRENT freed 185K, 2% free 17146K/17364K, paused 3ms+3ms, total 17ms
D/dalvikvm( 2758): GC_CONCURRENT freed 159K, 2% free 17489K/17688K, paused 2ms+1ms, total 12ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 2758): GC_CONCURRENT freed 156K, 2% free 17831K/18032K, paused 1ms+1ms, total 10ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2758): GC_CONCURRENT freed 154K, 2% free 18171K/18372K, paused 1ms+1ms, total 12ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2758): GC_CONCURRENT freed 157K, 2% free 18503K/18712K, paused 1ms+1ms, total 11ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 2758): GC_CONCURRENT freed 175K, 2% free 18907K/19136K, paused 2ms+1ms, total 14ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2758): GC_CONCURRENT freed 213K, 2% free 19403K/19676K, paused 2ms+1ms, total 15ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2758): GC_CONCURRENT freed 276K, 2% free 19994K/20336K, paused 1ms+1ms, total 16ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2758): GC_CONCURRENT freed 318K, 2% free 20734K/21124K, paused 2ms+2ms, total 20ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2758): GC_CONCURRENT freed 631K, 4% free 21415K/22112K, paused 2ms+1ms, total 23ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2758): GC_CONCURRENT freed 1278K, 6% free 21643K/23016K, paused 1ms+2ms, total 24ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 16ms
I/dalvikvm-heap( 2758): Grow heap (frag case) to 21.625MB for 485740-byte allocation
D/dalvikvm( 2758): GC_FOR_ALLOC freed 317K, 8% free 21799K/23492K, paused 18ms, total 18ms
D/dalvikvm( 2758): GC_CONCURRENT freed 1285K, 7% free 22112K/23532K, paused 2ms+2ms, total 29ms
D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 2758): GC_FOR_ALLOC freed 465K, 6% free 22153K/23532K, paused 24ms, total 24ms
I/dalvikvm-heap( 2758): Grow heap (frag case) to 22.703MB for 1092904-byte allocation
D/dalvikvm( 2758): GC_FOR_ALLOC freed 723K, 9% free 22497K/24600K, paused 19ms, total 19ms
,D/dalvikvm( 2758): GC_FOR_ALLOC freed 1392K, 9% free 22404K/24600K, paused 20ms, total 22ms
,I/dalvikvm-heap( 2758): Grow heap (frag case) to 23.468MB for 1639352-byte allocation
,D/dalvikvm( 2758): GC_FOR_ALLOC freed 5K, 9% free 23999K/26204K, paused 21ms, total 21ms
,D/dalvikvm( 2758): GC_FOR_ALLOC freed 3091K, 13% free 23053K/26204K, paused 22ms, total 25ms
,I/dalvikvm-heap( 2758): Grow heap (frag case) to 24.884MB for 2459024-byte allocation
,D/dalvikvm( 2758): GC_FOR_ALLOC freed 3K, 12% free 25451K/28608K, paused 19ms, total 19ms
,D/dalvikvm( 2758): GC_CONCURRENT freed 1740K, 17% free 23818K/28608K, paused 2ms+4ms, total 28ms
,D/dalvikvm( 2758): GC_CONCURRENT freed 2321K, 17% free 23873K/28608K, paused 1ms+3ms, total 34ms
,D/dalvikvm( 2758): WAIT_FOR_CONCURRENT_GC blocked 10ms
,W/jxcore-log( 2758): Initializing JXcore engine
,W/jxcore-log( 2758): JXcore engine is ready
,D/dalvikvm( 2758): GC_CONCURRENT freed 300K, 10% free 25864K/28608K, paused 5ms+11ms, total 36ms
,W/jxcore-log( 2758): Starting JXcore engine
,W/jxcore-log( 2758): Platform android
W/jxcore-log( 2758): 
,W/jxcore-log( 2758): Process ARCH arm
W/jxcore-log( 2758): 
,I/jxcore-log( 2758): JXcore Cordova bridge is ready!
I/jxcore-log( 2758): 
,W/jxcore-log( 2758): JXcore engine is started
,E/jxcore  ( 2758): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2758): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2758): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 2758): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 27ms. Plugin should use CordovaInterface.getThreadPool().
,W/Sidekick_LocationOracleImpl( 1170): Best location was null
,W/IInputConnectionWrapper( 2758): showStatusIcon on inactive InputConnection
,W/GCoreFlp(  996): No location to return for getLastLocation()
,D/dalvikvm(  996): GC_CONCURRENT freed 456K, 3% free 18651K/19204K, paused 3ms+16ms, total 45ms
,W/GCoreFlp(  996): No location to return for getLastLocation()
,W/GCoreFlp(  996): No location to return for getLastLocation()
,W/GCoreFlp(  996): No location to return for getLastLocation()
,W/GCoreFlp(  996): No location to return for getLastLocation()
,W/GCoreFlp(  996): No location to return for getLastLocation()
,D/dalvikvm( 1170): GC_FOR_ALLOC freed 788K, 6% free 17610K/18660K, paused 15ms, total 16ms
,I/dalvikvm-heap( 1170): Grow heap (frag case) to 17.834MB for 640016-byte allocation
,D/dalvikvm( 1170): GC_FOR_ALLOC freed 3K, 3% free 18232K/18660K, paused 14ms, total 14ms
,I/MicroHotwordRecognitionRunner( 1170): Starting hotword detection.
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
,D/dalvikvm( 1170): GC_CONCURRENT freed 7K, 3% free 18231K/18660K, paused 2ms+1ms, total 17ms
,I/SearchController( 1170): #onHotwordDetectorStarted
,E/libEGL  ( 2758): call to OpenGL ES API with no current context (logged once per thread)
,D/Finsky  ( 2472): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,D/dalvikvm( 1080): GC_CONCURRENT freed 336K, 3% free 18057K/18612K, paused 7ms+2ms, total 48ms
,D/dalvikvm( 1080): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/VacuumService(  996): Vacuum at: now=1454091977886 tag=VacuumService
,D/dalvikvm( 1080): GC_CONCURRENT freed 596K, 4% free 17883K/18612K, paused 1ms+2ms, total 22ms
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7065160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1224323376)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1224323376) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7065160
,I/PowerManagerService(  772): Going to sleep due to screen timeout...
,I/Adreno-EGL(  772): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb8176450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  772): Excessive delay in blankDisplay() while turning screen off: 284ms
,V/KeyguardServiceDelegate(  772): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@43d1a460)
,V/KeyguardServiceDelegate(  772): **** SHOWN CALLED ****
I/WindowManager(  772): No lock screen! windowToken=null
,I/SearchController( 1170): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1170): mic_close
,D/NfcService( 1039): NFC-C OFF
,I/ActivityManager(  772): Killing 2216:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  772): Service ServiceRecord{42e3b038 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42b3fe60 2216:com.google.android.music:main/u0a58} not same as in map: null
,I/MicroHotwordRecognitionRunner( 1170): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1170): Stopping hotword detection.
,F/ActivityManager(  772): Service ServiceRecord{42e3a8b8 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42b3fe60 2216:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  772): Service ServiceRecord{42c24f00 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42b3fe60 2216:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  772): Service ServiceRecord{42c0eaa8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42b3fe60 2216:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  772): Service ServiceRecord{42b39360 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42b3fe60 2216:com.google.android.music:main/u0a58} not same as in map: null
,D/dalvikvm(  772): GC_EXPLICIT freed 20628K, 48% free 26785K/51404K, paused 2ms+5ms, total 89ms
,D/dalvikvm( 1170): GC_CONCURRENT freed 829K, 6% free 17796K/18768K, paused 1ms+2ms, total 12ms
,D/dalvikvm( 1080): GC_CONCURRENT freed 314K, 4% free 17952K/18612K, paused 2ms+1ms, total 13ms
,I/PhenotypeConfigurator(  996): Scheduling Phenotype for one-off execution 3291 seconds from now (1454092057712)
,D/GetConfigurationSnapshotOperation(  996): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  996): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  996): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  996): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  996): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  996): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  996): GC_CONCURRENT freed 601K, 4% free 18704K/19400K, paused 2ms+3ms, total 28ms
,I/dalvikvm(  996): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  996): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  996): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  996): GC_CONCURRENT freed 427K, 4% free 18893K/19480K, paused 3ms+4ms, total 32ms
,D/dalvikvm(  996): GC_CONCURRENT freed 555K, 4% free 18996K/19644K, paused 3ms+2ms, total 19ms
,D/dalvikvm(  996): GC_CONCURRENT freed 583K, 4% free 19105K/19784K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  996): GC_CONCURRENT freed 740K, 5% free 19131K/19964K, paused 1ms+3ms, total 19ms
,D/dalvikvm(  996): GC_CONCURRENT freed 777K, 5% free 19088K/19992K, paused 3ms+3ms, total 20ms
,D/dalvikvm(  996): GC_CONCURRENT freed 705K, 5% free 19110K/19992K, paused 3ms+3ms, total 20ms
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0x5ee00001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1080): Read error: ssl=0x79274ee0: I/O error during system call, Connection timed out
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79274ee0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1213): GC_CONCURRENT freed 350K, 3% free 16740K/17128K, paused 1ms+0ms, total 11ms
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/dalvikvm( 1015): GC_CONCURRENT freed 338K, 3% free 17063K/17428K, paused 8ms+1ms, total 18ms
I/SystemUpdateService( 1313): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/iu.SyncManager( 1313): NEXT; no task
,I/Babel   ( 2012): connection state changed from CONNECTED to DISCONNECTED
I/ActivityManager(  772): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3026 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1313): onDestroy
,D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3026): VFY: unable to resolve instance field 68
D/dalvikvm( 3026): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3026): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3026): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 3026): VFY: unable to resolve instance field 68
,D/dalvikvm( 3026): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3026): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  772): Killing 1827:com.google.android.gm/u0a41 (adj 15): empty #17
D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3026): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3026): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3026): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/WifiStateMachine(  772): VerifyingLinkState enter
D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-3ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm(  978): GC_CONCURRENT freed 268K, 2% free 16995K/17292K, paused 6ms+0ms, total 38ms
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1313): NEXT; no task
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,I/Babel   ( 2012): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0x7c500001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1080): Read error: ssl=0x79294f90: I/O error during system call, Connection timed out
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79294f90: I/O error during system call, Broken pipe
D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 2012): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
I/SystemUpdateService( 1313): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/iu.SyncManager( 1313): NEXT; no task
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1080): GC_CONCURRENT freed 407K, 4% free 17930K/18612K, paused 2ms+1ms, total 14ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/SystemUpdateService( 1313): showing system update notification
,I/iu.SyncManager( 1313): NEXT; no task
,D/SystemUpdateService( 1313): onDestroy
,I/Babel   ( 2012): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0x9e900001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1080): Read error: ssl=0x79036b78: I/O error during system call, Connection timed out
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79036b78: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  178): write error (Broken pipe)
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,I/dalvikvm(  772): Jit: resizing JitTable from 8192 to 16384
,D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,D/dalvikvm(  772): GC_CONCURRENT freed 2434K, 48% free 26813K/51404K, paused 3ms+3ms, total 72ms
,D/dalvikvm( 2012): GC_CONCURRENT freed 1397K, 6% free 22825K/24264K, paused 2ms+2ms, total 31ms
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
,I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified,
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,D/dalvikvm( 1080): GC_CONCURRENT freed 409K, 4% free 17905K/18612K, paused 8ms+1ms, total 44ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=0 what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  772): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  772): Done.
,D/ConnectivityService(  772): Setting timer for 720seconds
,D/dalvikvm( 1313): GC_CONCURRENT freed 819K, 5% free 19140K/19992K, paused 3ms+3ms, total 21ms
,I/EventLogService( 1313): Aggregate from 1454090937892 (log), 1454090937892 (data)
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0xdc400001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1080): Read error: ssl=0x79039360: I/O error during system call, Connection timed out
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79039360: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2012): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1313): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/SystemUpdateService( 1313): showing system update notification
,I/iu.SyncManager( 1313): NEXT; no task
,D/SystemUpdateService( 1313): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/iu.SyncManager( 1313): NEXT; no task
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,I/Babel   ( 2012): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0xf8e00001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1080): Read error: ssl=0x79036b78: I/O error during system call, Connection timed out
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79036b78: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/Babel   ( 2012): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/SystemUpdateService( 1313): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
,I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
I/SystemUpdateService( 1313): OTA package size = 2571501
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/SystemUpdateService( 1313): showing system update notification
,I/iu.SyncManager( 1313): NEXT; no task
,D/SystemUpdateService( 1313): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/iu.SyncManager( 1313): NEXT; no task
I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,I/Babel   ( 2012): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/dalvikvm( 1080): GC_CONCURRENT freed 426K, 4% free 17923K/18612K, paused 8ms+1ms, total 92ms
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  772): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  772): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  772): Attempting to switch to mobile
,D/ConnectivityService(  772): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  772): android_net_utils_resetConnections in env=0x75419080 clazz=0x19d00001 iface=wlan0 mask=0x3
D/ConnectivityService(  772): resetConnections(wlan0, 3)
,V/NativeCrypto( 1080): Read error: ssl=0x79036b78: I/O error during system call, Connection timed out
,V/NativeCrypto( 1080): SSL shutdown failed: ssl=0x79036b78: I/O error during system call, Broken pipe
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  772): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  772): GC_CONCURRENT freed 2386K, 48% free 26835K/51404K, paused 2ms+3ms, total 46ms
,I/wpa_supplicant(  923): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  923): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  923): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  923): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  772): scanCount==0 - aborting
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/Babel   ( 2012): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1313): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,I/iu.SyncManager( 1313): NEXT; no task
,D/SystemUpdateService( 1313): onDestroy
,D/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  772): CaptivePortalCheckState enter
,D/WifiStateMachine(  772): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  772): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  772): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  772): Unexpected mtu value: android.net.wifi.WifiStateTracker@42aa6a78
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  772): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  772): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  772):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  772): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  772): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  772): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1313): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1313): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1313): num queued entries: 0
,I/iu.UploadsManager( 1313): num updated entries: 0
,I/SystemUpdateService( 1313): active receiver: enabled
I/iu.SyncManager( 1313): NEXT; no task
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,D/dalvikvm( 1313): GC_CONCURRENT freed 581K, 4% free 19283K/19992K, paused 2ms+2ms, total 37ms
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,D/SystemUpdateService( 1313): onDestroy
,I/Babel   ( 2012): connection state changed from DISCONNECTED to CONNECTED
,I/CheckinService( 1313): Checkin interval check for package: unspecified last checkin: 1454050333546 min interval config: 0 actual interval: 42746187
I/CheckinService( 1313): Checking schedule, now: 1454093079736 next: 1454092822495
,I/CheckinService( 1313): active receiver: enabled
,I/CheckinService( 1313): Preparing to send checkin request
,I/EventLogService( 1313): Accumulating logs since 1454092794213
,I/CheckinRequestBuilder( 1313): Checkin reason type: 1 attempt count: 1
,E/ActivityThread( 1313): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1080): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1080): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1080): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1080): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1080): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1080): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1080): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1080): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1080): VFY: replacing opcode 0x6e at 0x003d
,D/ConnectivityService(  772): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 1080): GC_CONCURRENT freed 384K, 4% free 17957K/18612K, paused 8ms+1ms, total 56ms
,D/dalvikvm( 1080): GC_CONCURRENT freed 393K, 4% free 17950K/18612K, paused 2ms+1ms, total 13ms
,I/ActivityManager(  772): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3735 uid=10007 gids={50007, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 3735): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3735): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3735): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3735): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 3735): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3735): install
,I/MultiDex( 3735): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3735): loading existing secondary dex files
,I/MultiDex( 3735): load found 3 secondary dex files
,I/MultiDex( 3735): install done
,D/dalvikvm( 3735): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3735): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3735): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3735): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3735): VFY: unable to resolve instance field 36
,D/dalvikvm( 3735): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3735): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3735): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3735): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3735): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3735): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3735): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42626890
D/dalvikvm( 3735): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42626890
,D/dalvikvm( 3735): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42626890, skipping init
,D/dalvikvm( 3735): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42626890
D/dalvikvm( 3735): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42626890
,V/JNIHelp ( 3735): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 3735): GC_CONCURRENT freed 344K, 3% free 16817K/17192K, paused 3ms+2ms, total 14ms
,D/dalvikvm( 3735): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42626890
,D/dalvikvm( 3735): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42626890
D/dalvikvm( 3735): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42626890
,D/dalvikvm( 3735): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42626890
,D/dalvikvm( 3735): GC_CONCURRENT freed 197K, 2% free 17044K/17312K, paused 1ms+1ms, total 10ms
,I/ProviderInstaller( 3735): Installed default security provider GmsCore_OpenSSL
,D/WearableService(  996): callingUid 10007, callindPid: 996
,D/LocationInitializer( 1313): Restart initialization of location
,D/AuthorizationBluetoothService( 1080): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1080): Proximity feature is not enabled.
,E/MDM     (  996): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1080): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp(  996): No location to return for getLastLocation()
,W/FusedLocationProvider(  996): location=null
,I/dalvikvm( 3735): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 3735): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 3735): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 3735): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 3735): GC_CONCURRENT freed 181K, 2% free 17306K/17520K, paused 3ms+1ms, total 21ms
,I/dalvikvm( 3735): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3735): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3735): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3735): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 3735): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3735): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 3735): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3735): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3735): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 3735): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/dalvikvm( 3735): GC_CONCURRENT freed 292K, 2% free 17522K/17848K, paused 1ms+1ms, total 17ms
D/dalvikvm( 3735): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 3735): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/WVCdm   (  184): Instantiating CDM.
,I/WVCdm   (  184): Level3 Library Nov 20 2013 18:09:31
,D/dalvikvm( 3735): GC_CONCURRENT freed 173K, 2% free 17795K/17996K, paused 1ms+2ms, total 20ms
,D/DrmWidevineDash(  184): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/QSEECOMAPI: (  184): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  184): App is not loaded in QSEE
,D/QSEECOMAPI: (  184): Loaded image: APP id = 3
,D/DrmWidevineDash(  184): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5443000
,E/DrmWidevineDash(  184): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5443000
,I/dalvikvm( 3735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 3735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  184): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_APIVersion...
,W/dalvikvm( 3735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 3735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 3735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 3735): VFY: replacing opcode 0x6e at 0x00bb
,D/DrmWidevineDash(  184): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  184): calling OEMCrypto_IsKeyboxValid...
,I/GoogleURLConnFactory( 3735): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  184): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  184): CdmEngine::OpenSession
,D/DrmWidevineDash(  184): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  184): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  184): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=2639347565
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 3735): GC_CONCURRENT freed 292K, 2% free 17912K/18244K, paused 2ms+2ms, total 17ms
,D/NativeLibraryUtils( 3735): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  184): CdmEngine::CloseSession
,D/DrmWidevineDash(  184): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 3735): GC_CONCURRENT freed 304K, 2% free 18063K/18400K, paused 1ms+3ms, total 12ms
,D/dalvikvm( 3735): GC_CONCURRENT freed 991K, 6% free 17493K/18528K, paused 1ms+0ms, total 12ms
,D/dalvikvm( 3735): GC_FOR_ALLOC freed 10K, 6% free 17493K/18528K, paused 9ms, total 9ms
,I/dalvikvm-heap( 3735): Grow heap (frag case) to 17.271MB for 168754-byte allocation
,D/dalvikvm( 3735): GC_FOR_ALLOC freed 81K, 6% free 17576K/18696K, paused 9ms, total 9ms
,D/dalvikvm( 3735): GC_FOR_ALLOC freed 189K, 7% free 17505K/18696K, paused 21ms, total 21ms
,D/dalvikvm( 3735): GC_FOR_ALLOC freed 109K, 6% free 17604K/18696K, paused 24ms, total 24ms
,D/dalvikvm( 3735): GC_FOR_ALLOC freed 196K, 7% free 17506K/18696K, paused 8ms, total 8ms
,D/dalvikvm( 3735): GC_CONCURRENT freed 320K, 6% free 17602K/18696K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 3735): DexOpt: --- BEGIN 'the.apk' (bootstrap=0) ---
,D/dalvikvm( 3777): DexOpt: load 2ms, verify+opt 1ms, 98164 bytes
,D/dalvikvm( 3735): DexOpt: --- END 'the.apk' (success) ---
,D/dalvikvm( 3735): DEX prep '/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/the.apk': unzip in 0ms, rewrite 35ms
,D/dalvikvm( 3735): GC_CONCURRENT freed 296K, 5% free 17817K/18696K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 3735): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 3735): GC_CONCURRENT freed 175K, 3% free 18154K/18696K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 3735): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3735): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x427812f8
D/dalvikvm( 3735): Added shared lib /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x427812f8
,D/dalvikvm( 3735): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/lib/libd317EF1D9D4A2.so 0x427812f8, skipping init
,I/WVCdm   (  184): CdmEngine::OpenSession
,D/DrmWidevineDash(  184): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  184): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  184): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=2223725035
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  184): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  184): CdmEngine::CloseSession
,D/DrmWidevineDash(  184): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 3735): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 3781): DexOpt: load 2ms, verify+opt 3ms, 123436 bytes
,D/dalvikvm( 3735): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3735): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 50ms
,D/dalvikvm( 3735): GC_CONCURRENT freed 488K, 3% free 18171K/18696K, paused 3ms+1ms, total 15ms
,D/dalvikvm( 3735): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/Adreno-EGL( 3735): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,I/Adreno-EGL( 3735): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,I/Adreno-EGL( 3735): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,W/Settings( 3735): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 3735): GC_CONCURRENT freed 278K, 3% free 18288K/18696K, paused 2ms+1ms, total 15ms
,I/CheckinRequestBuilder( 1313): Classify the device as Phone.
,D/dalvikvm( 1313): GC_CONCURRENT freed 853K, 5% free 19291K/20176K, paused 4ms+4ms, total 33ms
,D/dalvikvm( 1313): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/CheckinTask( 1313): Sending checkin request (11569 bytes)
,I/CheckinResponseProcessor( 1313): From server: 3 gservices updates and 0 deletes
,D/dalvikvm( 1080): GC_CONCURRENT freed 293K, 4% free 18041K/18612K, paused 2ms+1ms, total 13ms
,I/CertBlacklister(  772): Certificate blacklist changed, updating...
,I/GservicesProvider( 1080): main difference update completed
I/CertBlacklister(  772): Certificate blacklist updated
,I/ActivityManager(  772): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3797 uid=10002 gids={50002, 3003, 2001}
,D/dalvikvm(  182): GC_EXPLICIT freed 42K, 1% free 16698K/16772K, paused 1ms+2ms, total 15ms
,I/CheckinRequestBuilder( 1313): Checkin reason type: 1 attempt count: 1
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 0ms+2ms, total 11ms
,D/dalvikvm(  182): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+2ms, total 12ms
E/ActivityThread( 1313): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 2012): ApnsOta: OTA version -1
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 3797): Update started
,I/ActivityManager(  772): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,D/dalvikvm( 3797): GC_CONCURRENT freed 369K, 3% free 16753K/17160K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 1206): GC_CONCURRENT freed 349K, 3% free 17075K/17456K, paused 1ms+3ms, total 13ms
,E/UpdateRequestReceiver( 3797): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 3797): Update started
,I/ActivityManager(  772): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/CheckinRequestBuilder( 1313): Classify the device as Phone.
,I/CheckinTask( 1313): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1313): Checking schedule, now: 1454093083636 next: 1454135572624
,I/CheckinService( 1313): active receiver: disabled
I/ActivityManager(  772): Resuming delayed broadcast
,E/UpdateRequestReceiver( 3797): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/DownloadManager( 1206): Download 635 starting
,E/UpdateRequestReceiver( 3797): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/CheckinService( 1313): Recording last checkin time for package unspecified as 1454093083670
,I/DownloadManager( 1206): Download 634 starting
,E/UpdateRequestReceiver( 3797): Received malformed URL while handling Gservices.CHANGED_ACTION
W/ActivityThread( 1206): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/dalvikvm( 1206): GC_CONCURRENT freed 319K, 3% free 17162K/17576K, paused 1ms+2ms, total 12ms
,D/dalvikvm(  772): GC_EXPLICIT freed 973K, 48% free 26846K/51404K, paused 4ms+5ms, total 72ms
,I/ActivityManager(  772): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/ActivityManager(  772): Delay finish: com.google.android.gms/.checkin.CheckinService$Receiver
,I/Search.GservicesUpdateTask( 1170): Updating Gservices keys
,W/GAV2    ( 1170): Thread[Thread-87,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinService( 1313): Checkin interval check for package: unspecified last checkin: 1454093083670 min interval config: 0 actual interval: 153
,W/GAV2    ( 1170): Thread[Thread-87,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/dalvikvm( 1080): GC_CONCURRENT freed 425K, 4% free 18011K/18612K, paused 1ms+3ms, total 21ms
,D/dalvikvm( 1170): GC_CONCURRENT freed 352K, 5% free 17854K/18764K, paused 2ms+3ms, total 23ms
,I/CheckinService( 1313): Checking schedule, now: 1454093083846 next: 1454135572624
,I/CheckinService( 1313): active receiver: disabled
,I/DownloadManager( 1206): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1206): GC_CONCURRENT freed 429K, 3% free 17202K/17660K, paused 4ms+2ms, total 20ms
,I/ActivityManager(  772): Resuming delayed broadcast
,I/SystemUpdateService( 1313): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1313): onCreate
,D/SystemUpdateService( 1313): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1313): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1313): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1313): VFY: replacing opcode 0x71 at 0x004e
,I/DownloadManager( 1206): Download 635 finished with status SUCCESS
,I/SystemUpdateService( 1313): active receiver: enabled
,I/SystemUpdateService( 1313): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1313): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1313): now status is 0 (complete)
I/SystemUpdateService( 1313): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1313): file has been verified
,I/SystemUpdateService( 1313): OTA package size = 2571501
,I/SystemUpdateService( 1313): showing system update notification
,I/DownloadManager( 1206): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1313): GC_CONCURRENT freed 804K, 5% free 19303K/20176K, paused 3ms+4ms, total 28ms
,D/dalvikvm( 1080): GC_CONCURRENT freed 436K, 4% free 18037K/18612K, paused 2ms+1ms, total 27ms
,D/dalvikvm( 1080): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/DownloadManager( 1206): Download 634 finished with status SUCCESS
,D/SystemUpdateService( 1313): onDestroy
,E/DynamiteModule( 1313): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1313): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/system/framework/com.google.android.ble.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1313): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1313): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1313): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1313): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1313): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1313): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1313): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1313): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1313): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1313): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2407)
E/DynamiteModule( 1313): 	at android.app.ActivityThread.access$1700(ActivityThread.java:135)
E/DynamiteModule( 1313): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1272)
E/DynamiteModule( 1313): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1313): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 1313): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/DynamiteModule( 1313): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1313): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1313): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/DynamiteModule( 1313): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/DynamiteModule( 1313): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1313): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1313): Selected local version of com.google.android.gms.flags
,D/dalvikvm( 1080): GC_EXPLICIT freed 137K, 4% free 18040K/18612K, paused 2ms+3ms, total 19ms
,D/SystemEventReceiver( 1313): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1313): Updating ocr activity enabled=false
,W/ActivityManager(  772): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/dalvikvm( 1080): null clazz in OP_INSTANCE_OF, single-stepping
,I/Auth    ( 1080): [BroadcastManager] Broadcasting account services changed.
,D/GCM     ( 1080): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1313): GC_EXPLICIT freed 633K, 5% free 19319K/20176K, paused 5ms+7ms, total 62ms
,W/SQLiteConnectionPool( 1313): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/OcrModelManager( 1313): Updating downloaded model state (gservices changed)
,D/dalvikvm(  996): GC_CONCURRENT freed 824K, 6% free 19007K/20012K, paused 5ms+3ms, total 31ms
,E/dalvikvm(  996): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm(  996): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm(  996): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm(  996): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm(  996): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm(  996): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  996): VFY: replacing opcode 0x6e at 0x0012
,I/GCoreUlr(  996): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr(  996): DispatchingService.onCreate()
,D/GCM     ( 1080): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1080): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm(  996): GC_CONCURRENT freed 709K, 5% free 19048K/20012K, paused 4ms+5ms, total 42ms
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,D/dalvikvm( 3797): GC_CONCURRENT freed 428K, 3% free 16785K/17248K, paused 2ms+2ms, total 24ms
,I/GCoreUlr(  996): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/dalvikvm( 1080): GC_CONCURRENT freed 395K, 3% free 18060K/18612K, paused 1ms+3ms, total 26ms
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/GeofencerStateMachine(  996): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  (  996): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/DownloadManager( 1206): Download 636 starting
,D/dalvikvm( 1206): GC_CONCURRENT freed 350K, 3% free 17238K/17660K, paused 3ms+1ms, total 13ms
,I/GCoreUlr(  996): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr(  996): Unbound from all location providers
,I/GCoreUlr(  996): Place inference reporting - stopped
,I/GCoreUlr(  996): DispatchingService.onDestroy()
,I/GCoreUlr(  996): Stopping handler for UlrDispSvcFast
,I/DownloadManager( 1206): Download 637 starting
,I/DownloadManager( 1206): Ignoring Content-Length since Transfer-Encoding is also defined
,W/ctxmgr  (  996): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/DownloadManager( 1206): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm(  772): GC_EXPLICIT freed 813K, 48% free 26877K/51404K, paused 2ms+5ms, total 57ms
,I/GCoreUlr(  996): Unbound from all location providers
,I/GCoreUlr(  996): Place inference reporting - stopped
,E/ctxmgr  (  996): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/DownloadManager( 1206): Download 636 finished with status SUCCESS
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 3797): Update downloaded, starting installation
,I/UpdateFetcherService( 3797): Started installation
,D/dalvikvm( 3797): GC_CONCURRENT freed 377K, 3% free 16805K/17248K, paused 2ms+2ms, total 12ms
,I/DownloadManager( 1206): Download 637 finished with status SUCCESS
,W/ContextImpl( 3797): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 3797): Update downloaded, starting installation
,I/UpdateFetcherService( 3797): Started installation
,I/ConfigUpdateInstallReceiver(  772): Not installing, new version is <= current version
,I/ActivityManager(  772): Killing 2286:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/ActivityManager(  772): Killing 1758:com.google.android.calendar/u0a28 (adj 15): empty #18
,I/GAV2    ( 1170): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 1170): GC_CONCURRENT freed 412K, 5% free 17870K/18764K, paused 6ms+1ms, total 62ms
,D/CaptivePortalTracker(  772): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  772): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  772): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  772): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  772): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  772): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  772): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  772): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/Launcher( 1061): Deferring update until onResume
,I/Launcher( 1061): Deferring update until onResume
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "sms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/InputReader(  772): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "smsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mmsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "sms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "smsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mms"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  772):   Action: "android.intent.action.SENDTO"
I/PackageManager(  772):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  772):   Scheme: "mmsto"
I/PackageManager(  772): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 1170): Updating corpora: A: com.google.android.gms, C: MAYBE
,W/Launcher( 1061): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@4261fb80 new=com.google.android.velvet.VelvetApplication@4261fb80
,D/dalvikvm( 2350): GC_CONCURRENT freed 323K, 2% free 17661K/18016K, paused 2ms+7ms, total 28ms
I/ActivityManager(  772): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/GCoreNlp(  996): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  772): Resuming delayed broadcast
,D/PackageBroadcastService( 1313): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1313): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  772): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  772): Resuming delayed broadcast
,I/Icing   ( 1313): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1313): GC_CONCURRENT freed 888K, 5% free 19270K/20248K, paused 2ms+2ms, total 20ms
,I/Icing.InternalIcingCorporaProvider( 1170): UpdateCorporaTask done [took 357 ms] updated apps [took 357 ms] 
,I/Icing   ( 1313): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/Icing   ( 1313): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1313): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/Icing   ( 1313): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
,D/dalvikvm( 1170): GC_CONCURRENT freed 373K, 5% free 17881K/18764K, paused 2ms+1ms, total 12ms
,I/Icing   ( 1313): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,W/PackageSettings(  772): Skipping PackageSetting{4271cf68 com.example.hello/10116} due to missing metadata
,TIME-OUT KILL (timeout was 1200000ms)
```
