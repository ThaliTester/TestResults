#### Test 565307121a686b7_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2722): GC_CONCURRENT freed 332K, 3% free 17389K/17752K, paused 3ms+3ms, total 22ms
I/dalvikvm( 2722): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2722): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 2722): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 2722): GC_CONCURRENT freed 348K, 3% free 17547K/17928K, paused 2ms+3ms, total 24ms
D/dalvikvm( 2722): WAIT_FOR_CONCURRENT_GC blocked 10ms
,--------- beginning of /dev/log/system
I/ActivityManager(  758): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2759 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  758): Killing 1930:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2722): GC_CONCURRENT freed 246K, 2% free 17813K/18088K, paused 1ms+10ms, total 33ms
D/dalvikvm( 2722): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 2722): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2722): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2722): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2722): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2722): VFY: unable to resolve instance field 36
D/dalvikvm( 2722): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2722): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2722): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2722): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2722): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2722): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2722): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425d3cb8
D/dalvikvm( 2722): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425d3cb8
D/dalvikvm( 2722): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425d3cb8, skipping init
D/dalvikvm( 2722): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425d3cb8
D/dalvikvm( 2722): GC_CONCURRENT freed 422K, 3% free 17886K/18340K, paused 3ms+4ms, total 21ms
D/dalvikvm( 2722): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425d3cb8
V/JNIHelp ( 2722): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2722): GC_CONCURRENT freed 402K, 3% free 17966K/18400K, paused 1ms+2ms, total 18ms
D/dalvikvm( 2722): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x425d3cb8
D/dalvikvm( 2722): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x425d3cb8
D/dalvikvm( 2722): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x425d3cb8
D/dalvikvm( 2722): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x425d3cb8
D/dalvikvm( 2722): GC_FOR_ALLOC freed 107K, 3% free 18058K/18440K, paused 12ms, total 12ms
W/Quickoffice( 2759): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2759): Loading recent documents list
D/Quickoffice( 2759): The number of lines present in  /proc/mount 21
D/Quickoffice( 2759): Parsing the storagedefinition.xml.
D/Quickoffice( 2759): # of Storagedefinitions - 35
D/Quickoffice( 2759): The # of storage definitions available - 35
D/Quickoffice( 2759): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2759): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2759): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2759): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2759): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2759): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2759): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2759): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2759): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
I/ProviderInstaller( 2722): Installed default security provider GmsCore_OpenSSL
D/Quickoffice( 2759): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2759): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2759): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2759): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2759): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2759): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2759): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2759): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2759): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2759): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2759): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2759): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2759): Build properties are not configured for this storage definition.
D/Quickoffice( 2759): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2759): The # of mounts identified -  1
D/dalvikvm( 2759): GC_CONCURRENT freed 195K, 2% free 16917K/17144K, paused 3ms+2ms, total 15ms
D/com.google.android.apps.docs.quickoffice.X( 2759): Checking validity of 0 items
I/ActivityManager(  758): Killing 2148:com.google.android.music:main/u0a58 (adj 15): empty #17
W/ActivityManager(  758): No permission grants found for com.quickoffice.android
D/AndroidRuntime( 2771): 
D/AndroidRuntime( 2771): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2771): CheckJNI is OFF
D/ContentResolverUtil( 2759): There are 0 persisted uri permissions.
F/ActivityManager(  758): Service ServiceRecord{42d16b30 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bbb290 2148:com.google.android.music:main/u0a58} not same as in map: null
D/com.google.android.apps.docs.quickoffice.X( 2759): 0 items were valid
D/dalvikvm( 2771): Trying to load lib libjavacore.so 0x0
F/ActivityManager(  758): Service ServiceRecord{42d14da8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bbb290 2148:com.google.android.music:main/u0a58} not same as in map: null
D/dalvikvm( 2771): Added shared lib libjavacore.so 0x0
W/Quickoffice( 2759): Could not load clipboard.
D/dalvikvm( 2771): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2771): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2771): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
F/ActivityManager(  758): Service ServiceRecord{42cf1f18 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42bbb290 2148:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  758): Service ServiceRecord{42ceea70 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42bbb290 2148:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  758): Service ServiceRecord{42cece00 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42bbb290 2148:com.google.android.music:main/u0a58} not same as in map: null
W/Quickoffice( 2759): Could not store clipboard.
D/dalvikvm( 2771): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2771): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2771
D/PermissionCache(  181): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (119 us)
D/AndroidRuntime( 2771): Shutting down VM
D/dalvikvm( 2771): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2801 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1216): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1216): mic_close
I/ActivityManager(  758): Killing 1809:com.google.android.gm/u0a41 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 2801): Binding Chromium to main looper Looper (main, tid 1) {425c4a80}
I/LibraryLoader( 2801): Expected native library version number "",actual native library version number ""
I/chromium( 2801): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2801): Initializing chromium process, renderers=0
D/BluetoothManagerService(  758): Message: 20
I/MicroHotwordRecognitionRunner( 1216): Stopping hotword detection.
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@446718e0:true
I/MicroHotwordRecognitionRunner( 1216): Hotword detection finished
I/Adreno-EGL( 2801): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
I/Icing   ( 1317): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
W/chromium( 2801): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2801): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2801): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2801): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2801): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2801): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2801): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2801): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2801): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2801): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2801): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2801): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2801): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2801): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2801): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2801): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2801): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2801): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2801): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2801): CordovaWebView is running on device made by: LGE
I/Icing   ( 1317): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1317): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,I/Icing   ( 1317): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
D/OpenGLRenderer( 2801): Enabling debug mode 0
W/AwContents( 2801): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  758): Killing 2545:com.android.chrome/u0a31 (adj 15): empty #17
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +248ms
D/JsMessageQueue( 2801): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2801): GC_CONCURRENT freed 262K, 2% free 16894K/17188K, paused 3ms+2ms, total 19ms
D/dalvikvm( 2801): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x425c8d98
D/dalvikvm( 2801): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x425c8d98
D/jxcore_app_log( 2801): JniHelper::setJavaVM(0x414abf00), pthread_self() = 1984166848
I/chromium( 2801): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 2801): GC_CONCURRENT freed 195K, 2% free 17159K/17388K, paused 2ms+4ms, total 14ms
D/dalvikvm( 2801): GC_CONCURRENT freed 160K, 2% free 17500K/17700K, paused 1ms+1ms, total 16ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2801): GC_CONCURRENT freed 155K, 2% free 17840K/18040K, paused 2ms+1ms, total 15ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2801): GC_CONCURRENT freed 154K, 2% free 18182K/18384K, paused 1ms+1ms, total 12ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 2801): GC_CONCURRENT freed 158K, 2% free 18515K/18724K, paused 2ms+1ms, total 15ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 2801): GC_CONCURRENT freed 177K, 2% free 18920K/19152K, paused 1ms+1ms, total 13ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2801): GC_CONCURRENT freed 217K, 2% free 19414K/19692K, paused 2ms+1ms, total 16ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2801): GC_CONCURRENT freed 284K, 2% free 19999K/20352K, paused 2ms+1ms, total 16ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 2ms
D/dalvikvm( 2801): GC_CONCURRENT freed 318K, 2% free 20740K/21132K, paused 2ms+1ms, total 18ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2801): GC_CONCURRENT freed 391K, 3% free 21643K/22120K, paused 5ms+2ms, total 25ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2801): GC_CONCURRENT freed 649K, 4% free 22586K/23324K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2801): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 1485K, 7% free 22925K/24540K, paused 22ms, total 24ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 917K, 7% free 23047K/24540K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2801): Grow heap (frag case) to 23.228MB for 728606-byte allocation
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 0K, 6% free 23758K/25252K, paused 21ms, total 21ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 1281K, 8% free 23303K/25252K, paused 26ms, total 26ms
,I/dalvikvm-heap( 2801): Grow heap (frag case) to 23.826MB for 1092904-byte allocation
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 730K, 11% free 23639K/26320K, paused 24ms, total 24ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 1225K, 10% free 23708K/26320K, paused 26ms, total 30ms
,I/dalvikvm-heap( 2801): Grow heap (frag case) to 24.743MB for 1639352-byte allocation
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 1092K, 14% free 24217K/27924K, paused 25ms, total 25ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 1821K, 14% free 24284K/27924K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2801): Grow heap (frag case) to 26.086MB for 2459024-byte allocation
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 0K, 13% free 26685K/30328K, paused 25ms, total 25ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 4559K, 17% free 25249K/30328K, paused 26ms, total 26ms
,I/dalvikvm-heap( 2801): Grow heap (frag case) to 28.201MB for 3688532-byte allocation
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 107K, 16% free 28743K/33932K, paused 25ms, total 25ms
,D/dalvikvm( 2801): GC_CONCURRENT freed 2630K, 23% free 26274K/33932K, paused 2ms+3ms, total 35ms
,D/dalvikvm( 2801): GC_FOR_ALLOC freed 2031K, 23% free 26349K/33932K, paused 23ms, total 23ms
,W/jxcore-log( 2801): Initializing JXcore engine
,W/jxcore-log( 2801): JXcore engine is ready
,D/dalvikvm( 2801): GC_CONCURRENT freed 5905K, 31% free 23589K/33932K, paused 1ms+3ms, total 24ms
,W/jxcore-log( 2801): Starting JXcore engine
,W/jxcore-log( 2801): Platform android
W/jxcore-log( 2801): 
,W/jxcore-log( 2801): Process ARCH arm
W/jxcore-log( 2801): 
,I/jxcore-log( 2801): JXcore Cordova bridge is ready!
I/jxcore-log( 2801): 
,W/jxcore-log( 2801): JXcore engine is started
,E/jxcore  ( 2801): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2801): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2801): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/dalvikvm(  758): GC_FOR_ALLOC freed 24680K, 55% free 25837K/57356K, paused 95ms, total 96ms
,W/PluginManager( 2801): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 130ms. Plugin should use CordovaInterface.getThreadPool().
,W/Sidekick_LocationOracleImpl( 1216): Best location was null
,W/IInputConnectionWrapper( 2801): showStatusIcon on inactive InputConnection
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,W/GCoreFlp(  981): No location to return for getLastLocation()
,D/dalvikvm( 1216): GC_FOR_ALLOC freed 1018K, 7% free 17899K/19148K, paused 25ms, total 25ms
,I/dalvikvm-heap( 1216): Grow heap (frag case) to 18.117MB for 640016-byte allocation
,D/dalvikvm( 1317): GC_CONCURRENT freed 599K, 4% free 19060K/19692K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 1216): GC_FOR_ALLOC freed <1K, 4% free 18524K/19148K, paused 16ms, total 16ms
,I/MicroHotwordRecognitionRunner( 1216): Starting hotword detection.
,D/audio_hw_primary(  184): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  184): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  184): Error: ACDB AudProc vol returned = -19
,D/dalvikvm( 1216): GC_CONCURRENT freed 18K, 4% free 18529K/19148K, paused 3ms+4ms, total 22ms
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1132): GC_CONCURRENT freed 352K, 4% free 17973K/18660K, paused 1ms+2ms, total 21ms,
,I/SearchController( 1216): #onHotwordDetectorStarted
,E/libEGL  ( 2801): call to OpenGL ES API with no current context (logged once per thread)
,D/dalvikvm( 1132): GC_CONCURRENT freed 434K, 4% free 17944K/18660K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 1216): GC_CONCURRENT freed 471K, 4% free 18557K/19148K, paused 2ms+2ms, total 14ms
,I/VacuumService(  981): Vacuum at: now=1453241229212 tag=VacuumService
,D/dalvikvm( 1132): GC_CONCURRENT freed 446K, 4% free 18005K/18660K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 397K, 3% free 17432K/17864K, paused 2ms+1ms, total 23ms
,D/Finsky  ( 1664): [1] 5.onFinished: Installation state replication succeeded.
,I/PowerManagerService(  758): Going to sleep due to screen timeout...
,I/Adreno-EGL(  758): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  181): Screen released, type=0 flinger=0xb81c7450
,D/qdhwcomposer(  181): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  181): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  758): Excessive delay in blankDisplay() while turning screen off: 276ms
,V/KeyguardServiceDelegate(  758): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42c86c28)
,V/KeyguardServiceDelegate(  758): **** SHOWN CALLED ****
I/WindowManager(  758): No lock screen! windowToken=null
,I/MicrophoneInputStream( 1216): mic_close
,I/SearchController( 1216): #onHotwordDetectorStopped(false)
,D/NfcService( 1025): NFC-C OFF
I/ActivityManager(  758): Killing 1705:com.google.android.calendar/u0a28 (adj 15): empty #17
,D/dalvikvm(  758): GC_CONCURRENT freed 1415K, 54% free 26613K/57356K, paused 3ms+3ms, total 66ms
,I/MicroHotwordRecognitionRunner( 1216): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1216): Stopping hotword detection.
,I/rmt_storage(  177): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8b5f160
I/rmt_storage(  177): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  177): wakelock acquired: 1, error no: 2
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1196035552)
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  177): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1196035552) wakelock released: 1, error no: 0
I/rmt_storage(  177): 
,I/rmt_storage(  177): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8b5f160
,D/dalvikvm( 1216): GC_CONCURRENT freed 1121K, 7% free 18037K/19192K, paused 2ms+4ms, total 19ms
,D/dalvikvm( 1132): GC_CONCURRENT freed 447K, 4% free 18035K/18660K, paused 2ms+1ms, total 25ms
,D/dalvikvm(  981): GC_CONCURRENT freed 536K, 4% free 18702K/19332K, paused 2ms+2ms, total 26ms
,I/PhenotypeConfigurator(  981): Scheduling Phenotype for one-off execution 4356 seconds from now (1453241310602)
,D/GetConfigurationSnapshotOperation(  981): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  981): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  981): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  981): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  981): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  981): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  981): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  981): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  981): Using platform SSLCertificateSocketFactory
,I/dalvikvm(  981): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  981): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  981): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  981): GC_CONCURRENT freed 426K, 3% free 18863K/19412K, paused 3ms+3ms, total 19ms
,D/dalvikvm(  981): GC_CONCURRENT freed 577K, 4% free 19026K/19696K, paused 4ms+6ms, total 35ms
,D/dalvikvm(  981): GC_CONCURRENT freed 632K, 4% free 19134K/19860K, paused 1ms+4ms, total 22ms
,D/dalvikvm(  981): GC_CONCURRENT freed 787K, 5% free 19147K/20028K, paused 1ms+7ms, total 30ms
,D/dalvikvm(  981): GC_CONCURRENT freed 819K, 5% free 19153K/20064K, paused 1ms+5ms, total 29ms
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  981): GC_FOR_ALLOC freed 730K, 6% free 19053K/20072K, paused 34ms, total 35ms
,I/dalvikvm-heap(  981): Grow heap (frag case) to 18.711MB for 16400-byte allocation
,D/dalvikvm(  981): GC_FOR_ALLOC freed <1K, 6% free 19068K/20092K, paused 28ms, total 28ms
,D/dalvikvm(  981): GC_FOR_ALLOC freed 304K, 7% free 18820K/20092K, paused 15ms, total 15ms
,I/EventLogService( 1317): Aggregate from 1453239510937 (log), 1453239510937 (data)
,I/wpa_supplicant(  947): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  758): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  758): Attempting to switch to mobile
,D/ConnectivityService(  758): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  758): android_net_utils_resetConnections in env=0x7628aec8 clazz=0x5e400001 iface=wlan0 mask=0x3
D/ConnectivityService(  758): resetConnections(wlan0, 3)
,V/NativeCrypto( 1132): Read error: ssl=0x7940d070: I/O error during system call, Connection timed out
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1132): SSL shutdown failed: ssl=0x7940d070: I/O error during system call, Broken pipe
,D/Nat464Xlat(  758): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  758): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  947): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  947): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  947): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  947): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  758): scanCount==0 - aborting
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  758): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1252): GC_CONCURRENT freed 353K, 3% free 16741K/17124K, paused 22ms+1ms, total 32ms
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/ActivityManager(  758): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3027 uid=10031 gids={50031, 3003, 1028, 1015}
,I/Babel   ( 1968): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1317): num updated entries: 0
I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3027): VFY: unable to resolve instance field 68
,D/dalvikvm( 3027): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3027): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3027): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3027): VFY: unable to resolve instance field 68
,D/dalvikvm( 3027): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3027): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3027): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3027): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3027): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
I/ActivityManager(  758): Killing 2576:com.google.android.keep/u0a52 (adj 15): empty #17
,D/WifiStateMachine(  758): VerifyingLinkState enter
,D/WifiStateMachine(  758): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  758): CaptivePortalCheckState enter
D/ConnectivityService(  758): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  758): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  758): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  758): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  758): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b12ef0
,D/Nat464Xlat(  758): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  758): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  758): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  758):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  758): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  758): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1968): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  758): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  758): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  758): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  758): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  758): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  758): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  758): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  758): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  758): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1132): GC_CONCURRENT freed 463K, 4% free 17971K/18660K, paused 1ms+1ms, total 20ms
,D/dalvikvm( 1664): GC_FOR_ALLOC freed 341K, 4% free 17222K/17904K, paused 9ms, total 9ms
,I/dalvikvm-heap( 1664): Grow heap (frag case) to 16.921MB for 79892-byte allocation
,D/dalvikvm( 1664): GC_FOR_ALLOC freed <1K, 4% free 17300K/17984K, paused 10ms, total 10ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 374K, 4% free 17358K/17984K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 263K, 3% free 17483K/17984K, paused 2ms+0ms, total 12ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 123K, 2% free 17745K/17984K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 165K, 2% free 18076K/18288K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 1664): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 1664): GC_FOR_ALLOC freed 214K, 2% free 18200K/18528K, paused 10ms, total 11ms
,D/dalvikvm( 1664): GC_FOR_ALLOC freed 183K, 3% free 18262K/18656K, paused 11ms, total 11ms
,D/dalvikvm( 1664): GC_FOR_ALLOC freed 211K, 3% free 18355K/18784K, paused 11ms, total 11ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 260K, 2% free 18547K/18912K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 189K, 2% free 18978K/19196K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 1664): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 484K, 3% free 19252K/19768K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 1664): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 610K, 4% free 19468K/20116K, paused 1ms+3ms, total 21ms
,D/Finsky  ( 1664): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1132): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1664): Failed write_ctrl(u 56) res=-1 errno=22
I/qtaguid ( 1664): Untagging socket 56 failed errno=-22
,W/NetworkManagementSocketTagger( 1664): untagSocket(56) failed with errno -22
,D/dalvikvm( 1664): GC_CONCURRENT freed 659K, 4% free 19683K/20416K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 1664): GC_CONCURRENT freed 703K, 4% free 19884K/20624K, paused 2ms+1ms, total 23ms
,D/Finsky  ( 1664): [1] UpdateChecker.showUpdateNotifications: Notifying user that 12 applications have outstanding updates.
,D/Finsky  ( 1664): [1] DailyHygiene.flushEventLogs: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 1664): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  758): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  758): Done.
,D/ConnectivityService(  758): Setting timer for 720seconds
,TIME-OUT KILL (timeout was 1200000ms)
```
