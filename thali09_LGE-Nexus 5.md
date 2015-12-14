#### Test 5357450766a890e_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/GAv4    ( 2700): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2700):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2700):   adb logcat -s GAv4
I/dalvikvm( 2700): Could not find method android.content.Context.checkSelfPermission, referenced from method asa.a
W/dalvikvm( 2700): VFY: unable to resolve virtual method 1616: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 2700): VFY: replacing opcode 0x6e at 0x001b
W/GAv4    ( 2700): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/dalvikvm( 2700): GC_CONCURRENT freed 300K, 2% free 17259K/17588K, paused 2ms+2ms, total 13ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 3ms
W/GAv4    ( 2700): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2700): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/dalvikvm( 2700): GC_CONCURRENT freed 259K, 2% free 17511K/17800K, paused 3ms+1ms, total 13ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 5ms
W/AnalyticsTrackerProxyImpl( 2700): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.474.23.35, sample rate 1.0
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 12ms
I/dalvikvm( 2700): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2700): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 2700): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 2700): GC_CONCURRENT freed 409K, 3% free 17542K/17980K, paused 2ms+1ms, total 13ms
--------- beginning of /dev/log/system
I/ActivityManager(  771): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2737 uid=10065 gids={50065, 3003, 1028, 1015}
D/dalvikvm( 2700): GC_CONCURRENT freed 236K, 2% free 17775K/18060K, paused 1ms+1ms, total 14ms
I/ActivityManager(  771): Killing 1934:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2700): GC_CONCURRENT freed 286K, 2% free 18001K/18316K, paused 2ms+1ms, total 14ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2700): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2700): VFY: unable to resolve instance field 36
D/dalvikvm( 2700): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2700): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2700): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2700): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429c8bb8
D/dalvikvm( 2700): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429c8bb8
D/dalvikvm( 2700): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429c8bb8, skipping init
D/dalvikvm( 2700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429c8bb8
D/dalvikvm( 2700): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429c8bb8
V/JNIHelp ( 2700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2700): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x429c8bb8
D/dalvikvm( 2700): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x429c8bb8
D/dalvikvm( 2700): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x429c8bb8
D/dalvikvm( 2700): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x429c8bb8
D/dalvikvm( 2700): GC_CONCURRENT freed 536K, 4% free 17965K/18536K, paused 2ms+2ms, total 24ms
D/dalvikvm( 2700): WAIT_FOR_CONCURRENT_GC blocked 7ms
I/dalvikvm-heap( 2700): Grow heap (frag case) to 17.609MB for 39954-byte allocation
W/Quickoffice( 2737): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2737): Loading recent documents list
D/Quickoffice( 2737): The number of lines present in  /proc/mount 21
D/Quickoffice( 2737): Parsing the storagedefinition.xml.
D/dalvikvm( 2700): GC_FOR_ALLOC freed <1K, 4% free 18004K/18576K, paused 22ms, total 22ms
D/Quickoffice( 2737): # of Storagedefinitions - 35
D/Quickoffice( 2737): The # of storage definitions available - 35
D/Quickoffice( 2737): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2737): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2737): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2737): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2737): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2737): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2737): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2737): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2737): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2737): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2737): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2737): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2737): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2737): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2737): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2737): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2737): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2737): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2737): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2737): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2737): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2737): Build properties are not configured for this storage definition.
D/Quickoffice( 2737): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2737): The # of mounts identified -  1
I/ActivityManager(  771): Killing 2373:com.android.chrome/u0a31 (adj 15): empty #17
D/dalvikvm( 2700): GC_FOR_ALLOC freed <1K, 4% free 18004K/18576K, paused 21ms, total 22ms
I/dalvikvm-heap( 2700): Grow heap (frag case) to 17.684MB for 79892-byte allocation
D/dalvikvm( 2737): GC_CONCURRENT freed 216K, 2% free 16958K/17204K, paused 2ms+6ms, total 20ms
D/com.google.android.apps.docs.quickoffice.X( 2737): Checking validity of 0 items
D/ContentResolverUtil( 2737): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2737): 0 items were valid
D/dalvikvm( 2700): GC_FOR_ALLOC freed 0K, 4% free 18082K/18656K, paused 12ms, total 12ms
W/ActivityManager(  771): No permission grants found for com.quickoffice.android
W/Quickoffice( 2737): Could not load clipboard.
W/Quickoffice( 2737): Could not store clipboard.
I/ProviderInstaller( 2700): Installed default security provider GmsCore_OpenSSL
I/Icing   ( 1327): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm( 1215): GC_CONCURRENT freed 408K, 3% free 18245K/18724K, paused 3ms+2ms, total 23ms
I/Icing   ( 1327): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1327): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
I/Icing   ( 1327): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/AndroidRuntime( 2761): 
D/AndroidRuntime( 2761): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2761): CheckJNI is OFF
D/dalvikvm( 2761): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2761): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2761): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2761): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2761): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2761): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2761): Calling main entry com.android.commands.am.Am
I/ActivityManager(  771): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2761
D/PermissionCache(  180): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (108 us)
D/AndroidRuntime( 2761): Shutting down VM
D/dalvikvm( 2761): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  771): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2773 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1215): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1215): mic_close
I/ActivityManager(  771): Killing 2411:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
I/ActivityManager(  771): Killing 1174:com.google.android.keep/u0a52 (adj 15): empty #18
I/MicroHotwordRecognitionRunner( 1215): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1215): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2773): Binding Chromium to main looper Looper (main, tid 1) {428b8758}
I/LibraryLoader( 2773): Expected native library version number "",actual native library version number ""
I/chromium( 2773): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2773): Initializing chromium process, renderers=0
D/BluetoothManagerService(  771): Message: 20
D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4452eae8:true
I/Adreno-EGL( 2773): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,W/chromium( 2773): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 2773): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2773): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2773): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2773): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 2773): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2773): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2773): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2773): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 2773): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 2773): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2773): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2773): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 2773): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2773): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2773): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2773): Enabling debug mode 0
,W/AwContents( 2773): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  771): Displayed com.test.thalitest/.MainActivity: +332ms
,D/JsMessageQueue( 2773): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2773): GC_CONCURRENT freed 263K, 2% free 16889K/17184K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 2773): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428bca70
,D/dalvikvm( 2773): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x428bca70
,D/jxcore_app_log( 2773): JniHelper::setJavaVM(0x41853ed0), pthread_self() = 1982489296
,D/JX-Cordova( 2773): jxcore cordova android initializing
,D/dalvikvm( 2773): GC_CONCURRENT freed 208K, 2% free 17193K/17432K, paused 1ms+1ms, total 10ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 157K, 2% free 17538K/17736K, paused 0ms+2ms, total 11ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 154K, 2% free 17882K/18080K, paused 2ms+2ms, total 14ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 152K, 2% free 18225K/18424K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 157K, 2% free 18562K/18768K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 179K, 2% free 18982K/19216K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 221K, 2% free 19494K/19776K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 280K, 2% free 20113K/20460K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 328K, 2% free 20881K/21284K, paused 1ms+3ms, total 30ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 403K, 3% free 21821K/22308K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 1212K, 6% free 22278K/23560K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 1470K, 7% free 22553K/24172K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 84K, 7% free 22540K/24172K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2773): Grow heap (frag case) to 22.748MB for 744140-byte allocation
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 486K, 9% free 22780K/24900K, paused 32ms, total 32ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 832K, 9% free 22784K/24900K, paused 20ms, total 21ms
,I/dalvikvm-heap( 2773): Grow heap (frag case) to 23.340MB for 1116206-byte allocation
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 13K, 9% free 23860K/25992K, paused 20ms, total 20ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 1977K, 11% free 23199K/25992K, paused 20ms, total 22ms
,I/dalvikvm-heap( 2773): Grow heap (frag case) to 24.279MB for 1674304-byte allocation
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 11K, 11% free 24823K/27628K, paused 20ms, total 20ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 3089K, 14% free 23845K/27628K, paused 23ms, total 27ms
,I/dalvikvm-heap( 2773): Grow heap (frag case) to 25.708MB for 2511452-byte allocation
,D/dalvikvm( 2773): GC_CONCURRENT freed 1695K, 19% free 24602K/30084K, paused 4ms+1ms, total 24ms
D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 2517K, 18% free 24722K/30084K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 774K, 19% free 24498K/30084K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2773): Grow heap (frag case) to 27.542MB for 3767174-byte allocation
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 2454K, 24% free 25722K/33764K, paused 22ms, total 22ms
,D/dalvikvm( 2773): GC_CONCURRENT freed 151K, 24% free 25742K/33764K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 2773): GC_FOR_ALLOC freed 546K, 24% free 25723K/33764K, paused 19ms, total 19ms
,W/jxcore-log( 2773): Initializing JXcore engine
,W/jxcore-log( 2773): JXcore engine is ready
,D/dalvikvm( 2773): GC_CONCURRENT freed 5403K, 31% free 23320K/33764K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 2773): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/jxcore-log( 2773): Starting JXcore engine
,W/jxcore-log( 2773): Platform android
W/jxcore-log( 2773): 
,W/jxcore-log( 2773): Process ARCH arm
W/jxcore-log( 2773): 
,I/jxcore-log( 2773): JXcore Cordova bridge is ready!
I/jxcore-log( 2773): 
,W/jxcore-log( 2773): JXcore engine is started
,I/chromium( 2773): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2773): Toggling radios to true
I/jxcore-log( 2773): 
,D/BluetoothAdapter( 2773): enable(): BT is already enabled..!
,D/WifiService(  771): setWifiEnabled: true pid=2773, uid=10108
I/jxcore-log( 2773): Radios toggled
I/jxcore-log( 2773): 
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x5db00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x79004348: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x79004348: I/O error during system call, Broken pipe,
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/dalvikvm(  995): GC_CONCURRENT freed 334K, 3% free 17065K/17428K, paused 2ms+4ms, total 15ms
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2773): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): my name is : LGE-Nexus 5_PT8445
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): attempting to connect to test coordinator
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): check test folder
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): found test : ./testFindPeers.js
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): found test : ./testReConnect.js
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): found test : ./testSendData.js
I/jxcore-log( 2773): 
,E/WifiStateMachine(  771): scanCount==0 - aborting
,I/jxcore-log( 2773): Test app app.js loaded
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/Choreographer( 2773): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2773): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/MusicLifecycle( 2181): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@428aca38 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2181): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/ActivityManager(  771): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2896 uid=10031 gids={50031, 3003, 1028, 1015}
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2896): VFY: unable to resolve instance field 68
,D/dalvikvm( 2896): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2896): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2896): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2896): VFY: unable to resolve instance field 68
,D/dalvikvm( 2896): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2896): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2896): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2896): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2896): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  771): Killing 2181:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  771): Service ServiceRecord{4302bc50 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42e93518 2181:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{42e25740 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42e93518 2181:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{42e1b820 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42e93518 2181:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{42dbf858 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42e93518 2181:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{42d6d5b0 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42e93518 2181:com.google.android.music:main/u0a58} not same as in map: null
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/dalvikvm( 1126): GC_CONCURRENT freed 371K, 4% free 17920K/18604K, paused 5ms+2ms, total 28ms
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/dalvikvm( 1327): GC_CONCURRENT freed 653K, 4% free 19090K/19780K, paused 2ms+3ms, total 50ms
,D/SystemUpdateService( 1327): onDestroy
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/jxcore-log( 2773): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 2773): 
,D/dalvikvm( 1215): GC_FOR_ALLOC freed 824K, 6% free 17720K/18724K, paused 10ms, total 10ms
,D/dalvikvm(  771): GC_EXPLICIT freed 23574K, 53% free 26252K/55668K, paused 2ms+5ms, total 92ms
,D/dalvikvm( 1215): GC_CONCURRENT freed 274K, 5% free 17835K/18724K, paused 1ms+1ms, total 11ms
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,D/dalvikvm( 2466): GC_CONCURRENT freed 1171K, 6% free 19621K/20824K, paused 10ms+3ms, total 41ms
,D/Finsky  ( 2466): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 1126): GC_CONCURRENT freed 405K, 4% free 17948K/18604K, paused 2ms+2ms, total 26ms
,I/VacuumService(  975): Vacuum at: now=1450106345843 tag=VacuumService
,D/dalvikvm( 1126): GC_CONCURRENT freed 416K, 4% free 17967K/18604K, paused 2ms+2ms, total 25ms
,I/PhenotypeConfigurator(  975): Scheduling Phenotype for one-off execution 10795 seconds from now (1450106346077)
,D/GetConfigurationSnapshotOperation(  975): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  975): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  975): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  975): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  975): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  975): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  975): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  975): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  975): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  975): GC_CONCURRENT freed 574K, 4% free 18739K/19408K, paused 2ms+2ms, total 25ms
,I/dalvikvm(  975): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm(  975): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  975): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  975): GC_CONCURRENT freed 457K, 4% free 18881K/19488K, paused 4ms+2ms, total 24ms
,D/dalvikvm(  975): GC_CONCURRENT freed 539K, 4% free 18995K/19628K, paused 3ms+3ms, total 20ms
,D/dalvikvm(  975): GC_CONCURRENT freed 569K, 4% free 19121K/19784K, paused 2ms+4ms, total 21ms
,D/dalvikvm(  975): GC_CONCURRENT freed 760K, 5% free 19149K/20004K, paused 2ms+4ms, total 23ms
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/rmt_storage(  176): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8ce7160
I/rmt_storage(  176): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  176): wakelock acquired: 1, error no: 2
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1194429920)
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1194429920) wakelock released: 1, error no: 0
I/rmt_storage(  176): 
,I/rmt_storage(  176): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8ce7160
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/PowerManagerService(  771): Going to sleep due to screen timeout...
,I/Adreno-EGL(  771): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  180): Screen released, type=0 flinger=0xb6fd2450
,D/qdhwcomposer(  180): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  180): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  771): Excessive delay in blankDisplay() while turning screen off: 289ms
,V/KeyguardServiceDelegate(  771): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42fd5090)
,V/KeyguardServiceDelegate(  771): **** SHOWN CALLED ****
I/WindowManager(  771): No lock screen! windowToken=null
,D/dalvikvm(  975): GC_CONCURRENT freed 811K, 6% free 19055K/20080K, paused 1ms+3ms, total 53ms
,D/NfcService( 1017): NFC-C OFF
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector connect called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): Coordinator is now connected to the server!
I/jxcore-log( 2773): 
,I/chromium( 2773): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2773): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): DBG, CoordinatorConnector command called
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93
,I/jxcore-log( 2773): Start now : testSendData.js
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): check server
I/jxcore-log( 2773): 
,I/jxcore-log( 2773): serverPort is 52698
I/jxcore-log( 2773): 
,I/dalvikvm( 2773): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 2773): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x0019
I/dalvikvm( 2773): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 2773): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2773): VFY: replacing opcode 0x6e at 0x0020
,I/jxcore-log( 2773): 2015-12-14T15:24:08.408Z SendDataTCPServer.js: TCP/IP server is bound to port: 52698
I/jxcore-log( 2773): 
D/AndroidRuntime( 2773): Shutting down VM
,W/dalvikvm( 2773): threadid=1: thread exiting with uncaught exception (group=0x41865ba8)
E/AndroidRuntime( 2773): FATAL EXCEPTION: main
E/AndroidRuntime( 2773): Process: com.test.thalitest, PID: 2773
E/AndroidRuntime( 2773): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 2773): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 2773): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 2773): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 2773): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 2773): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 2773): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 2773): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 2773): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 2773): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 2773): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 2773): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 2773): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2773): 	at android.app.ActivityThread.main(ActivityThread.java:5001)
E/AndroidRuntime( 2773): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2773): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2773): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  771):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  771): Killing 1808:com.google.android.gm/u0a41 (adj 15): empty #17
,I/Process ( 2773): Sending signal. PID: 2773 SIG: 9
,I/ActivityManager(  771): Process com.test.thalitest (pid 2773) has died.
,I/WindowState(  771): WIN DEATH: Window{44d63520 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x7e100001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x78ff76b8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78ff76b8: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1233): GC_CONCURRENT freed 327K, 3% free 16765K/17132K, paused 22ms+1ms, total 38ms
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1327): active receiver: enabled
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1327): num queued entries: 0
I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1126): GC_CONCURRENT freed 480K, 4% free 17927K/18604K, paused 7ms+1ms, total 57ms
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 230f
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 230f
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1540): GC_CONCURRENT freed 336K, 3% free 16898K/17264K, paused 8ms+1ms, total 50ms
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/BluetoothManagerService(  771): Message: 20
,D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e2b8b8:true
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab95c rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab5e4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 230f
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1540): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab5e4 rs_disc_pending=2
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:3c:51]: 7, f, 230f
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab5e4 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab5e4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:3c:51]: 7, f, 230f
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x9c800001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x79058910: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x79058910: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1327): num updated entries: 0
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
,I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm(  771): GC_CONCURRENT freed 2300K, 53% free 26246K/55668K, paused 5ms+3ms, total 61ms
,I/dalvikvm(  771): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 1995): GC_CONCURRENT freed 1402K, 6% free 22822K/24264K, paused 8ms+2ms, total 58ms
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0xbb500001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x78c5ab60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78c5ab60: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/SocketClient(  177): write error (Broken pipe)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
,I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm( 1126): GC_CONCURRENT freed 412K, 4% free 17909K/18604K, paused 9ms+6ms, total 81ms
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0xd8a00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x79058910: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x79058910: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
W/SocketClient(  177): write error (Broken pipe)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/dalvikvm( 1327): GC_CONCURRENT freed 679K, 4% free 19134K/19844K, paused 2ms+3ms, total 45ms
,D/SystemUpdateService( 1327): onDestroy
,W/ProcessCpuTracker(  771): Skipping unknown process pid 3486
,W/ProcessCpuTracker(  771): Skipping unknown process pid 3489
,W/ProcessCpuTracker(  771): Skipping unknown process pid 3490
,W/ProcessCpuTracker(  771): Skipping unknown process pid 3493
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1540): GC_CONCURRENT freed 422K, 3% free 16876K/17328K, paused 15ms+0ms, total 49ms
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/dalvikvm( 1215): GC_CONCURRENT freed 493K, 5% free 17841K/18724K, paused 2ms+1ms, total 17ms
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751abe90 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab26c rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751aaef4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 0, 0, 0
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751aaef4 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751aaef4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751abe90 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751abe90 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
,I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751aaef4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,D/dalvikvm( 1540): GC_CONCURRENT freed 394K, 3% free 16877K/17316K, paused 15ms+8ms, total 75ms
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab26c rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751abe90 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751abe90 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab26c rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751aaef4 rs_disc_pending=0
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0xf8100001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1126): Read error: ssl=0x78c5ab60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78c5ab60: I/O error during system call, Broken pipe
D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1327): num queued entries: 0
I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm(  771): GC_CONCURRENT freed 2270K, 53% free 26243K/55656K, paused 2ms+7ms, total 79ms
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm(  948): GC_EXPLICIT freed 344K, 3% free 17050K/17420K, paused 1ms+5ms, total 54ms
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1126): GC_CONCURRENT freed 391K, 4% free 17904K/18604K, paused 3ms+3ms, total 27ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x16200001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x79058910: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x79058910: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/ConnectivityService(  771): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  771): Done.
,D/ConnectivityService(  771): Setting timer for 720seconds
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1327): num queued entries: 0
,D/dalvikvm( 2896): GC_CONCURRENT freed 285K, 2% free 16800K/17116K, paused 1ms+1ms, total 18ms
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1327): NEXT; no task
I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
,I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/dalvikvm( 1215): GC_CONCURRENT freed 512K, 5% free 17840K/18724K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 1215): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,D/dalvikvm( 1540): GC_CONCURRENT freed 395K, 3% free 16877K/17304K, paused 11ms+0ms, total 56ms
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x57e00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x78c5ab60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78c5ab60: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/iu.UploadsManager( 1327): num updated entries: 0
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/iu.UploadsManager( 1327): num updated entries: 0
I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1126): GC_CONCURRENT freed 413K, 4% free 17908K/18604K, paused 8ms+1ms, total 32ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=9 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/dalvikvm(  771): GC_CONCURRENT freed 2375K, 53% free 26251K/55656K, paused 25ms+3ms, total 95ms
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x75000001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1126): Read error: ssl=0x79058910: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x79058910: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm( 1327): GC_CONCURRENT freed 724K, 4% free 19127K/19884K, paused 7ms+2ms, total 27ms
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ac3c4 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 1540): GC_CONCURRENT freed 389K, 3% free 16877K/17296K, paused 7ms+6ms, total 53ms
,W/bt-btif ( 1540): info:x10,
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ab95c rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ac580 rs_disc_pending=1
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x753a3af8 clazz=0x92600001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1126): Read error: ssl=0x78c5ab60: I/O error during system call, Connection timed out
,V/NativeCrypto( 1126): SSL shutdown failed: ssl=0x78c5ab60: I/O error during system call, Broken pipe
D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  941): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  941): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  941): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  941): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 1995): connection state changed from CONNECTED to DISCONNECTED
I/iu.UploadsManager( 1327): num queued entries: 0
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
I/iu.UploadsManager( 1327): num updated entries: 0
I/SystemUpdateService( 1327): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1327): file has been verified
I/SystemUpdateService( 1327): OTA package size = 2571501
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/dalvikvm( 1008): GC_CONCURRENT freed 334K, 3% free 16745K/17108K, paused 2ms+0ms, total 19ms
E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42df5bc0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1327): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1327): onCreate
,D/SystemUpdateService( 1327): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1327): active receiver: enabled
,I/iu.Environment( 1327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1327): num queued entries: 0
,I/iu.UploadsManager( 1327): num updated entries: 0
,I/iu.SyncManager( 1327): NEXT; no task
,I/SystemUpdateService( 1327): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1327): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1327): now status is 0 (complete)
I/SystemUpdateService( 1327): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1327): file has been verified
,I/SystemUpdateService( 1327): OTA package size = 2571501
,I/SystemUpdateService( 1327): showing system update notification
,D/SystemUpdateService( 1327): onDestroy
,D/dalvikvm( 2327): GC_CONCURRENT freed 265K, 2% free 17709K/17960K, paused 2ms+3ms, total 26ms
,I/Babel   ( 1995): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm(  975): GC_FOR_ALLOC freed 738K, 6% free 18913K/20076K, paused 16ms, total 17ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=11 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ac580 rs_disc_pending=1
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 0
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,I/EventLogService( 1327): Aggregate from 1450105726445 (log), 1450105726445 (data)
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,W/bt-btm  ( 1540): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 1540): tBTM_SEC_DEV:0x751ac580 rs_disc_pending=2
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1540): bta_dm_check_av:0
,W/bt-btif ( 1540): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,D/dalvikvm( 1540): GC_CONCURRENT freed 402K, 3% free 16876K/17312K, paused 14ms+1ms, total 58ms
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: Note3-1
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1215): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1215): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,D/BluetoothAdapterService(1116474112)( 1540): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1540): getBondedDevices: length=7
,W/bt-l2cap( 1540): l2cu_get_conn_role 1
,W/bt-btif ( 1540): info:x10
,D/        ( 1540): remote version info [7c:f9:0e:37:96:ab]: 6, 10f, 608
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 1540): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1540): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 1540): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  771): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  771): Done.
,D/ConnectivityService(  771): Setting timer for 720seconds
,D/dalvikvm(  771): GC_CONCURRENT freed 2202K, 53% free 26383K/55656K, paused 3ms+3ms, total 55ms
,I/ProcessStatsService(  771): Prepared write state in 43ms
,I/ProcessStatsService(  771): Pruning old procstats: /data/system/procstats/state-2015-12-13-18-08-00.bin
,I/ActivityManager(  771): Killing 2664:com.android.musicfx/u0a13 (adj 15): empty for 1810s
,I/ActivityManager(  771): Killing 2643:com.google.android.partnersetup/u0a11 (adj 15): empty for 1810s
,I/ActivityManager(  771): Killing 2353:android.process.acore/u0a3 (adj 15): empty for 1810s
,I/ActivityManager(  771): Killing 2628:com.android.defcontainer/u0a4 (adj 15): empty for 1810s
,I/ActivityManager(  771): Killing 2265:com.android.providers.calendar/u0a1 (adj 15): empty for 1829s
,I/ActivityManager(  771): Killing 1741:com.google.android.calendar/u0a28 (adj 15): empty for 1849s
,TIME-OUT KILL (timeout was 1800000ms)
```
