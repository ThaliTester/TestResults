#### Test 549702618c0ebdb_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 2787): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2787): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 2787): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 2787): GC_CONCURRENT freed 442K, 3% free 17586K/18060K, paused 1ms+1ms, total 12ms
D/dalvikvm( 2787): WAIT_FOR_CONCURRENT_GC blocked 8ms
I/dalvikvm-heap( 2787): Grow heap (frag case) to 17.278MB for 79892-byte allocation
D/dalvikvm( 2787): GC_FOR_ALLOC freed 4K, 3% free 17661K/18140K, paused 11ms, total 11ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 322K, 2% free 17852K/18204K, paused 1ms+2ms, total 13ms
D/dalvikvm( 2787): WAIT_FOR_CONCURRENT_GC blocked 3ms
--------- beginning of /dev/log/system
I/ActivityManager(  774): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2827 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  774): Killing 1972:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2787): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2787): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2787): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2787): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2787): VFY: unable to resolve instance field 36
D/dalvikvm( 2787): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2787): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2787): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2787): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2787): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2787): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2787): GC_CONCURRENT freed 389K, 3% free 17864K/18288K, paused 2ms+0ms, total 14ms
D/dalvikvm( 2787): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42708d80
D/dalvikvm( 2787): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42708d80
D/dalvikvm( 2787): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42708d80, skipping init
D/dalvikvm( 2787): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42708d80
D/dalvikvm( 2787): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42708d80
V/JNIHelp ( 2787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2787): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42708d80
D/dalvikvm( 2787): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42708d80
D/dalvikvm( 2787): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42708d80
D/dalvikvm( 2787): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42708d80
D/dalvikvm( 2787): GC_CONCURRENT freed 308K, 2% free 17945K/18288K, paused 2ms+1ms, total 14ms
W/Quickoffice( 2827): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2827): Loading recent documents list
D/Quickoffice( 2827): The number of lines present in  /proc/mount 21
D/Quickoffice( 2827): Parsing the storagedefinition.xml.
D/Quickoffice( 2827): # of Storagedefinitions - 35
D/Quickoffice( 2827): The # of storage definitions available - 35
D/Quickoffice( 2827): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2827): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2827): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2827): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2827): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2827): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2827): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
I/ProviderInstaller( 2787): Installed default security provider GmsCore_OpenSSL
D/Quickoffice( 2827): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2827): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2827): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2827): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2827): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2827): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2827): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2827): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2827): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2827): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2827): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2827): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2827): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2827): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2827): Build properties are not configured for this storage definition.
D/Quickoffice( 2827): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2827): The # of mounts identified -  1
I/ActivityManager(  774): Killing 2455:com.android.chrome/u0a31 (adj 15): empty #17
D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
D/dalvikvm( 2827): GC_CONCURRENT freed 200K, 2% free 16935K/17168K, paused 3ms+8ms, total 22ms
D/com.google.android.apps.docs.quickoffice.X( 2827): Checking validity of 0 items
D/ContentResolverUtil( 2827): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2827): 0 items were valid
D/ConnectivityService(  774): Done.
D/ConnectivityService(  774): Setting timer for 720seconds
W/ActivityManager(  774): No permission grants found for com.quickoffice.android
W/Quickoffice( 2827): Could not load clipboard.
D/AndroidRuntime( 2838): 
D/AndroidRuntime( 2838): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2838): CheckJNI is OFF
W/Quickoffice( 2827): Could not store clipboard.
D/dalvikvm( 2838): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2838): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2838): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2838): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2838): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2838): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2838): Calling main entry com.android.commands.am.Am
I/ActivityManager(  774): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2838
D/PermissionCache(  185): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
D/AndroidRuntime( 2838): Shutting down VM
D/dalvikvm( 2838): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+1ms, total 2ms
I/ActivityManager(  774): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2857 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1228): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1228): mic_close
I/ActivityManager(  774): Killing 1022:com.google.android.keep/u0a52 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1228): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1228): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2857): Binding Chromium to main looper Looper (main, tid 1) {425aa2d8}
I/LibraryLoader( 2857): Expected native library version number "",actual native library version number ""
I/chromium( 2857): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2857): Initializing chromium process, renderers=0
D/BluetoothManagerService(  774): Message: 20
D/BluetoothManagerService(  774): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@443e5c78:true
I/Icing   ( 1332): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Adreno-EGL( 2857): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2857): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/dalvikvm( 1228): GC_CONCURRENT freed 387K, 3% free 18245K/18664K, paused 2ms+8ms, total 29ms
I/dalvikvm( 2857): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2857): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2857): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2857): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2857): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2857): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2857): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2857): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2857): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2857): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2857): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2857): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2857): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2857): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2857): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2857): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2857): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2857): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2857): CordovaWebView is running on device made by: LGE
,D/dalvikvm( 1332): GC_CONCURRENT freed 556K, 3% free 19158K/19748K, paused 3ms+7ms, total 37ms
,I/Icing   ( 1332): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
,I/Icing   ( 1332): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/OpenGLRenderer( 2857): Enabling debug mode 0
,W/AwContents( 2857): nativeOnDraw failed; clearing to background color.
,I/Icing   ( 1332): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/ActivityManager(  774): Displayed com.test.thalitest/.MainActivity: +287ms
I/ActivityManager(  774): Killing 2483:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,D/JsMessageQueue( 2857): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2857): GC_CONCURRENT freed 235K, 2% free 16864K/17128K, paused 1ms+1ms, total 17ms
D/dalvikvm( 2857): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425b0a40
D/dalvikvm( 2857): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425b0a40
D/jxcore_app_log( 2857): JniHelper::setJavaVM(0x41492f00), pthread_self() = 1983949952
D/JX-Cordova( 2857): jxcore cordova android initializing
D/dalvikvm( 2857): GC_CONCURRENT freed 221K, 2% free 17156K/17408K, paused 1ms+2ms, total 12ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2857): GC_CONCURRENT freed 157K, 2% free 17502K/17700K, paused 1ms+1ms, total 13ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2857): GC_CONCURRENT freed 155K, 2% free 17846K/18044K, paused 1ms+1ms, total 17ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2857): GC_CONCURRENT freed 152K, 2% free 18191K/18388K, paused 2ms+1ms, total 19ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2857): GC_CONCURRENT freed 157K, 2% free 18527K/18732K, paused 0ms+0ms, total 11ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2857): GC_CONCURRENT freed 176K, 2% free 18939K/19168K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2857): GC_CONCURRENT freed 219K, 2% free 19445K/19720K, paused 2ms+3ms, total 24ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 2857): GC_CONCURRENT freed 277K, 2% free 20055K/20392K, paused 2ms+4ms, total 26ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2857): GC_CONCURRENT freed 324K, 2% free 20815K/21208K, paused 1ms+2ms, total 30ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/dalvikvm( 2857): GC_CONCURRENT freed 397K, 3% free 21747K/22220K, paused 2ms+2ms, total 20ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2857): GC_CONCURRENT freed 958K, 5% free 22437K/23464K, paused 2ms+1ms, total 22ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/dalvikvm( 2857): GC_CONCURRENT freed 1665K, 8% free 22582K/24384K, paused 2ms+2ms, total 24ms
D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 2857): GC_FOR_ALLOC freed 186K, 8% free 22508K/24384K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2857): Grow heap (frag case) to 22.703MB for 728606-byte allocation
,D/dalvikvm( 2857): GC_FOR_ALLOC freed <1K, 8% free 23220K/25096K, paused 20ms, total 20ms
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 1235K, 10% free 22801K/25096K, paused 20ms, total 20ms
,D/dalvikvm( 2857): GC_CONCURRENT freed 1666K, 8% free 23171K/25096K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 363K, 8% free 23129K/25096K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2857): Grow heap (frag case) to 24.177MB for 1639352-byte allocation
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 0K, 8% free 24730K/26700K, paused 20ms, total 20ms
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 2912K, 12% free 23824K/26792K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2857): Grow heap (frag case) to 25.637MB for 2459024-byte allocation
,D/dalvikvm( 2857): GC_CONCURRENT freed 4K, 11% free 26221K/29196K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2857): GC_CONCURRENT freed 4596K, 16% free 24772K/29428K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 2857): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 327K, 17% free 24489K/29428K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2857): Grow heap (frag case) to 27.459MB for 3688532-byte allocation
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 4K, 15% free 28087K/33032K, paused 23ms, total 23ms
,D/dalvikvm( 2857): GC_CONCURRENT freed 2588K, 23% free 25709K/33032K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 752K, 23% free 25703K/33032K, paused 19ms, total 20ms
,I/dalvikvm-heap( 2857): Grow heap (frag case) to 27.720MB for 2718876-byte allocation
,W/jxcore-log( 2857): Initializing JXcore engine
,W/jxcore-log( 2857): JXcore engine is ready
,D/dalvikvm( 2857): GC_FOR_ALLOC freed 5089K, 35% free 23268K/35688K, paused 27ms, total 27ms
,W/jxcore-log( 2857): Starting JXcore engine
,W/jxcore-log( 2857): Platform android
W/jxcore-log( 2857): 
,W/jxcore-log( 2857): Process ARCH arm
W/jxcore-log( 2857): 
,I/jxcore-log( 2857): JXcore Cordova bridge is ready!
I/jxcore-log( 2857): 
,W/jxcore-log( 2857): JXcore engine is started
,I/chromium( 2857): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2857): Toggling radios to true
I/jxcore-log( 2857): 
,D/BluetoothAdapter( 2857): enable(): BT is already enabled..!
,D/WifiService(  774): setWifiEnabled: true pid=2857, uid=10108
I/jxcore-log( 2857): Radios toggled
I/jxcore-log( 2857): 
,I/wpa_supplicant(  938): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  774): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  774): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  774): Attempting to switch to mobile
,D/ConnectivityService(  774): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  774): android_net_utils_resetConnections in env=0x77187f40 clazz=0x5ef00001 iface=wlan0 mask=0x3
D/ConnectivityService(  774): resetConnections(wlan0, 3)
,V/NativeCrypto( 1130): Read error: ssl=0x7730eb98: I/O error during system call, Connection timed out
,V/NativeCrypto( 1130): SSL shutdown failed: ssl=0x7730eb98: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  774): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  938): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  938): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  938): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  938): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  774): scanCount==0 - aborting
,D/WifiStateMachine(  774): VerifyingLinkState enter
,D/WifiStateMachine(  774): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  774): CaptivePortalCheckState enter
D/ConnectivityService(  774): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  774): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  774): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  774): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  774): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a50978
,D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  774): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  774): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2229): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@426c5b38 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2229): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1332): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1332): onCreate
,D/SystemUpdateService( 1332): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1332): active receiver: enabled
,I/SystemUpdateService( 1332): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1332): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1332): now status is 0 (complete)
I/SystemUpdateService( 1332): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1332): file has been verified
,I/SystemUpdateService( 1332): OTA package size = 2571501
,I/SystemUpdateService( 1332): showing system update notification
,D/SystemUpdateService( 1332): onDestroy
,I/ActivityManager(  774): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2981 uid=10031 gids={50031, 3003, 1028, 1015}
,D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2981): VFY: unable to resolve instance field 68
,D/dalvikvm( 2981): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2981): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2981): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2981): VFY: unable to resolve instance field 68
,D/dalvikvm( 2981): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2981): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2981): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2981): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2981): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  774): Killing 2229:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  774): Service ServiceRecord{42ce4ea8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42c2f178 2229:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{42ca1f70 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42c2f178 2229:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{42c9d390 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42c2f178 2229:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{42c8b7b0 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42c2f178 2229:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  774): Service ServiceRecord{42bd8698 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42c2f178 2229:com.google.android.music:main/u0a58} not same as in map: null
,D/ConnectivityService(  774): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  774): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  774):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  774): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  774): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  774): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1041): GC_CONCURRENT freed 335K, 3% free 17063K/17428K, paused 2ms+1ms, total 11ms
,I/SystemUpdateService( 1332): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1332): onCreate
,D/SystemUpdateService( 1332): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1332): active receiver: enabled
,I/SystemUpdateService( 1332): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1332): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1332): now status is 0 (complete)
I/SystemUpdateService( 1332): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1332): file has been verified
,I/SystemUpdateService( 1332): OTA package size = 2571501
,I/SystemUpdateService( 1332): showing system update notification
,I/jxcore-log( 2857): Test app app.js loaded
I/jxcore-log( 2857): 
,I/Choreographer( 2857): Skipped 374 frames!  The application may be doing too much work on its main thread.
,D/SystemUpdateService( 1332): onDestroy
,I/chromium( 2857): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm( 1228): GC_CONCURRENT freed 845K, 6% free 17830K/18784K, paused 3ms+5ms, total 35ms
,D/dalvikvm( 2525): GC_CONCURRENT freed 1066K, 6% free 19790K/20892K, paused 2ms+2ms, total 23ms
,D/Finsky  ( 2525): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm(  774): GC_EXPLICIT freed 23505K, 54% free 26921K/57440K, paused 3ms+6ms, total 114ms
,D/dalvikvm( 1130): GC_CONCURRENT freed 398K, 3% free 18086K/18608K, paused 1ms+2ms, total 16ms
,I/VacuumService( 1000): Vacuum at: now=1452267134462 tag=VacuumService
,D/dalvikvm( 1130): GC_CONCURRENT freed 498K, 4% free 18055K/18652K, paused 3ms+2ms, total 24ms
,D/CaptivePortalTracker(  774): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  774): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  774): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  774): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  774): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  774): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  774): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  774): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/rmt_storage(  181): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb7d02160
I/rmt_storage(  181): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  181): wakelock acquired: 1, error no: 2
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211096544)
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211096544) wakelock released: 1, error no: 0
I/rmt_storage(  181): 
,I/rmt_storage(  181): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb7d02160
,I/PowerManagerService(  774): Going to sleep due to screen timeout...
,I/Adreno-EGL(  774): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  185): Screen released, type=0 flinger=0xb709b450
,D/qdhwcomposer(  185): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  185): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  774): Excessive delay in blankDisplay() while turning screen off: 300ms
,V/KeyguardServiceDelegate(  774): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42d28138)
,V/KeyguardServiceDelegate(  774): **** SHOWN CALLED ****
I/WindowManager(  774): No lock screen! windowToken=null
,D/NfcService( 1074): NFC-C OFF
,I/ClearcutLoggerApiImpl( 1130): disconnect managed GoogleApiClient
,I/PhenotypeConfigurator( 1000): Scheduling Phenotype for one-off execution 14365 seconds from now (1452267213759)
,D/dalvikvm( 1000): GC_CONCURRENT freed 549K, 4% free 18761K/19412K, paused 2ms+3ms, total 19ms
,D/GetConfigurationSnapshotOperation( 1000): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1000): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1000): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1000): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1000): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1000): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1000): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1000): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1000): Using platform SSLCertificateSocketFactory
,I/dalvikvm( 1000): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1000): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1000): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1000): GC_CONCURRENT freed 578K, 4% free 18895K/19568K, paused 4ms+6ms, total 35ms
,D/dalvikvm( 1000): GC_CONCURRENT freed 613K, 4% free 19030K/19736K, paused 3ms+6ms, total 36ms
,D/dalvikvm( 1000): GC_CONCURRENT freed 620K, 4% free 19142K/19856K, paused 2ms+3ms, total 21ms
,D/dalvikvm( 1000): GC_CONCURRENT freed 738K, 5% free 19126K/19956K, paused 3ms+4ms, total 24ms
,D/dalvikvm( 1000): GC_CONCURRENT freed 847K, 5% free 19114K/20056K, paused 3ms+6ms, total 37ms
,D/dalvikvm( 1000): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 1000): GC_FOR_ALLOC freed 671K, 6% free 18993K/20056K, paused 41ms, total 43ms
,I/jxcore-log( 2857): TAP version 13
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # multiplex can send data
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 1 String should be length:200
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # basic
I/jxcore-log( 2857): 
,I/dalvikvm( 2787): Could not find method android.content.Context.checkSelfPermission, referenced from method ija.a
,W/dalvikvm( 2787): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 2787): VFY: replacing opcode 0x6e at 0x001c
,D/dalvikvm( 2787): GC_CONCURRENT freed 192K, 2% free 18154K/18404K, paused 2ms+3ms, total 21ms
,I/PeopleSync( 1332): onPerformSync() [5005f081]
,W/Flag    ( 2787): Duration spec must be at least 2 characters long: 
,D/dalvikvm( 1332): GC_CONCURRENT freed 633K, 4% free 19265K/19932K, paused 3ms+4ms, total 45ms
,I/PeopleSync( 1332): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1332): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 1332): Using Auth Proxy for data requests.
,W/BaseAppContext( 1332): Using Auth Proxy for data requests.
,D/dalvikvm( 1130): GC_CONCURRENT freed 423K, 4% free 18020K/18652K, paused 1ms+1ms, total 18ms
,W/BaseAppContext( 1332): Using Auth Proxy for data requests.
,I/PeopleSync( 1332): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2787): GC_CONCURRENT freed 356K, 3% free 18189K/18576K, paused 3ms+1ms, total 18ms
,V/NativeCrypto( 1130): SSL shutdown failed: ssl=0x773420f0: I/O error during system call, Connection timed out
,D/dalvikvm( 1130): GC_CONCURRENT freed 409K, 4% free 18005K/18652K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 2787): GC_FOR_ALLOC freed 184K, 2% free 18386K/18732K, paused 26ms, total 27ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 400K, 3% free 18489K/18920K, paused 3ms+1ms, total 26ms
,V/NativeCrypto( 1332): Write error: ssl=0x8014d638: I/O error during system call, Connection timed out
,V/NativeCrypto( 1332): SSL shutdown failed: ssl=0x8014d638: I/O error during system call, Connection timed out
,D/dalvikvm( 2787): GC_CONCURRENT freed 493K, 3% free 18505K/19032K, paused 3ms+4ms, total 22ms
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,W/isz     ( 2787): Application name is not set. Call Builder#setApplicationName.
,W/isz     ( 2787): Application name is not set. Call Builder#setApplicationName.
,W/isz     ( 2787): Application name is not set. Call Builder#setApplicationName.
,D/dalvikvm( 2787): GC_CONCURRENT freed 644K, 4% free 18388K/19068K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 1332): GC_CONCURRENT freed 721K, 4% free 19284K/20036K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 1130): GC_CONCURRENT freed 388K, 4% free 18011K/18652K, paused 2ms+3ms, total 27ms
,I/PeopleSync( 1332): Sync finished, successful=true, took 1292ms
,I/PeopleContactsSync( 1332): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1332): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1332): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/dalvikvm( 2384): GC_CONCURRENT freed 256K, 2% free 17035K/17324K, paused 6ms+3ms, total 38ms
,I/PeopleContactsSync( 1332): CP2 cleanup done, kept= duration=73 ms
,I/PeopleContactsSync( 1332): ===CP2 sync finished, success=true, time=93,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1332): ***Sync finished***, duration: 1665 [5005f081]
,D/dalvikvm( 2787): GC_CONCURRENT freed 513K, 4% free 18385K/19068K, paused 10ms+4ms, total 53ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 484K, 4% free 18407K/19068K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 514K, 4% free 18418K/19068K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 413K, 3% free 18520K/19068K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2787): GC_CONCURRENT freed 510K, 3% free 18535K/19080K, paused 3ms+2ms, total 18ms
,D/dalvikvm( 2787): GC_FOR_ALLOC freed 65K, 3% free 18565K/19132K, paused 19ms, total 19ms
,D/dalvikvm( 2787): GC_FOR_ALLOC freed 59K, 4% free 18564K/19188K, paused 24ms, total 24ms
,I/dalvikvm-heap( 2787): Grow heap (frag case) to 18.307MB for 159002-byte allocation
,D/dalvikvm( 2787): GC_FOR_ALLOC freed <1K, 4% free 18719K/19344K, paused 15ms, total 15ms
,D/dalvikvm( 1000): GC_FOR_ALLOC freed 318K, 6% free 18859K/20056K, paused 16ms, total 16ms
,I/jxcore-log( 2857): ok 2 sane
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # another
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 3 sane
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 4 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 5 null
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 6 (unnamed assert)
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 7 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 8 should not throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 9 (unnamed assert)
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 10 (unnamed assert)
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 11 should not throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 12 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 13 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 14 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # failed to get mobile documents path
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 15 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 16 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 17 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 18 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #init should register the networkChanged event
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 19 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on null device name
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 20 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 21 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on non-number port
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 22 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on NaN port
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 23 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on negative port
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 24 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should throw on too large port
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 25 should throw
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 26 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 27 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 28 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 29 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 30 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 31 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 2857): 
,I/ClearcutLoggerApiImpl( 1332): disconnect managed GoogleApiClient
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 32 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 33 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 34 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 35 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 36 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 37 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 38 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 39 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 40 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # should call Mobile("Disconnect") without an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 41 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 42 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 43 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): ok 44 should be equal
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # setup
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 2857): 
,I/jxcore-log( 2857): # teardown
I/jxcore-log( 2857): 
,I/dalvikvm( 2857): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 2857): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2857): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 2857): Shutting down VM
,W/dalvikvm( 2857): threadid=1: thread exiting with uncaught exception (group=0x41559ba8)
,E/AndroidRuntime( 2857): FATAL EXCEPTION: main
E/AndroidRuntime( 2857): Process: com.test.thalitest, PID: 2857
E/AndroidRuntime( 2857): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 2857): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 2857): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 2857): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 2857): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 2857): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 2857): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 2857): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 2857): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 2857): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 2857): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2857): ,	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2857): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2857): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  774):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  774): Killing 1830:com.google.android.gm/u0a41 (adj 15): empty #17
,I/Process ( 2857): Sending signal. PID: 2857 SIG: 9
,I/ActivityManager(  774): Process com.test.thalitest (pid 2857) has died.
,I/WindowState(  774): WIN DEATH: Window{44c33eb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,W/ProcessCpuTracker(  774): Skipping unknown process pid 3256
,W/ProcessCpuTracker(  774): Skipping unknown process pid 3261
,W/ProcessCpuTracker(  774): Skipping unknown process pid 3262
,D/ConnectivityService(  774): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  774): Done.
,D/ConnectivityService(  774): Setting timer for 720seconds
,I/EventLogService( 1332): Aggregate from 1452266735454 (log), 1452266735454 (data)
,D/dalvikvm(  774): GC_EXPLICIT freed 1924K, 54% free 26860K/57440K, paused 2ms+4ms, total 56ms
,I/dalvikvm(  774): Jit: resizing JitTable from 8192 to 16384
,I/ProcessStatsService(  774): Prepared write state in 31ms
,I/ProcessStatsService(  774): Prepared write state in 4ms
,I/ProcessStatsService(  774): Pruning old procstats: /data/system/procstats/state-2016-01-07-23-15-00.bin
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1130): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  774): Killing 2827:com.quickoffice.android/u0a65 (adj 15): empty for 1802s
,I/ActivityManager(  774): Killing 2757:com.android.musicfx/u0a13 (adj 15): empty for 1803s
,I/ActivityManager(  774): Killing 2729:com.google.android.partnersetup/u0a11 (adj 15): empty for 1803s
,I/ActivityManager(  774): Killing 2704:com.android.defcontainer/u0a4 (adj 15): empty for 1803s
,I/ActivityManager(  774): Killing 2323:com.android.providers.calendar/u0a1 (adj 15): empty for 1822s
,I/ActivityManager(  774): Killing 1758:com.google.android.calendar/u0a28 (adj 15): empty for 1842s
,D/ConnectivityService(  774): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,TIME-OUT KILL (timeout was 1800000ms)
```
