#### Test 83084099807e426_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
08-31 16:53:51.586   754  1298 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:53:51.596   754  1298 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-31 16:53:51.596   754  1298 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-31 16:53:51.606   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 16:53:51.616   754   754 I MotionRecognitionService: Plugged
08-31 16:53:51.616   754   754 D MotionRecognitionService:   cableConnection= 1
08-31 16:53:51.616   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-31 16:53:51.626   754   754 D MotionRecognitionService: skip setTransmitPower. 
08-31 16:53:51.626   754  1298 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
08-31 16:53:51.626   754  1298 D BatteryService: stay LED for fully charged
--------- beginning of main
08-31 16:53:51.646  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:53:51.646  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:53:51.646  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 16:53:51.686  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:53:51.686  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:53:51.686  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:53:51.716   754  3296 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 300, LCD = 0
08-31 16:53:52.516  2062  2062 E audit   : type=1400 msg=audit(1472655232.516:278): avc:  denied  { execmod } for  pid=6429 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:53:52.516  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 16:53:52.516  2062  2062 E audit   : type=1300 msg=audit(1472655232.516:278): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4020000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=6429 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:53:52.526  2062  2062 E audit   : type=1327 msg=audit(1472655232.516:278): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 16:53:52.526  2062  2062 E audit   : type=1320 msg=audit(1472655232.516:278): 
08-31 16:53:52.576  2062  2062 E audit   : type=1400 msg=audit(1472655232.576:279): avc:  denied  { execmod } for  pid=6429 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:53:52.576  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 16:53:52.586  2062  2062 E audit   : type=1300 msg=audit(1472655232.576:279): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe0000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=6429 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:53:52.586  2062  2062 E audit   : type=1327 msg=audit(1472655232.576:279): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 16:53:52.586  2062  2062 E audit   : type=1320 msg=audit(1472655232.576:279): 
08-31 16:53:52.626  2062  2062 E audit   : type=1400 msg=audit(1472655232.626:280): avc:  denied  { execmod } for  pid=6429 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:53:52.626  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-31 16:53:52.626  2062  2062 E audit   : type=1300 msg=audit(1472655232.626:280): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe0000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=6429 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:53:52.626  2062  2062 E audit   : type=1327 msg=audit(1472655232.626:280): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-31 16:53:52.636  2062  2062 E audit   : type=1320 msg=audit(1472655232.626:280): 
08-31 16:53:52.636  6429  6429 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 16:53:52.636  6429  6429 D AndroidRuntime: CheckJNI is OFF
08-31 16:53:52.636  6429  6429 D AndroidRuntime: readGMSProperty: start
08-31 16:53:52.636  6429  6429 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:53:52.636  6429  6429 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:53:52.636  6429  6429 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:53:52.636  6429  6429 D AndroidRuntime: readGMSProperty: end
08-31 16:53:52.636  6429  6429 D AndroidRuntime: addProductProperty: start
08-31 16:53:52.646  6429  6429 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 16:53:52.646  6429  6429 W art     : af18e000-b20b4000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:53:52.646  6429  6429 W art     : b20b4000-b4323000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:53:52.646  6429  6429 W art     : b4323000-b4324000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:53:52.646  6429  6429 W art     : b4324000-b4772000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-31 16:53:52.646  6429  6429 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b4773000-b477d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-31 16:53:52.646  6429  6429 W art     : b477d000-b477e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-31 16:53:52.646  6429  6429 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-31 16:53:52.646  6429  6429 W art     : b4885000-b48ae000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 16:53:52.646  6429  6429 W art     : b48ae000-b48b1000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:53:52.646  6429  6429 W art     : b48b1000-b48b2000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:53:52.646  6429  6429 W art     : b48b2000-b48b3000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:53:52.646  6429  6429 W art     : b48b3000-b48b4000 r--p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b48b4000-b48d4000 r--s 00000000 00:0b 6700       /dev/__properties__
08-31 16:53:52.646  6429  6429 W art     : b48d4000-b52e5000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-31 16:53:52.646  6429  6429 W art     : b52e5000-b52e6000 ---p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b52e6000-b532f000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-31 16:53:52.646  6429  6429 W art     : b532f000-b5330000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-31 16:53:52.646  6429  6429 W art     : b5330000-b5338000 rw-p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b5338000-b536d000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:53:52.646  6429  6429 W art     : b536d000-b536e000 ---p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b536e000-b536f000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:53:52.646  6429  6429 W art     : b536f000-b5370000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:53:52.646  6429  6429 W art     : b5370000-b53c8000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-31 16:53:52.646  6429  6429 W art     : b53c8000-b53c9000 ---p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b53c9000-b53ca000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-31 16:53:52.646  6429  6429 W art     : b53ca000-b53cb000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-31 16:53:52.646  6429  6429 W art     : b53cc000-b53d2000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:53:52.646  6429  6429 W art     : b53d2000-b53d3000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:53:52.646  6429  6429 W art     : b53d3000-b53d4000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:53:52.646  6429  6429 W art     : b53d4000-b53d6000 rw-p 00000000 00:00 0 
08-31 16:53:52.646  6429  6429 W art     : b53d7000-b53e1000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 16:53:52.646  6429  6429 W art     : b53e1000-b53e4000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 16:53:52.656  6429  6429 W art     : b53e4000-b53e5000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 16:53:52.656  6429  6429 W art     : b53e6000-b53fd000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:53:52.656  6429  6429 W art     : b53fd000-b53fe000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b53fe000-b53ff000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:53:52.656  6429  6429 W art     : b53ff000-b5400000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:53:52.656  6429  6429 W art     : b5401000-b540b000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:53:52.656  6429  6429 W art     : b540b000-b540c000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:53:52.656  6429  6429 W art     : b540c000-b540d000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:53:52.656  6429  6429 W art     : b540d000-b5411000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:53:52.656  6429  6429 W art     : b5411000-b5412000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:53:52.656  6429  6429 W art     : b5412000-b5413000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:53:52.656  6429  6429 W art     : b5413000-b5429000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-31 16:53:52.656  6429  6429 W art     : b5429000-b542a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-31 16:53:52.656  6429  6429 W art     : b542a000-b542b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-31 16:53:52.656  6429  6429 W art     : b542b000-b5438000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:53:52.656  6429  6429 W art     : b5438000-b5439000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:53:52.656  6429  6429 W art     : b5439000-b543a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:53:52.656  6429  6429 W art     : b543a000-b549a000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-31 16:53:52.656  6429  6429 W art     : b549a000-b549d000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-31 16:53:52.656  6429  6429 W art     : b549d000-b54a1000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b54a1000-b5502000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-31 16:53:52.656  6429  6429 W art     : b5502000-b5503000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-31 16:53:52.656  6429  6429 W art     : b5503000-b5552000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:53:52.656  6429  6429 W art     : b5552000-b5554000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:53:52.656  6429  6429 W art     : b5554000-b5555000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:53:52.656  6429  6429 W art     : b5555000-b5556000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5556000-b555d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 16:53:52.656  6429  6429 W art     : b555d000-b555e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 16:53:52.656  6429  6429 W art     : b555e000-b555f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-31 16:53:52.656  6429  6429 W art     : avc_common.so
08-31 16:53:52.656  6429  6429 W art     : b5560000-b5563000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 16:53:52.656  6429  6429 W art     : b5563000-b5564000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 16:53:52.656  6429  6429 W art     : b5564000-b5565000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-31 16:53:52.656  6429  6429 W art     : enc_common.so
08-31 16:53:52.656  6429  6429 W art     : b5566000-b556a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-31 16:53:52.656  6429  6429 W art     : b556a000-b556b000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b556b000-b556c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-31 16:53:52.656  6429  6429 W art     : b556c000-b556d000 rw-p 00005000 b3:17 2510       /syste
08-31 16:53:52.656  6429  6429 W art     : m/lib/libpowermanager.so
08-31 16:53:52.656  6429  6429 W art     : b556e000-b558b000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:53:52.656  6429  6429 W art     : b558b000-b558c000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:53:52.656  6429  6429 W art     : b558c000-b558d000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:53:52.656  6429  6429 W art     : b558e000-b5593000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:53:52.656  6429  6429 W art     : b5593000-b5594000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:53:52.656  6429  6429 W art     : b5594000-b5595000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:53:52.656  6429  6429 W art     : b5596000-b55c7000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:53:52.656  6429  6429 W art     : b55c7000-b55c8000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b55c8000-b55cb000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:53:52.656  6429  6429 W art     : b55cb000-b55cc000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:53:52.656  6429  6429 W art     : b55cd000-b5608000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-31 16:53:52.656  6429  6429 W art     : b5608000-b5609000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-31 16:53:52.656  6429  6429 W art     : b5609000-b560a000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-31 16:53:52.656  6429  6429 W art     : b560b000-b5612000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:53:52.656  6429  6429 W art     : b5612000-b5613000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5613000-b5614000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:53:52.656  6429  6429 W art     : b5614000-b5615000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:53:52.656  6429  6429 W art     : b5615000-b5616000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5616000-b562d000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:53:52.656  6429  6429 W art     : b562d000-b562e000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b562e000-b5631000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:53:52.656  6429  6429 W art     : b5631000-b5632000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:53:52.656  6429  6429 W art     : b5632000-b5651000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-31 16:53:52.656  6429  6429 W art     : b5651000-b5652000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-31 16:53:52.656  6429  6429 W art     : b5652000-b5653000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-31 16:53:52.656  6429  6429 W art     : b5653000-b5691000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-31 16:53:52.656  6429  6429 W art     : b5691000-b5692000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5692000-b5694000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-31 16:53:52.656  6429  6429 W art     : b5694000-b5695000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-31 16:53:52.656  6429  6429 W art     : b5696000-b569d000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:53:52.656  6429  6429 W art     : b569d000-b569e000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:53:52.656  6429  6429 W art     : b569e000-b569f000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:53:52.656  6429  6429 W art     : b56a0000-b56a3000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:53:52.656  6429  6429 W art     : b56a3000-b56a4000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:53:52.656  6429  6429 W art     : b56a4000-b56a5000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:53:52.656  6429  6429 W art     : b56a5000-b56ab000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b56ab000-b56ac000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b56ac000-b56ad000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b56ad000-b56ae000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b56ae000-b56b7000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:53:52.656  6429  6429 W art     : b56b7000-b56b8000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:53:52.656  6429  6429 W art     : b56b8000-b56b9000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:53:52.656  6429  6429 W art     : b56b9000-b574a000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:53:52.656  6429  6429 W art     : b574a000-b574b000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b574b000-b5756000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:53:52.656  6429  6429 W art     : b5756000-b5757000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:53:52.656  6429  6429 W art     : b5758000-b576a000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-31 16:53:52.656  6429  6429 W art     : b576a000-b576b000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-31 16:53:52.656  6429  6429 W art     : b576b000-b576c000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-31 16:53:52.656  6429  6429 W art     : b576d000-b5772000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:53:52.656  6429  6429 W art     : b5772000-b5773000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:53:52.656  6429  6429 W art     : b5773000-b5774000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:53:52.656  6429  6429 W art     : b5775000-b57e2000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:53:52.656  6429  6429 W art     : b57e2000-b57e3000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b57e3000-b57e5000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:53:52.656  6429  6429 W art     : b57e5000-b57e6000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:53:52.656  6429  6429 W art     : b57e6000-b57e7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b57e7000-b57ee000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:53:52.656  6429  6429 W art     : b57ee000-b57ef000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:53:52.656  6429  6429 W art     : b57ef000-b57f0000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:53:52.656  6429  6429 W art     : b57f1000-b5871000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:53:52.656  6429  6429 W art     : b5871000-b5872000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5872000-b5873000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:53:52.656  6429  6429 W art     : b5873000-b5874000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:53:52.656  6429  6429 W art     : b5874000-b588b000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b588b000-b58c2000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:53:52.656  6429  6429 W art     : b58c2000-b58c3000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:53:52.656  6429  6429 W art     : b58c3000-b58c4000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:53:52.656  6429  6429 W art     : b58c4000-b58e0000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:53:52.656  6429  6429 W art     : b58e0000-b58e1000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:53:52.656  6429  6429 W art     : b58e1000-b58e2000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:53:52.656  6429  6429 W art     : b58e3000-b5944000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-31 16:53:52.656  6429  6429 W art     : b5944000-b5946000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-31 16:53:52.656  6429  6429 W art     : b5946000-b5947000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-31 16:53:52.656  6429  6429 W art     : b5948000-b596d000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-31 16:53:52.656  6429  6429 W art     : b596d000-b596e000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-31 16:53:52.656  6429  6429 W art     : b596e000-b596f000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-31 16:53:52.656  6429  6429 W art     : b5970000-b5978000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:53:52.656  6429  6429 W art     : b5978000-b597a000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:53:52.656  6429  6429 W art     : b597a000-b597b000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:53:52.656  6429  6429 W art     : b597c000-b597f000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-31 16:53:52.656  6429  6429 W art     : b597f000-b5980000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-31 16:53:52.656  6429  6429 W art     : b5980000-b5981000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-31 16:53:52.656  6429  6429 W art     : b5981000-b5985000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:53:52.656  6429  6429 W art     : b5985000-b5986000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5986000-b5987000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:53:52.656  6429  6429 W art     : b5987000-b5988000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:53:52.656  6429  6429 W art     : b5988000-b5998000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-31 16:53:52.656  6429  6429 W art     : b5998000-b5999000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-31 16:53:52.656  6429  6429 W art     : b5999000-b599a000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-31 16:53:52.656  6429  6429 W art     : b599a000-b59e0000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b59e0000-b59e9000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-31 16:53:52.656  6429  6429 W art     : b59e9000-b59ea000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-31 16:53:52.656  6429  6429 W art     : b59ea000-b59eb000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-31 16:53:52.656  6429  6429 W art     : b59ec000-b59f1000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-31 16:53:52.656  6429  6429 W art     : b59f1000-b59f2000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-31 16:53:52.656  6429  6429 W art     : b59f2000-b59f3000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-31 16:53:52.656  6429  6429 W art     : b59f3000-b59f6000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:53:52.656  6429  6429 W art     : b59f6000-b59f7000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b59f7000-b59f8000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:53:52.656  6429  6429 W art     : b59f8000-b59f9000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:53:52.656  6429  6429 W art     : b59f9000-b59fa000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-31 16:53:52.656  6429  6429 W art     : or]
08-31 16:53:52.656  6429  6429 W art     : b59fa000-b5a12000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 16:53:52.656  6429  6429 W art     : b5a12000-b5a13000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5a13000-b5a14000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 16:53:52.656  6429  6429 W art     : b5a14000-b5a15000 rw-p 00019000 b3:
08-31 16:53:52.656  6429  6429 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-31 16:53:52.656  6429  6429 W art     : b5a16000-b5bb0000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-31 16:53:52.656  6429  6429 W art     : b5bb0000-b5bb1000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5bb1000-b5bbe000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-31 16:53:52.656  6429  6429 W art     : b5bbe000-b5bbf000 rw-p 001a7000 b3:17 604        /system/
08-31 16:53:52.656  6429  6429 W art     : lib/libstagefright.so
08-31 16:53:52.656  6429  6429 W art     : b5bbf000-b5bc3000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-31 16:53:52.656  6429  6429 W art     : b5bc3000-b5bc4000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5bc4000-b5bc5000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-31 16:53:52.656  6429  6429 W art     : b5bc5000-b5bc6000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-31 16:53:52.656  6429  6429 W art     : ersona.so
08-31 16:53:52.656  6429  6429 W art     : b5bc6000-b5bd9000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:53:52.656  6429  6429 W art     : b5bd9000-b5bda000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:53:52.656  6429  6429 W art     : b5bda000-b5bdb000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:53:52.656  6429  6429 W art     : b5bdc000-b5c27000 r
08-31 16:53:52.656  6429  6429 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:53:52.656  6429  6429 W art     : b5c27000-b5c28000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:53:52.656  6429  6429 W art     : b5c28000-b5c29000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:53:52.656  6429  6429 W art     : b5c29000-b5c2b000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5c2b000-b5c2c000 r--p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5c2c000-b5c3d000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:53:52.656  6429  6429 W art     : b5c3d000-b5c3e000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5c3e000-b5c3f000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:53:52.656  6429  6429 W art     : b5c3f000-b5c40000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:53:52.656  6429  6429 W art     : b5c40000-b5c41000 r--p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5c41000-b5c4b000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:53:52.656  6429  6429 W art     : b5c4b000-b5c4d000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:53:52.656  6429  6429 W art     : b5c4d000-b5c4e000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:53:52.656  6429  6429 W art     : b5c4e000-b5c67000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:53:52.656  6429  6429 W art     : b5c67000-b5c68000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:53:52.656  6429  6429 W art     : b5c68000-b5c6b000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:53:52.656  6429  6429 W art     : b5c6b000-b5c6f000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5c6f000-b5ce3000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-31 16:53:52.656  6429  6429 W art     : b5ce3000-b5ce4000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5ce4000-b5ce7000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-31 16:53:52.656  6429  6429 W art     : b5ce7000-b5ce8000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-31 16:53:52.656  6429  6429 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5ce9000-b5cec000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:53:52.656  6429  6429 W art     : b5cec000-b5ced000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:53:52.656  6429  6429 W art     : b5ced000-b5cee000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:53:52.656  6429  6429 W art     : b5cee000-b5cef000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5cef000-b5cf4000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:53:52.656  6429  6429 W art     : b5cf4000-b5cf5000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:53:52.656  6429  6429 W art     : b5cf5000-b5cf6000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:53:52.656  6429  6429 W art     : b5cf6000-b5cf7000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5cf7000-b5cfa000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b5cfa000-b5cfb000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b5cfb000-b5cfc000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b5cfc000-b5cfd000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:53:52.656  6429  6429 W art     : b5cfd000-b5d01000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:53:52.656  6429  6429 W art     : b5d01000-b5d02000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:53:52.656  6429  6429 W art     : b5d02000-b5d03000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:53:52.656  6429  6429 W art     : b5d03000-b5d04000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5d04000-b5d08000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:53:52.656  6429  6429 W art     : b5d08000-b5d09000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:53:52.656  6429  6429 W art     : b5d09000-b5d0a000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:53:52.656  6429  6429 W art     : b5d0a000-b5d0b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5d0b000-b5d19000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-31 16:53:52.656  6429  6429 W art     : b5d19000-b5d1a000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b5d1a000-b5d1b000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-31 16:53:52.656  6429  6429 W art     : b5d1b000-b5d1c000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-31 16:53:52.656  6429  6429 W art     : b5d1c000-b5d26000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:53:52.656  6429  6429 W art     : b5d26000-b5d29000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:53:52.656  6429  6429 W art     : b5d29000-b5d2a000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:53:52.656  6429  6429 W art     : b5d2a000-b5d2b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5d2b000-b5d35000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-31 16:53:52.656  6429  6429 W art     : b5d35000-b5d38000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-31 16:53:52.656  6429  6429 W art     : b5d38000-b5d39000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-31 16:53:52.656  6429  6429 W art     : b5d39000-b5d3d000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:53:52.656  6429  6429 W art     : b5d3d000-b5d3e000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:53:52.656  6429  6429 W art     : b5d3e000-b5d3f000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:53:52.656  6429  6429 W art     : b5d3f000-b5d40000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b5d40000-b5d4d000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:53:52.656  6429  6429 W art     : b5d4d000-b5d4f000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:53:52.656  6429  6429 W art     : b5d4f000-b5d50000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:53:52.656  6429  6429 W art     : b5d50000-b6162000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-31 16:53:52.656  6429  6429 W art     : b6162000-b6163000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6163000-b616c000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-31 16:53:52.656  6429  6429 W art     : b616c000-b6170000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-31 16:53:52.656  6429  6429 W art     : b6170000-b6171000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6171000-b6178000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:53:52.656  6429  6429 W art     : b6178000-b6179000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:53:52.656  6429  6429 W art     : b6179000-b617a000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:53:52.656  6429  6429 W art     : b617a000-b617b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b617b000-b6196000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-31 16:53:52.656  6429  6429 W art     : b6196000-b6197000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-31 16:53:52.656  6429  6429 W art     : b6197000-b6198000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-31 16:53:52.656  6429  6429 W art     : b6198000-b6199000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b6199000-b61e5000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:53:52.656  6429  6429 W art     : b61e5000-b61e6000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b61e6000-b61e7000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:53:52.656  6429  6429 W art     : b61e7000-b61e8000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:53:52.656  6429  6429 W art     : b61e8000-b61e9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b61e9000-b61ed000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:53:52.656  6429  6429 W art     : b61ed000-b61ee000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b61ee000-b61ef000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:53:52.656  6429  6429 W art     : b61ef000-b61f0000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:53:52.656  6429  6429 W art     : b61f0000-b6228000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:53:52.656  6429  6429 W art     : b6228000-b6229000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:53:52.656  6429  6429 W art     : b6229000-b622a000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:53:52.656  6429  6429 W art     : b622a000-b622b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.656  6429  6429 W art     : b622b000-b62ca000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-31 16:53:52.656  6429  6429 W art     : b62ca000-b62e8000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-31 16:53:52.656  6429  6429 W art     : b62e8000-b62e9000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-31 16:53:52.656  6429  6429 W art     : b62e9000-b645c000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:53:52.656  6429  6429 W art     : b645c000-b6467000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:53:52.656  6429  6429 W art     : b6467000-b6468000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:53:52.656  6429  6429 W art     : b6468000-b657f000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:53:52.656  6429  6429 W art     : b657f000-b658a000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:53:52.656  6429  6429 W art     : b658a000-b658b000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:53:52.656  6429  6429 W art     : b658b000-b658f000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b658f000-b65b3000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-31 16:53:52.656  6429  6429 W art     : b65b3000-b65b5000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-31 16:53:52.656  6429  6429 W art     : b65b5000-b65b6000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-31 16:53:52.656  6429  6429 W art     : b65b6000-b665c000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-31 16:53:52.656  6429  6429 W art     : b665c000-b6669000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-31 16:53:52.656  6429  6429 W art     : b6669000-b666a000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-31 16:53:52.656  6429  6429 W art     : b666a000-b666b000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b666b000-b66be000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:53:52.656  6429  6429 W art     : b66be000-b66bf000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b66bf000-b66c0000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:53:52.656  6429  6429 W art     : b66c0000-b66c1000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:53:52.656  6429  6429 W art     : b66c1000-b66c6000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b66c6000-b66d8000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-31 16:53:52.656  6429  6429 W art     : b66d8000-b66d9000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b66d9000-b66da000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-31 16:53:52.656  6429  6429 W art     : b66da000-b66db000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-31 16:53:52.656  6429  6429 W art     : b66db000-b66e2000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:53:52.656  6429  6429 W art     : b66e2000-b66e3000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:53:52.656  6429  6429 W art     : b66e3000-b66e4000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:53:52.656  6429  6429 W art     : b66e4000-b66e5000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b66e5000-b66e8000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-31 16:53:52.656  6429  6429 W art     : b66e8000-b66e9000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-31 16:53:52.656  6429  6429 W art     : b66e9000-b66ea000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-31 16:53:52.656  6429  6429 W art     : b66ea000-b66ee000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-31 16:53:52.656  6429  6429 W art     : b66ee000-b66ef000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-31 16:53:52.656  6429  6429 W art     : b66ef000-b66f0000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-31 16:53:52.656  6429  6429 W art     : b66f0000-b66fe000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:53:52.656  6429  6429 W art     : b66fe000-b66ff000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b66ff000-b6700000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:53:52.656  6429  6429 W art     : b6700000-b6701000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:53:52.656  6429  6429 W art     : b6701000-b670a000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:53:52.656  6429  6429 W art     : b670a000-b670b000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:53:52.656  6429  6429 W art     : b670b000-b670c000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:53:52.656  6429  6429 W art     : b670c000-b6772000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-31 16:53:52.656  6429  6429 W art     : b6772000-b6773000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6773000-b6775000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-31 16:53:52.656  6429  6429 W art     : b6775000-b677e000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-31 16:53:52.656  6429  6429 W art     : b677e000-b6781000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6781000-b6818000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-31 16:53:52.656  6429  6429 W art     : b6818000-b681a000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-31 16:53:52.656  6429  6429 W art     : b681a000-b681b000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-31 16:53:52.656  6429  6429 W art     : b681b000-b681c000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b681c000-b6b3a000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-31 16:53:52.656  6429  6429 W art     : b6b3a000-b6b3b000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6b3b000-b6b56000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-31 16:53:52.656  6429  6429 W art     : b6b56000-b6b5a000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-31 16:53:52.656  6429  6429 W art     : b6b5a000-b6b5f000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6b5f000-b6b67000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b6b67000-b6b68000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b6b68000-b6b69000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:53:52.656  6429  6429 W art     : b6b69000-b6b97000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:53:52.656  6429  6429 W art     : b6b97000-b6b98000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6b98000-b6b9f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:53:52.656  6429  6429 W art     : b6b9f000-b6ba0000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:53:52.656  6429  6429 W art     : b6ba0000-b6be6000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:53:52.656  6429  6429 W art     : b6be6000-b6be7000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6be7000-b6bea000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:53:52.656  6429  6429 W art     : b6bea000-b6beb000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:53:52.656  6429  6429 W art     : b6beb000-b6c06000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-31 16:53:52.656  6429  6429 W art     : b6c06000-b6c0a000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-31 16:53:52.656  6429  6429 W art     : b6c0a000-b6c0b000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-31 16:53:52.656  6429  6429 W art     : b6c0b000-b6c58000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
08-31 16:53:52.656  6429  6429 W art     : b6c58000-b6c59000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6c59000-b6c65000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-31 16:53:52.656  6429  6429 W art     : b6c65000-b6c66000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-31 16:53:52.656  6429  6429 W art     : b6c66000-b6c73000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-31 16:53:52.656  6429  6429 W art     : b6c73000-b6c74000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6c74000-b6c75000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-31 16:53:52.656  6429  6429 W art     : b6c75000-b6c76000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-31 16:53:52.656  6429  6429 W art     : b6c76000-b6c7e000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:53:52.656  6429  6429 W art     : b6c7e000-b6c7f000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6c7f000-b6c80000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:53:52.656  6429  6429 W art     : b6c80000-b6c81000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:53:52.656  6429  6429 W art     : b6c81000-b6c88000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b6c88000-b6c89000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b6c89000-b6c8a000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:53:52.656  6429  6429 W art     : b6c8a000-b6c9e000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-31 16:53:52.656  6429  6429 W art     : b6c9e000-b6ca0000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-31 16:53:52.656  6429  6429 W art     : b6ca0000-b6ca1000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-31 16:53:52.656  6429  6429 W art     : b6ca1000-b6cc9000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:53:52.656  6429  6429 W art     : b6cc9000-b6ccb000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:53:52.656  6429  6429 W art     : b6ccb000-b6ccc000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:53:52.656  6429  6429 W art     : b6ccc000-b6ccf000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:53:52.656  6429  6429 W art     : b6ccf000-b6cd0000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:53:52.656  6429  6429 W art     : b6cd0000-b6cd1000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:53:52.656  6429  6429 W art     : b6cd1000-b6cda000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:53:52.656  6429  6429 W art     : b6cda000-b6cdb000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:53:52.656  6429  6429 W art     : b6cdb000-b6cdc000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:53:52.656  6429  6429 W art     : b6cdc000-b6cfc000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-31 16:53:52.656  6429  6429 W art     : b6cfc000-b6cfd000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-31 16:53:52.656  6429  6429 W art     : b6cfd000-b6cfe000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-31 16:53:52.656  6429  6429 W art     : b6cfe000-b6d71000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-31 16:53:52.656  6429  6429 W art     : b6d71000-b6d75000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-31 16:53:52.656  6429  6429 W art     : b6d75000-b6d78000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-31 16:53:52.656  6429  6429 W art     : b6d78000-b6d82000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6d82000-b6e0a000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-31 16:53:52.656  6429  6429 W art     : b6e0a000-b6e0b000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6e0b000-b6e0f000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-31 16:53:52.656  6429  6429 W art     : b6e0f000-b6e10000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-31 16:53:52.656  6429  6429 W art     : b6e10000-b6e11000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6e11000-b6e3a000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:53:52.656  6429  6429 W art     : b6e3a000-b6e3b000 ---p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6e3b000-b6e3e000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:53:52.656  6429  6429 W art     : b6e3e000-b6e3f000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:53:52.656  6429  6429 W art     : b6e3f000-b6f19000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:53:52.656  6429  6429 W art     : b6f19000-b6f20000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:53:52.656  6429  6429 W art     : b6f20000-b6f28000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:53:52.656  6429  6429 W art     : b6f28000-b6f29000 rw-p 00000000 00:00 0 
08-31 16:53:52.656  6429  6429 W art     : b6f29000-b6f2a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:53:52.666  6429  6429 W art     : b6f2a000-b6f2b000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-31 16:53:52.666  6429  6429 W art     : b6f2b000-b6f2c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f2c000-b6f2f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f2f000-b6f54000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-31 16:53:52.666  6429  6429 W art     : b6f54000-b6f55000 ---p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6f55000-b6f5c000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-31 16:53:52.666  6429  6429 W art     : b6f5c000-b6f5d000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-31 16:53:52.666  6429  6429 W art     : b6f5d000-b6f64000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-31 16:53:52.666  6429  6429 W art     : b6f64000-b6f65000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-31 16:53:52.666  6429  6429 W art     : b6f65000-b6f66000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-31 16:53:52.666  6429  6429 W art     : b6f66000-b6f67000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f67000-b6f7f000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f7f000-b6f80000 ---p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6f80000-b6f81000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f81000-b6f82000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f82000-b6f90000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f90000-b6f91000 ---p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6f91000-b6f92000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f92000-b6f93000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-31 16:53:52.666  6429  6429 W art     : b6f93000-b6f94000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:53:52.666  6429  6429 W art     : b6f94000-b6f96000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f96000-b6f97000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f97000-b6f98000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:53:52.666  6429  6429 W art     : b6f98000-b6f99000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-31 16:53:52.666  6429  6429 W art     : b6f99000-b6f9a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:53:52.666  6429  6429 W art     : b6f9a000-b6fba000 r--s 00000000 00:0b 6700       /dev/__properties__
08-31 16:53:52.666  6429  6429 W art     : b6fba000-b6fbb000 r--p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6fbb000-b6fbc000 ---p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6fbc000-b6fbe000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-31 16:53:52.666  6429  6429 W art     : b6fbe000-b6fbf000 r-xp 00000000 00:00 0          [sigpage]
08-31 16:53:52.666  6429  6429 W art     : b6fbf000-b6fda000 r-xp 00000000 b3:17 341        /system/bin/linker
08-31 16:53:52.666  6429  6429 W art     : b6fda000-b6fdb000 r--p 0001a000 b3:17 341        /system/bin/linker
08-31 16:53:52.666  6429  6429 W art     : b6fdb000-b6fdd000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-31 16:53:52.666  6429  6429 W art     : b6fdd000-b6fdf000 rw-p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : b6fdf000-b6fe4000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-31 16:53:52.666  6429  6429 W art     : b6fe4000-b6fe5000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-31 16:53:52.666  6429  6429 W art     : b6fe5000-b6fe6000 rw-p 00000000 00:00 0 
08-31 16:53:52.666  6429  6429 W art     : be844000-be865000 rw-p 00000000 00:00 0          [stack]
08-31 16:53:52.666  6429  6429 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-31 16:53:52.726  6429  6429 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 16:53:52.776  6429  6429 I Radio-JNI: register_android_hardware_Radio DONE
08-31 16:53:52.786  6429  6429 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:53:52.806  6429  6429 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:53:52.816   754  1496 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-31 16:53:52.826   754  1496 D ActivityManager: mDVFSHelper.acquire()
08-31 16:53:52.836   754  1496 V WindowManager: addAppToken: AppWindowToken{e2a0800 token=Token{64ce83 ActivityRecord{47a6132 u0 com.test.thalitest/.MainActivity t168}}} to stack=1 task=168 at 0
08-31 16:53:52.846   754   893 D SecWifiDisplayUtil: Metadata value : none
08-31 16:53:52.846   754   893 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{580d718 V.E...... R.....ID 0,0-0,0}
08-31 16:53:52.846   754   893 D ISSUE_DEBUG: InputChannelName : 448bf56 Starting com.test.thalitest
08-31 16:53:52.846   754  1496 D InputDispatcher: Focused application set to: xxxx
08-31 16:53:52.846   754  1496 I ActivityManager: Start proc 6444:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-31 16:53:52.856  6444  6444 E Zygote  : v2
08-31 16:53:52.856  6444  6444 I libpersona: KNOX_SDCARD checking this for 10004
08-31 16:53:52.856  6444  6444 I libpersona: KNOX_SDCARD not a persona
08-31 16:53:52.856  6444  6444 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:53:52.856   754  1496 D InputDispatcher: Focus left window: 3356
08-31 16:53:52.856  6444  6444 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:53:52.856   754   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{159ee1b u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-31 16:53:52.856   754  1326 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-31 16:53:52.856  6444  6444 E Zygote  : accessInfo : 0
08-31 16:53:52.856  6444  6444 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-31 16:53:52.856  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-31 16:53:52.856  6429  6429 D AndroidRuntime: Shutting down VM
08-31 16:53:52.866   293   293 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, uhalitest
08-31 16:53:52.876   754   893 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
08-31 16:53:52.876   754   893 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:53:52.876   754   893 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
08-31 16:53:52.876   754   893 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-31 16:53:52.876   754   893 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-31 16:53:52.886  6444  6444 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:53:52.886  6444  6444 D ActivityThread: Added TimaKeyStore provider
08-31 16:53:52.886   754  2180 V WindowOrientationListener: setCurrentAppOrientation :-1
08-31 16:53:52.886   754  2180 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-31 16:53:52.896   754   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{448bf56 u0 d0 Starting com.test.thalitest}
08-31 16:53:52.896  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-31 16:53:52.906   754   893 V WindowStateAnimator: Finishing drawing window Window{448bf56 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-31 16:53:52.916   754  2180 D ActivityManager:  Launching com.test.thalitest, updated priority
08-31 16:53:52.916   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef39364
08-31 16:53:52.916   754   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-31 16:53:52.936  1721  1881 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-31 16:53:52.936  1721  1721 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-31 16:53:52.946   293  1300 D libEGL  : eglTerminate EGLDisplay = 0xb2d7d64c
08-31 16:53:52.946   293   345 I SurfaceFlinger: id=18 Removed VSBConnecti (7/11)
08-31 16:53:52.946   293   341 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/11)
,08-31 16:53:52.946   754  3329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 16:53:52.946   293   345 D libEGL  : eglTerminate EGLDisplay = 0xb65bf64c
08-31 16:53:52.946   293   345 D libEGL  : eglTerminate EGLDisplay = 0xb65bf64c
08-31 16:53:52.956   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
08-31 16:53:52.956   293   341 I SurfaceFlinger: id=19 Removed VSBConnecti (5/10)
08-31 16:53:52.956   293   345 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/10)
08-31 16:53:52.956   293   345 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
08-31 16:53:52.956   293  1300 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-31 16:53:52.966  3356  3356 V ActivityThread: updateVisibility : ActivityRecord{74af2b3 token=android.os.BinderProxy@76135 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-31 16:53:52.966  2319  2341 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-31 16:53:52.966  1721  1721 V ActivityThread: updateVisibility : ActivityRecord{c328f5c token=android.os.BinderProxy@b563319 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 16:53:52.966  1721  1721 D Launcher: onTrimMemory. Level: 20
08-31 16:53:52.966   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
08-31 16:53:52.966   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
08-31 16:53:53.066   754  1326 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-31 16:53:53.076  6444  6444 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-31 16:53:53.086   754  3296 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:53:53.106  6444  6444 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-31 16:53:53.106  6444  6444 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-31 16:53:53.136  6444  6444 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-31 16:53:53.166  6444  6444 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-31 16:53:53.176  6444  6444 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 16:53:53.176   754   768 I art     : Background partial concurrent mark sweep GC freed 39785(3MB) AllocSpace objects, 88(1760KB) LOS objects, 27% free, 41MB/57MB, paused 1.627ms total 129.776ms
,08-31 16:53:53.186  6444  6444 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 8760-8763)
08-31 16:53:53.186  6444  6444 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-31 16:53:53.206  6444  6444 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24f9f8f}
,08-31 16:53:53.206  6444  6444 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-31 16:53:53.206  6444  6444 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:53:53.206  6444  6469 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-31 16:53:53.216  6444  6444 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 16:53:53.226  6444  6470 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,08-31 16:53:53.236  6444  6444 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:53:53.236  6444  6444 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:53:53.236  6444  6444 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:53:53.236  6444  6444 I Adreno-EGL: Local Branch: ss
08-31 16:53:53.236  6444  6444 I Adreno-EGL: Remote Branch: 
08-31 16:53:53.236  6444  6444 I Adreno-EGL: Local Patches: 
08-31 16:53:53.236  6444  6444 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:53:53.246  6444  6444 D libEGL  : eglInitialize EGLDisplay = 0xbeefcdac
,08-31 16:53:53.276   754  1732 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-31 16:53:53.276   754  1732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-31 16:53:53.316  6444  6444 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 16:53:53.336  6444  6444 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:53:53.336  6444  6444 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-31 16:53:53.336  6444  6444 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-31 16:53:53.336  6444  6444 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 16:53:53.356  6444  6444 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-31 16:53:53.356  6444  6444 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 16:53:53.456  6444  6444 D SecWifiDisplayUtil: Metadata value : none
,08-31 16:53:53.466  6444  6444 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4956e7c I.E...... R.....ID 0,0-0,0}
,08-31 16:53:53.466  6444  6499 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 16:53:53.466   754  1713 D ISSUE_DEBUG: InputChannelName : 6fe22db com.test.thalitest/com.test.thalitest.MainActivity
,08-31 16:53:53.476   754   775 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-31 16:53:53.476   754   775 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 16:53:53.476   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 16:53:53.476   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-31 16:53:53.486  6444  6444 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6444
,08-31 16:53:53.486   754  1414 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6444 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:53:53.496  6444  6444 D SecWifiDisplayUtil: Metadata value : none
,08-31 16:53:53.496  6444  6469 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-31 16:53:53.506   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, NainActivit
,08-31 16:53:53.516   754  1590 D InputDispatcher: Focus entered window: 6444
,08-31 16:53:53.516   754   893 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
08-31 16:53:53.516   754   893 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:53:53.516   754   893 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
08-31 16:53:53.516   754   893 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 16:53:53.526  6444  6499 D libEGL  : eglInitialize EGLDisplay = 0x9cad67c4
08-31 16:53:53.526  6444  6499 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:53:53.586  6444  6444 V ActivityThread: updateVisibility : ActivityRecord{c54ca81 token=android.os.BinderProxy@774116f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 16:53:53.586  6444  6444 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-31 16:53:53.586  6444  6444 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-31 16:53:53.606   754   774 V WindowStateAnimator: Finishing drawing window Window{6fe22db u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-31 16:53:53.606  6444  6444 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-31 16:53:53.606   754  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:53:53.616   754   893 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 16:53:53.616   754   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +549ms (total +777ms)
,08-31 16:53:53.616   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-31 16:53:53.616   754   754 I KnoxTimeoutHandler: SD activityfalse
,08-31 16:53:53.616   754   893 D ActivityManager: mDVFSHelper.release()
,08-31 16:53:53.616   754   893 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{47a6132 u0 com.test.thalitest/.MainActivity t168} time:289193
,08-31 16:53:53.616   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef39364
,08-31 16:53:53.616   754   893 D ViewRootImpl: #3 mView = null
,08-31 16:53:53.616   293   345 I SurfaceFlinger: id=20 Removed uhalitest (7/9)
,08-31 16:53:53.616   293  1300 I SurfaceFlinger: id=20 Removed uhalitest (-2/9)
,08-31 16:53:53.636  6444  6444 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-31 16:53:53.636  6444  6444 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@774116f time:289210
,08-31 16:53:53.636   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
,08-31 16:53:53.666  6444  6507 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:53:53.666  6444  6507 D libEGL  : eglInitialize EGLDisplay = 0x9b1ef3ec
,08-31 16:53:53.716  6444  6444 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6444
,08-31 16:53:53.806  6444  6444 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:53:53.976  6444  6513 D jxcore_app_log: JniHelper::setJavaVM(0xb483c000), pthread_self() = -1700214480
,08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 16:53:53.976  6444  6513 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2345f added. We now have 1 listener(s)
,08-31 16:53:53.976  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-31 16:53:53.986  6444  6513 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-31 16:53:53.986  6444  6513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 16:53:53.986  6444  6513 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 16:53:53.986  6444  6513 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adbf30a added. We now have 1 listener(s)
08-31 16:53:53.986  6444  6513 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 16:53:53.986  6444  6513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:53:53.996  6444  6513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
08-31 16:53:53.996  6444  6513 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:53:53.996  6444  6513 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:53:53.996  6444  6513 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:53:53.996  6444  6513 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 16:53:53.996  6444  6513 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:53:54.026  6444  6444 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:53:54.066   754  3297 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-31 16:53:54.476  1457  1457 D Recents : onTaskStackChanged
,08-31 16:53:54.486  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:53:54.926  6444  6514 W jxcore-log: Initializing JXcore engine
,08-31 16:53:54.926  6444  6514 W jxcore-log: JXcore engine is ready
,08-31 16:53:54.976  2062  2062 E audit   : type=1400 msg=audit(1472655234.976:281): avc:  denied  { ioctl } for  pid=6514 comm="Thread-903" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 16:53:54.976  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 16:53:54.976  2062  2062 E audit   : type=1300 msg=audit(1472655234.976:281): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=98d2a3c8 items=0 ppid=350 ppcomm=main pid=6514 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-903" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:53:54.976  2062  2062 E audit   : type=1327 msg=audit(1472655234.976:281): proctitle="com.test.thalitest"
08-31 16:53:54.976  2062  2062 E audit   : type=1320 msg=audit(1472655234.976:281): 
,08-31 16:53:54.976  2062  2062 E audit   : type=1400 msg=audit(1472655234.976:282): avc:  denied  { ioctl } for  pid=6514 comm="Thread-903" path="socket:[36770]" dev="sockfs" ino=36770 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-31 16:53:54.976  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 16:53:54.976  2062  2062 E audit   : type=1300 msg=audit(1472655234.976:282): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=1 a3=98d2a3c8 items=0 ppid=350 ppcomm=main pid=6514 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-903" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-31 16:53:54.976  2062  2062 E audit   : type=1327 msg=audit(1472655234.976:282): proctitle="com.test.thalitest"
08-31 16:53:54.976  2062  2062 E audit   : type=1320 msg=audit(1472655234.976:282): 
,08-31 16:53:54.986  6444  6514 W jxcore-log: Starting JXcore engine
,08-31 16:53:55.056  6444  6514 W jxcore-log: Platform android
08-31 16:53:55.056  6444  6514 W jxcore-log: 
,08-31 16:53:55.056  6444  6514 W jxcore-log: Process ARCH arm
08-31 16:53:55.056  6444  6514 W jxcore-log: 
,08-31 16:53:55.276  6444  6514 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:53:55.276  6444  6514 I jxcore-log: 
,08-31 16:53:55.276  6444  6514 W jxcore-log: JXcore engine is started
,08-31 16:53:55.276  6444  6513 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:53:55.286  6444  6444 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:53:55.886   754  1368 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/168_task.xml.bak
,08-31 16:53:59.116   754  3296 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:01.656   754  1704 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:54:01.666   754  1704 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-31 16:54:01.666   754  1704 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-31 16:54:01.666   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:54:01.666   754   754 I MotionRecognitionService: Plugged
,08-31 16:54:01.676   754   754 D MotionRecognitionService:   cableConnection= 1
08-31 16:54:01.676   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-31 16:54:01.676   754   754 D MotionRecognitionService: skip setTransmitPower. 
,08-31 16:54:01.676   754  1704 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
,08-31 16:54:01.676   754  1704 D BatteryService: stay LED for fully charged
,08-31 16:54:01.676  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:54:01.676  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:54:01.676  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:54:01.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:54:01.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:54:01.706  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 16:54:01.756   754  3296 D SSRM:n  : SIOP:: AP = 350, PST = 320, CUR = 300, LCD = 0
,08-31 16:54:02.886   754   917 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 16:54:02.916   754   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:54:05.276   754  1591 E Watchdog: !@Sync 9 [08-31 16:54:05.285]
,08-31 16:54:09.106  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:54:09.106  6444  6514 I jxcore-log: 
,08-31 16:54:09.106  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:54:09.106  6444  6514 I jxcore-log: 
,08-31 16:54:09.106  6444  6514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:09.106  6444  6514 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:54:09.106  6444  6514 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:54:09.106  6444  6514 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:54:09.106  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:54:09.106  6444  6514 I jxcore-log: 
08-31 16:54:09.106  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:54:09.106  6444  6514 I jxcore-log: 
,08-31 16:54:09.476  6444  6514 I jxcore-log: Running unit tests
08-31 16:54:09.476  6444  6514 I jxcore-log: 
,08-31 16:54:09.476  6444  6514 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:54:09.476  6444  6514 I jxcore-log: Failed to execute UT.
08-31 16:54:09.476  6444  6514 I jxcore-log: 
,08-31 16:54:09.476  6444  6514 I jxcore-log: Unit Test app is loaded
08-31 16:54:09.476  6444  6514 I jxcore-log: 
,08-31 16:54:09.476  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:54:09.476  6444  6514 I jxcore-log: 
,08-31 16:54:09.486  6444  6444 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 16:54:09.496  6444  6514 I WifiManager: isAllowWifiWarning() -> isCscWifiEnableWarning : false ChinaNalSecurityType : 
,08-31 16:54:09.496   754   774 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
08-31 16:54:09.496   754   774 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
08-31 16:54:09.506   754   774 E SContext.CaeProvider: setAttribute() : attribute is null!
,08-31 16:54:09.506   754   774 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,08-31 16:54:09.516   754   774 V CAE     : start(ContextProvider.java:128)
,08-31 16:54:09.516   754   774 V CAE     : clear(ActivityTrackerRunner.java:108)
08-31 16:54:09.516   754   774 V CAE     : enable(ActivityTrackerRunner.java:84)
,08-31 16:54:09.516   754   774 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 54, 9,
08-31 16:54:09.516   754   774 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 54, 9
,08-31 16:54:09.516   330   556 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 14, 54, 9
,08-31 16:54:09.526   754   774 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,08-31 16:54:09.526   754   774 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,08-31 16:54:09.536   754   774 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,08-31 16:54:09.536   754   774 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,08-31 16:54:09.536   754   774 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
08-31 16:54:09.536   754   774 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@eab2445, Service : ACTIVITY_TRACKER(1)
,08-31 16:54:09.536   754   774 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
08-31 16:54:09.536   754   774 D SContextService: 	.registerCallback : 1, client=
08-31 16:54:09.536   754   774 D SContextService: ===== SContext Service List =====
08-31 16:54:09.536   754   774 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@98978cb, Service : Activity Tracker
08-31 16:54:09.536   754   774 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@649a79a, service=Activity Tracker
,08-31 16:54:09.536   754   774 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
08-31 16:54:09.536   754   774 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
08-31 16:54:09.536   754   774 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
08-31 16:54:09.536   754   774 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
08-31 16:54:09.536   754   774 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
08-31 16:54:09.536   330   330 D Sensorhubs: sendContextData: -72, 26, 1, 0
,08-31 16:54:09.546   754   774 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,08-31 16:54:09.546   754   774 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,08-31 16:54:09.556   754   774 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,08-31 16:54:09.556   754   774 D SContextService: requestToUpdate() : service = Activity Tracker
08-31 16:54:09.556   754   774 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@649a79a, service=Activity Tracker
08-31 16:54:09.556   754   774 D WifiService: Wi-Fi on and Screen on , checkSensorStatus !!
08-31 16:54:09.556   754   774 D WifiService: setWifiEnabled: true pid=6444, uid=10004
,08-31 16:54:09.556   754   774 W ActivityManager: Permission Denial: getCurrentUser() from pid=6444, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:54:09.556   754   774 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:54:09.556   754   774 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6444, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:54:09.556   754   774 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28202)
08-31 16:54:09.556   754   774 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2437)
08-31 16:54:09.556   754   774 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2425)
08-31 16:54:09.556   754   774 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:257)
08-31 16:54:09.556   754   774 W WifiService: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 16:54:09.566   754  1328 D WifiBigDataLog: getJsonFormat() - feature : ONOF
08-31 16:54:09.566   754   774 D SettingsProvider: isChangeAllowed() : name = wifi_on
,08-31 16:54:09.566   754  1329 D WifiController: [FCC]setFccChannel() is called !!!
,08-31 16:54:09.566   754  1717 I WifiService: disconnect: pid=6444, uid=10004
08-31 16:54:09.566   754  1329 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,08-31 16:54:09.566   754  1329 D WifiStateMachine: setFccChannel: channel = 0
,08-31 16:54:09.566   754  1329 D SecContentProvider: insert(), uri = 2
,08-31 16:54:09.566   754  1328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.wifi.WifiStateMachine.insertLog:18701 com.android.server.wifi.WifiStateMachine.access$3900:292 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:8638 com.android.internal.util.StateMachine$SmHandler.processMsg:968 
,08-31 16:54:09.576   754  1328 D WifiBigDataLog: init : 
,08-31 16:54:09.576  6444  6514 D BluetoothAdapter: enable()
,08-31 16:54:09.576   754  1328 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 16:54:09.576   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a5878a8 u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ed2104 2104:com.samsung.android.providers.context/u0a174}
,08-31 16:54:09.586   754  1496 W ActivityManager: Permission Denial: getCurrentUser() from pid=6444, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:54:09.586   754  1496 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 16:54:09.586   754  1496 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6444, uid=10004 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:28202)
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2848)
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2838)
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.setBtEnableFlag(BluetoothManagerService.java:1218)
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:254)
08-31 16:54:09.586   754  1496 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:09.586   754  1496 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:54:09.586   754  1496 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:54:09.586   308  1190 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,08-31 16:54:09.596   308  1190 I WifiHW  : module is semco 3RD
08-31 16:54:09.596   308  1190 E WifiHW  : ==========[WIFI] SEMCO 3RD MODULE ===========
08-31 16:54:09.596   308  1190 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt_semco3rd
08-31 16:54:09.596   330   555 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 3, 50, -98, 91, 0, 0
08-31 16:54:09.596   308  1190 E WifiHW  : TEMP_FAILURE_RETRY complete
08-31 16:54:09.596   308  1190 D SoftapController: Softap fwReload - Ok
,08-31 16:54:09.596   754  1239 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 3, 50, -98, 91, 0, 0
,08-31 16:54:09.596   754  1496 D SettingsProvider: isChangeAllowed() : name = bluetooth_on
,08-31 16:54:09.596   754  1238 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 14, 54, 9,
,08-31 16:54:09.606   754  1238 D SensorHubManager: SendSensorHubData: send data = -63, 14, 14, 54, 9
08-31 16:54:09.606   330  1242 D Sensorhubs: sendContextData: -63, 14, 14, 54, 9
,08-31 16:54:09.606  6444  6514 I jxcore-log: My device name is: samsung-SM-G900F
08-31 16:54:09.606  6444  6514 I jxcore-log: 
,08-31 16:54:09.616  6444  6514 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:54:09.616  6444  6514 I jxcore-log: 
,08-31 16:54:09.616   754   892 I ActivityManager: Start proc 6532:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 16:54:09.626  6532  6532 E Zygote  : v2
08-31 16:54:09.626  6532  6532 I libpersona: KNOX_SDCARD checking this for 1002
08-31 16:54:09.626  6532  6532 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:09.626  6532  6532 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:09.626  6532  6532 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:09.626  6532  6532 E Zygote  : accessInfo : 0
,08-31 16:54:09.636   754  1238 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_SLEEP
,08-31 16:54:09.636   754  1238 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
08-31 16:54:09.636   754  1238 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 3, 50, -98, 91, 0, 0,
,08-31 16:54:09.636   308  1190 D CommandListener: Setting iface cfg
08-31 16:54:09.636   308  1190 D CommandListener: Trying to bring down wlan0
,08-31 16:54:09.636   754  1238 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
08-31 16:54:09.636   308  1190 D CommandListener: Clearing all IP addresses on wlan0
,08-31 16:54:09.646   754  1238 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1472655248987]
,08-31 16:54:09.646   754  1244 D SContextService: updateSContext() : event = Activity Tracker
,08-31 16:54:09.656   754  1328 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-31 16:54:09.656   754   754 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,08-31 16:54:09.656   754   754 D WifiService: ACTIVITY_STATUS_UNKNOWN 
08-31 16:54:09.656   754   754 D WifiService: setWifiScanWithSensor bMove = 0
,08-31 16:54:09.656   754  1328 D wifi    : Can not initialize the vendor function pointer table
,08-31 16:54:09.656   754  1328 E WifiNative-HAL: Could not start hal
08-31 16:54:09.656   754  1328 E WifiStateMachine: Failed to start HAL
08-31 16:54:09.656   754   754 D WifiStateMachine: setWifiScanMove bMove = 0
,08-31 16:54:09.656   754   754 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,08-31 16:54:09.656   754  1328 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 16:54:09.676  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:09.676  6532  6532 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:09.706  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in com.android.bluetooth rsrc of package null
,08-31 16:54:09.736  6549  6549 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 16:54:09.736  6549  6549 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:54:09.736  6549  6549 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x20000), vendorssid_list()
,08-31 16:54:09.736  6549  6549 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 16:54:09.746  6532  6532 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 16:54:09.756   754  1328 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 16:54:09.756  6549  6549 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 16:54:09.766   397   397 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6549
08-31 16:54:09.766   397   397 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
08-31 16:54:09.766  6549  6549 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 16:54:09.766  6549  6549 I wpa_supplicant: ssSupport state is = 1
08-31 16:54:09.766  6549  6549 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:54:09.766  6549  6549 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 16:54:09.766   397   397 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 6549
08-31 16:54:09.766   397   397 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x00000106
,08-31 16:54:09.766   754   754 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:54:09.766   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:54:09.766   754  1333 I WifiHs20Service: Message received 5011
08-31 16:54:09.766  1386  1386 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:54:09.766  1386  1386 D STATUSBAR-WifiTile: Wifi onReceive(2)
,08-31 16:54:09.776  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:09.776   754  1336 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
08-31 16:54:09.776  1386  1386 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=2
08-31 16:54:09.776  1386  1386 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:54:09.776  1386  1386 D HotspotTile: onReceive : 2, 0
08-31 16:54:09.776  1705  1716 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
,08-31 16:54:09.776  1705  1716 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
08-31 16:54:09.776   754  1336 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:54:09.776  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)ss_id will be loaded by secure_storage_daemon: /system/bin/wpa_supplicant
08-31 16:54:09.776  1386  2954 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 16:54:09.776   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5696fd u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8d8ff2 6444:com.test.thalitest/u0a4}
,08-31 16:54:09.776  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.776   754  1717 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:09.786   754  1717 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.796  6532  6532 D BtSettings.ProfileConfig: Adding GattService
,08-31 16:54:09.806  6532  6532 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 16:54:09.806  6558  6558 E Zygote  : v2
08-31 16:54:09.806  6558  6558 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:09.806  6558  6558 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:09.806  6558  6558 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-31 16:54:09.806  6558  6558 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:09.806  6558  6558 E Zygote  : accessInfo : 0
,08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding A2dpService
08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding HidService
08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding HealthService
08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding PanService
,08-31 16:54:09.816   754   846 I ActivityManager: Start proc 6558:com.samsung.android.securitylogagent/1000 for broadcast-5 com.samsung.android.securitylogagent/.receivers.NetworkReceiver
,08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding SapService
,08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 16:54:09.816  6532  6532 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 16:54:09.816  6532  6532 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 16:54:09.826   754  1298 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.gatt.GattService
08-31 16:54:09.826   754  1298 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754  1298 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:09.826   754  1298 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.826   754  1298 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  1298 D SettingsProvider: selectionArgs: 1002
,08-31 16:54:09.826   754  1298 D SettingsProvider: ret = -1
08-31 16:54:09.826   754  1676 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 16:54:09.826   754  1676 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754  1676 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.826   754  1676 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:09.826   754  1676 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  1676 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.826   754  1676 D SettingsProvider: ret = -1
,08-31 16:54:09.826   754  1732 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 16:54:09.826   754  1732 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754  1732 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:09.826   754  1732 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.826   754  1732 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  1732 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.826   754  1732 D SettingsProvider: ret = -1
,08-31 16:54:09.826   754  1590 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 16:54:09.826   754  1590 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:54:09.826   754  1590 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.826   754  1590 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  1590 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.826   754  1590 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:54:09.826   754  1590 D SettingsProvider: ret = -1
,08-31 16:54:09.826   754  2180 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 16:54:09.826   754  2180 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754  2180 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.826   754  2180 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  2180 D SettingsProvider: selectionArgs: 1002
,08-31 16:54:09.826   754  2180 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:09.826   754  2180 D SettingsProvider: ret = -1
,08-31 16:54:09.826   754  1704 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 16:54:09.826   754  1704 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754  1704 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:54:09.826   754  1704 D SettingsProvider: selectionArgs: false
08-31 16:54:09.826   754  1704 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.826   754  1704 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:54:09.826   754  1704 D SettingsProvider: ret = -1
,08-31 16:54:09.826   754   774 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 16:54:09.826   754   774 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:09.826   754   774 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.836   754   774 D SettingsProvider: selectionArgs: false
08-31 16:54:09.836   754   774 D SettingsProvider: selectionArgs: 1002
,08-31 16:54:09.836   754   774 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:09.836   754   774 D SettingsProvider: ret = -1
,08-31 16:54:09.836   754  1717 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.sap.SapService
08-31 16:54:09.836   754  1717 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:54:09.836   754  1717 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.836   754  1717 D SettingsProvider: selectionArgs: false
08-31 16:54:09.836   754  1717 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.836   754  1717 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:54:09.836   754  1717 D SettingsProvider: ret = -1
,08-31 16:54:09.836   754  1414 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:54:09.836   754  1414 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:54:09.836   754  1414 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.836   754  1414 D SettingsProvider: selectionArgs: false
08-31 16:54:09.836   754  1414 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.836   754  1414 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:54:09.836   754  1414 D SettingsProvider: ret = -1
,08-31 16:54:09.836   754  1713 D SettingsProvider: isChangeAllowed() : name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:54:09.836   754  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:54:09.836   754  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:09.836   754  1713 D SettingsProvider: selectionArgs: false
08-31 16:54:09.836   754  1713 D SettingsProvider: selectionArgs: 1002
08-31 16:54:09.836   754  1713 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,08-31 16:54:09.836   754  1713 D SettingsProvider: ret = -1
,08-31 16:54:09.846  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:09.846  6558  6558 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:09.846   754   775 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5696fd u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44e3643 6558:com.samsung.android.securitylogagent/1000}
,08-31 16:54:09.856  6558  6558 W ResourcesManager: getTopLevelResources: /system/app/SecurityLogAgent/SecurityLogAgent.apk / 1.0 running in com.samsung.android.securitylogagent rsrc of package null
,08-31 16:54:09.866  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:54:09.866  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:09.866  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:09.866  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:09.866  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:09.866  6558  6558 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm
,08-31 16:54:09.876   754  1414 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:09.876  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 16:54:09.876  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:54:09.876  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:54:09.876  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:54:09.886  6532  6532 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 16:54:09.886  6573  6573 E Zygote  : v2
08-31 16:54:09.886  6573  6573 I libpersona: KNOX_SDCARD checking this for 10170
08-31 16:54:09.886  6573  6573 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:09.896  6573  6573 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:09.896  6573  6573 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:09.896   754  1732 I ActivityManager: Start proc 6573:tv.peel.smartremote/u0a170 for broadcast-5 tv.peel.smartremote/com.peel.receiver.ConnectivityActionReceiver
,08-31 16:54:09.896   754  1732 I ActivityManager: Killing 4955:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-31 16:54:09.896  6573  6573 E Zygote  : accessInfo : 0
,08-31 16:54:09.896  6573  6573 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=tv.peel.smartremote 
,08-31 16:54:09.896  6532  6532 I bt_bluedroid: init
,08-31 16:54:09.896  6532  6572 I BluetoothAdapterState: Entering OffState
,08-31 16:54:09.906  6532  6578 E bt_core_counter: counter_init unable to open counter port
08-31 16:54:09.906  6532  6578 E bt_core_module: module_init failed to initialize "counter_module"
08-31 16:54:09.906  6532  6578 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 16:54:09.906  6532  6578 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:54:09.906  6532  6578 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 16:54:09.906  6532  6578 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 16:54:09.916  6532  6532 I bt_bluedroid: get_profile_interface socket
08-31 16:54:09.916  6532  6532 W bt_btif : btif_get_adapter_property 2
08-31 16:54:09.916  6532  6532 W bt_btif : btif_get_adapter_property 1
,08-31 16:54:09.916  6532  6532 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 16:54:09.916  6532  6532 I bt_bluedroid: get_profile_interface sdp
,08-31 16:54:09.926  6532  6587 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
08-31 16:54:09.926  6532  6587 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:54:09.926  6532  6587 I bt_bluedroid: getModelRssiValues
08-31 16:54:09.926  6532  6587 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:54:09.926  6532  6587 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:54:09.926  6532  6587 D BluetoothAdapterProperties: Name is: S5-1
08-31 16:54:09.926  6532  6548 I bt_bluedroid: config_hci_snoop_log
,08-31 16:54:09.926   754   754 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,08-31 16:54:09.926   754   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 16:54:09.936  6532  6572 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,08-31 16:54:09.936  6532  6572 D BluetoothAdapterProperties: Setting state to 14
08-31 16:54:09.936  6532  6572 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 16:54:09.936  6532  6572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:54:09.936  6532  6572 D BluetoothAdapterService: updateAdapterState state is 14
,08-31 16:54:09.936   754   892 D BluetoothManagerService: Ble Turning On/Off, G state: 1, S state: 1
08-31 16:54:09.936  6532  6572 D BluetoothAdapterService: Autoconnection is available 
08-31 16:54:09.936  6532  6572 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,08-31 16:54:09.936  6532  6572 D BluetoothSecureManager: getInstant: null
08-31 16:54:09.936  6532  6572 D BluetoothSecureManager: calling getMethod for getService
08-31 16:54:09.936  6532  6572 D BluetoothSecureManager: calling getService
,08-31 16:54:09.936  6532  6572 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@891ddc6
08-31 16:54:09.936  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:09.936  6573  6573 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:09.946   754  1704 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 16:54:09.946   754  1704 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 16:54:09.946  6532  6572 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:54:09.946   754  1590 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{5696fd u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ea5d84 6573:tv.peel.smartremote/u0a170}
08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:54:09.946  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:54:09.946  6532  6572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:54:09.946  6532  6572 D BluetoothBondStateMachine: make
,08-31 16:54:09.946  6532  6589 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 16:54:09.956  6532  6572 I BluetoothAdapterState: Entering PendingCommandState
,08-31 16:54:09.956  6532  6532 I BtGatt.JNI: classInitNative(L992): classInitNative: Success!
,08-31 16:54:09.956   754  1713 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-31 16:54:09.966  6573  6573 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,08-31 16:54:09.966  6532  6532 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 16:54:09.966  6532  6532 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:54:09.966  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
08-31 16:54:09.966  6532  6532 D BtGatt.GattService: start()
08-31 16:54:09.966  6532  6532 I bt_bluedroid: get_profile_interface gatt
,08-31 16:54:09.966  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
08-31 16:54:09.966  6532  6532 D BtGatt.AdvertiseManager: advertise manager created
,08-31 16:54:09.966  6532  6532 D BtGatt.AdvertiseManager: start
,08-31 16:54:09.966  6532  6532 D BtGatt.ScanManager: start
,08-31 16:54:09.966  6532  6532 D BtGatt.GattService: [GSIM LOG]: loadLogPref
,08-31 16:54:09.996  6532  6532 D BtGatt.GattService: [GSIM LOG]: loadLogPref END
,08-31 16:54:09.996  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
08-31 16:54:09.996  6532  6532 E BtGatt.GattService: notifyProfileServiceStateChanged
,08-31 16:54:09.996  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:09.996  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
08-31 16:54:09.996  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:09.996  6532  6532 V BluetoothAdapterState: isTurningOn()=false
08-31 16:54:09.996  6532  6532 V BluetoothAdapterState: isBleTurningOn()=true
08-31 16:54:09.996  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 16:54:09.996  6532  6572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,08-31 16:54:09.996  6532  6572 I bt_bluedroid: bt_bluedroid
08-31 16:54:09.996  6532  6578 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 16:54:10.006  6532  6578 I bt_hci  : start_up
,08-31 16:54:10.006  6532  6578 I bt_vendor: alloc value 0xb2be5be1
08-31 16:54:10.006  6532  6578 I bt_vendor: init
08-31 16:54:10.006  6532  6578 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 16:54:10.006  6532  6578 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-31 16:54:10.006  6532  6578 D bt_vendor: op for 5
08-31 16:54:10.006  6532  6578 D bt_vendor: op for 0
,08-31 16:54:10.006  6532  6578 I bt_upio : upio_set_bluetooth_power(on: 0)
08-31 16:54:10.006  6532  6578 D bt_upio : is_emulator_context : 0
08-31 16:54:10.006  6532  6578 D bt_upio : is_rfkill_disabled ? [0]
08-31 16:54:10.006  6532  6578 D bt_upio : is_rfkill_disabled ? [0]
,08-31 16:54:10.016  6532  6578 D bt_vendor: op for 0
08-31 16:54:10.016  6532  6578 I bt_upio : upio_set_bluetooth_power(on: 1)
08-31 16:54:10.016  6532  6578 D bt_upio : is_emulator_context : 0
08-31 16:54:10.016  6532  6578 D bt_upio : is_rfkill_disabled ? [0]
,08-31 16:54:10.016  6532  6578 D bt_hci  : start_up starting async portion
08-31 16:54:10.016  6532  6603 I bt_hci  : event_finish_startup
08-31 16:54:10.016  6532  6603 I bt_hci_h4: hal_open
08-31 16:54:10.016  6532  6603 D bt_vendor: op for 3
08-31 16:54:10.016  6532  6603 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 16:54:10.016  6532  6603 I bt_userial_vendor: userial_vendor_open():UART is setup
08-31 16:54:10.016  6532  6603 I bt_userial_vendor: device fd = 60 open
,08-31 16:54:10.026  6532  6603 D bt_vendor: op for 1
08-31 16:54:10.026  6532  6603 E bt_hwcfg: Start CFG HW, HCI reset
,08-31 16:54:10.036   397   397 I SecureStorage: [INFO]: SPID(0x00000007)Secure Storage Daemon finished processing with result: 0
,08-31 16:54:10.036  6573  6573 W System  : ClassLoader referenced unknown path: /system/app/SmartRemote_KL/lib/arm
,08-31 16:54:10.036  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)Processing data has been completed
,08-31 16:54:10.056  6549  6549 I wpa_supplicant: Ctrl_iface: loading system cred
08-31 16:54:10.056  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,08-31 16:54:10.086  6573  6573 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 16:54:10.086  6573  6573 I MultiDex: install
08-31 16:54:10.086  6573  6573 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:54:10.086  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
08-31 16:54:10.086   397   397 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6549
08-31 16:54:10.086   397   397 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
08-31 16:54:10.086  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
08-31 16:54:10.086  6549  6549 I wpa_supplicant: ssSupport state is = 1
,08-31 16:54:10.086  6549  6549 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:54:10.086  6549  6549 E wpa_supplicant: SIM READ ERROR
08-31 16:54:10.086  6549  6549 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:54:10.086  6549  6549 E wpa_supplicant: SIM READ ERROR
08-31 16:54:10.086  6549  6549 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:54:10.086  6549  6549 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:54:10.086  6549  6549 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 16:54:10.086  6549  6549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:54:10.096  6532  6603 E bt_hwcfg: Read Local Name after HCI reset
,08-31 16:54:10.096   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{2a42925: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.126  6532  6603 D bt_hwcfg: Chipset BCM4350C0
08-31 16:54:10.126  6532  6603 D bt_hwcfg: Target name = [BCM4350C0]
,08-31 16:54:10.126  6532  6603 I bt_hwcfg: module_type[semco3rd].
08-31 16:54:10.126  6532  6603 I bt_hwcfg: module_type[semco3rd] is invalid.
08-31 16:54:10.126  6532  6603 E bt_hwcfg: patchram path ORG . BCM4350C0
08-31 16:54:10.126  6532  6603 E bt_hwcfg: patchram path ORG .. BCM4350C0
08-31 16:54:10.126  6532  6603 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350C0
08-31 16:54:10.126  6532  6603 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350C0
08-31 16:54:10.126  6532  6603 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350C0
08-31 16:54:10.126  6532  6603 E bt_hwcfg: fw ver (org)0.0
,08-31 16:54:10.136  6532  6603 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,08-31 16:54:10.136  6532  6603 E bt_hwcfg: Remove module rev, try again BCM4350
08-31 16:54:10.136  6532  6603 D bt_hwcfg: Target name = [BCM4350]
08-31 16:54:10.136  6532  6603 I bt_hwcfg: module_type[semco3rd].
08-31 16:54:10.136  6532  6603 I bt_hwcfg: module_type[semco3rd] is invalid.
08-31 16:54:10.136  6532  6603 E bt_hwcfg: patchram path ORG . BCM4350
08-31 16:54:10.136  6532  6603 E bt_hwcfg: patchram path ORG .. BCM4350
08-31 16:54:10.136  6532  6603 E bt_hwcfg: patchram path ORG libpn547_fw.so BCM4350
08-31 16:54:10.136  6532  6603 E bt_hwcfg: patchram path ORG bcm4350_V0353.0733_wisol.hcd BCM4350
08-31 16:54:10.136  6532  6603 I bt_hwcfg: patch(org) : bcm4350_V0353.0733_wisol.hcd
08-31 16:54:10.136  6532  6603 E bt_hwcfg: Module type exists. Skip
08-31 16:54:10.136  6532  6603 E bt_hwcfg: patchram path ORG bcm4350_V0353.0727.hcd BCM4350
08-31 16:54:10.136  6532  6603 I bt_hwcfg: patch(org) : bcm4350_V0353.0727.hcd
08-31 16:54:10.136  6532  6603 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4350_V0353.0727.hcd
08-31 16:54:10.136  6532  6603 E bt_hwcfg: ORG patchram base 0353
08-31 16:54:10.136  6532  6603 E bt_hwcfg: ORG patchram minor 0727
08-31 16:54:10.136  6532  6603 E bt_hwcfg: fw ver (org)353.727
08-31 16:54:10.136  6532  6603 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4350_V0353.0727.hcd
,08-31 16:54:10.146  6532  6603 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-31 16:54:10.146   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{c0cfafa: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.146   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{d5b38ab: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.146  6532  6603 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,08-31 16:54:10.226  6573  6573 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-31 16:54:10.246  6573  6573 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,08-31 16:54:10.246   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a5d6b08: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.256   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{9332a1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.256  6573  6573 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 16:54:10.266  6573  6573 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 5836-5839)
08-31 16:54:10.266  6573  6573 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-31 16:54:10.276  6573  6573 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4956e7c}
08-31 16:54:10.276  6573  6573 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-31 16:54:10.276  6573  6573 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:54:10.286  6573  6573 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 16:54:10.286  6573  6573 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in tv.peel.smartremote rsrc of package null
,08-31 16:54:10.306   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{892b487: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.306   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{e22fb4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.306   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{40f57dd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.306   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{93bef52: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.306   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{cdc1223: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.316   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{14c9320: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.316   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{d2e94d9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.316   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{705ae9e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.316   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{4d3ad7f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.326   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{c37c14c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.326   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{d6aa595: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.326   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{b1a16aa: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.326   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e7fa29b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.336   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{ec5a638: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.336   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{a1d0611: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.336   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{85af376: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.346   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{82bcd77: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.346   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{44aede4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.346   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{abaf24d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.356   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{bfad102: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.356   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{f05ca13: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.356   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{6bb0450: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.356   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{ed16649: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.356   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{1c8fb4e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.366   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{b78f46f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.366   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{9d4157c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.366   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{7c11e05: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.366   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{13d7e5a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.376   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{74a688b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.376   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{d0b0d68: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.376   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{23a9581: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.376   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{f452626: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.386   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{9750267: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.386   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{379814: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.386   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{b7a08bd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.386   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{cd7eb2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.386   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{3c55e03: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.396   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{7002180: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.396   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e4373b9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.396   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{a10d3fe: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.396   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{e35d75f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.406   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{705d5ac: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.406   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{39e9275: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.406   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{6a2320a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.406   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{c0a8a7b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.416   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{cd0a098: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.416   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{352e0f1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.416   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{63964d6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.416   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{6ad5357: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.416   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{37b2e44: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.426   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{239b2d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.426   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{a3ef862: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.426   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{a49cdf3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.426   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{b1eeab0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.436   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{bcbbd29: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.436   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{1838ae: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.436   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{29564f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.436   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{a0001dc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.436   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{eba02e5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.446   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{43331ba: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.446   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{2cf086b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.446   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{4795fc8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.446   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{f8ce861: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.446   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{9d2af86: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.456   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{7d3c047: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.456   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{7a8b074: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.456   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{64ea99d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.456   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{39a3e12: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.456   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{b8219e3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.466   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{2da5fe0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.466   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7714299: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.466   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{8da295e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.466   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a32713f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.466   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{bb59a0c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.476   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{28a6f55: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.476   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{39b7d6a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.476   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{366e25b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.476   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{9284af8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.476   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{cfabd1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.486   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{36c0636: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.486   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{2a74937: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.486   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{1131ea4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.486   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{f52340d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.496   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{ea4fc2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.496   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{a1d41d3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.496   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4b58110: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.496   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{fb0409: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.496   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{e11a60e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.506   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{af0282f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.506   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{7d99e3c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.506   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{446d7c5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.506   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{f46151a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.506   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{761184b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.516   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{ec06228: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.516   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{8c22b41: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.516   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{92068e6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.516   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{aa6ee27: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.526   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{ecd78d4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.526   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{453a7d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.526   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{efa2d72: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.526   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{28a45c3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.526   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{df34e40: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.536   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{7f00179: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.536   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{e39aebe: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.536   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{6c17b1f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.536   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{cdf0e6c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.546   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{4e63c35: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.546   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{25df8ca: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.546   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{a0caa3b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.546   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7e4a558: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.556   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{cb66b1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.556   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{dcad796: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.556   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{111af17: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.556   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{aaabf04: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.566   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{1febced: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.566   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{354d722: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.566   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{af825b3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.566   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{296c770: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.566   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{b973ae9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.576   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{c8d436e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.576   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{7c56a0f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.576   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{bf8ea9c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.576   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{11f9ca5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.586   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{8ce287a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.586   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{878982b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.586   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{5f81488: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.586   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{a125e21: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.586   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{1065246: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.596   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{4e68c07: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.596   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{93df134: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.596   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{115bb5d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.596   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{c454cd2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.606   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{355e1a3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.606   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{d62eca0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.606   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{af7b059: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.606   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{107641e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.616   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{ddaf4ff: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.616   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{91a32cc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.616   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{169f915: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.616   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{f41a42a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.616   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{173e21b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.626   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{91dafb8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.626   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{d7e1191: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.626   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{f2dd8f6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.626   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{2e484f7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.626   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{9da0f64: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.636   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{de135cd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.636   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{d68e82: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.636   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{5527993: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.636   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{fdabdd0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.636   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4d861c9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.646   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{86310ce: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.646   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{ea11bef: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.646   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{af5e6fc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.646   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{9fc5185: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.656   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{3236bda: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.656   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{58d880b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.656   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{3876e8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.656   308  1181 D Netd    : Iface wlan0 link up
,08-31 16:54:10.656   308  1181 D Netd    : Iface wlan0 link up
08-31 16:54:10.656   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:10.656   754   851 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:54:10.656   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{bb58101: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.666   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{15c6ba6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.666   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{c782c3d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.666   754   892 D Tethering: enter TetherInterfaceSM  and send tetherstatechangebroadcast
,08-31 16:54:10.666   754   892 D Tethering: NAP Supported and not Wifi Model
,08-31 16:54:10.666   754   892 E Tethering: No numeric data
,08-31 16:54:10.666   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:10.666   754   851 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:54:10.666   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{41b497e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.666   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{576dedf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.676   754   892 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 16:54:10.676  1386  1386 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 16:54:10.676  1386  1386 D HotspotTile: updateTetherState():false, false
,08-31 16:54:10.676   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aff072c u-1 android.net.conn.TETHER_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a623dbe 754:system/1000}
,08-31 16:54:10.686   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{acda5f5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.686   754  1325 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:54:10.686   754  1325 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:54:10.686   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{29e7f8a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.686   754  1325 V NetworkStats: performPollLocked() took 5ms
,08-31 16:54:10.686  6573  6619 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
,08-31 16:54:10.686   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{71489fb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.696   754  1326 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:54:10.696   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{8eb6a18: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.696   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{d1fac71: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.696   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d6d0a56: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.696   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{517cad7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.696   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{4390fc4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.706   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{4b19ead: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.706  6573  6573 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:54:10.706  6573  6573 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:54:10.706  6573  6573 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:54:10.706  6573  6573 I Adreno-EGL: Local Branch: ss
08-31 16:54:10.706  6573  6573 I Adreno-EGL: Remote Branch: 
08-31 16:54:10.706  6573  6573 I Adreno-EGL: Local Patches: 
08-31 16:54:10.706  6573  6573 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:54:10.706   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{4c775e2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.706   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{da43d73: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.706   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{3996430: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{1f678a9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{a6b0e2e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{37b3dcf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{568935c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{f94f665: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.716  6573  6573 D libEGL  : eglInitialize EGLDisplay = 0xbeefd23c
,08-31 16:54:10.726   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{c9ddf3a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.726   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{a17e7eb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.726   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{f998948: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.726   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{1e393e1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.726   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{5fab506: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.726   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{78b17c7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.736   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{261f1f4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.736   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{2248d1d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.736   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{dfd1b92: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.736   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{8176963: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.746   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{9a63960: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.746  6549  6549 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
08-31 16:54:10.746  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)Checking if this device supports Secure Storage
,08-31 16:54:10.746   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{181de19: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.746   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{64d5ede: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.746   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{f8d38bf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.746   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{9258b8c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.756   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{fc942d5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.756   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{cc8aea: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.766   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{466a1db: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.766   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{f65d478: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.766   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{1e83751: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.766   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{a606bb6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.766   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{a380b7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.776   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{b5fc024: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.776   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{eaba90: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.776   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{4297f89: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.776   754  1298 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10170
,08-31 16:54:10.776   754  1298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,08-31 16:54:10.776   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{ea18b45: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.776  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)This device supports Secure Storage
,08-31 16:54:10.776   397   397 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 1010, gid 1010, pid 6549
08-31 16:54:10.776   397   397 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x0000010C
08-31 16:54:10.786  6549  6549 I SecureStorage: [INFO]: SPID(0x00000007)SS Daemon is running
08-31 16:54:10.786  6549  6549 I wpa_supplicant: ssSupport state is = 1
,08-31 16:54:10.786   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{f95829a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.786  6549  6549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 16:54:10.786   308  1181 D Netd    : Iface p2p0 link up
,08-31 16:54:10.786   308  1181 D Netd    : Iface p2p0 link up
,08-31 16:54:10.786   754   851 D Tethering: interfaceLinkStateChanged p2p0, true
08-31 16:54:10.786   754   851 D Tethering: interfaceStatusChanged p2p0, true
,08-31 16:54:10.786   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{d8fb7cb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.786   754   851 D Tethering: interfaceLinkStateChanged p2p0, true
08-31 16:54:10.786   754   851 D Tethering: interfaceStatusChanged p2p0, true
,08-31 16:54:10.786   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{2334ba8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.786   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{cd496c1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.796   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{6b92e66: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.796   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{1e005a7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.796   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{4457a54: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.796   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{dd2ddfd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.806   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{119caf2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.806   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{cfd5543: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.806   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{ca9e7c0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.816   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{7745cf9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.816   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{275a43e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.816   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{a16029f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.816   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{625bfec: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.826   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{a23c64a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.826   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{a4eed8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.826   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{3dffd16: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.826   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{956d4a2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.836   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{60e1533: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.836   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{6e6c0f0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.836   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{8a97669: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.836  6532  6603 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 16:54:10.846  6532  6603 I bt_hwcfg: FW Download delta = 742647
08-31 16:54:10.846  6532  6603 D bt_hwcfg: Settlement delay -- 100 ms
08-31 16:54:10.846  6532  6603 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 16:54:10.846   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{7198ee: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.846   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{30ad18f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.846   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{36cf7ab: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.846   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{381aa52: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.846   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{d86b123: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.856  6549  6549 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
08-31 16:54:10.856   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{644620: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.856   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{4cfcbd9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.856   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{f6c199e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.856   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{f093c7f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.866   754  1328 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 16:54:10.866   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{97a44c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.866   754  1328 E WifiStateMachine: Deffering msg in Supplicant Starting State131085
,08-31 16:54:10.866   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{3684c95: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.866   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{afc31aa: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.876  6573  6573 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 16:54:10.876   754  1328 D WifiNative-wlan0: callSECApiBoolean - ID [301]
,08-31 16:54:10.876  6549  6549 I wpa_supplicant: HOTSPOT20_ENABLE called ON
08-31 16:54:10.876  6549  6549 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:54:10.876  6549  6549 E wpa_supplicant: SIM READ ERROR
08-31 16:54:10.876  6549  6549 I wpa_supplicant: Blacklist: Clear (all) 
08-31 16:54:10.876   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{7ff219b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.876   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{cc0b938: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.876   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{fce1d11: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.876   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{3c3be76: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.886   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{3a43c77: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.886  6549  6549 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 16:54:10.886   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{26430e4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.886   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{fe6794d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.886  6573  6573 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 16:54:10.886  6549  6549 I wpa_supplicant: wlan0: Skip scan - bUseNetwork false
,08-31 16:54:10.886  6573  6573 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-31 16:54:10.886  6573  6573 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-31 16:54:10.886   754  1328 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:54:10.886  6573  6573 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 16:54:10.896   754   754 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:54:10.896   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
08-31 16:54:10.896   754  1330 D HS20StateMachine: WIFI_STATE_ENABLED
,08-31 16:54:10.896   754  1333 I WifiHs20Service: Message received 5011
08-31 16:54:10.896   754  1330 D HS20StateMachine: reloadCredentialsToSupplicant
,08-31 16:54:10.896   754  1330 D HotspotDBHandler: getCredentialIds
,08-31 16:54:10.896   754  1336 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:54:10.896  1386  1386 D STATUSBAR-WifiTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:54:10.896  1386  1386 D STATUSBAR-WifiTile: Wifi onReceive(3)
08-31 16:54:10.896  1386  1386 D STATUSBAR-WifiTile: getWiFiState : WifiManager.WIFI_STATE=3
,08-31 16:54:10.896  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:54:10.896  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,08-31 16:54:10.896  1386  1386 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:54:10.896  1386  2954 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 16:54:10.896   754  1336 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:54:10.906   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca54c02 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8d8ff2 6444:com.test.thalitest/u0a4}
08-31 16:54:10.906  1386  1386 D HotspotTile: onReceive : 3, 0
,08-31 16:54:10.906   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{b162913: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.906  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,08-31 16:54:10.906  6444  6444 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:10.906  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:54:10.906   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{a57750: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.906  6444  6444 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:54:10.906  6444  6444 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.906   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{8ae5d49: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.906   754  1414 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.916   754  1414 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.916   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{220264e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.916   754  1414 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:10.916   754  1414 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.916   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{1b0436f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.916  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-31 16:54:10.916   754  1328 D WifiConfigStore: Loading config and enabling all networks 
,08-31 16:54:10.916   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca54c02 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44e3643 6558:com.samsung.android.securitylogagent/1000}
,08-31 16:54:10.926   754  1590 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:10.926  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:54:10.926  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:54:10.926  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-31 16:54:10.926  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:54:10.926  6573  6573 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-31 16:54:10.926  6573  6573 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:54:10.936  6573  6573 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-31 16:54:10.936  6573  6573 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-31 16:54:10.936  6573  6573 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-31 16:54:10.936   754  1328 I WifiConfigStore: "NG700" is a verified password AP: true
08-31 16:54:10.936   754  1328 E WifiConfigStore: Not a HS20
,08-31 16:54:10.936   754  1330 I ActivityManager: Start proc 6652:com.samsung.hs20provider/u0a202 for content provider com.samsung.hs20provider/.Hs20Provider
,08-31 16:54:10.936  6652  6652 E Zygote  : v2
08-31 16:54:10.936  6652  6652 I libpersona: KNOX_SDCARD checking this for 10202
08-31 16:54:10.936  6652  6652 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:10.936  6652  6652 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:10.936  6652  6652 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:10.946  6652  6652 E Zygote  : accessInfo : 0
,08-31 16:54:10.946  6652  6652 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,08-31 16:54:10.946   754  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ca54c02 u-1 android.net.wifi.WIFI_STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ea5d84 6573:tv.peel.smartremote/u0a170}
,08-31 16:54:10.946   754  1328 D WifiConfigStore: loaded 0 passpoint configs
,08-31 16:54:10.946   754  1328 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 16:54:10.946   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{372b87c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.946   754  1328 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 16:54:10.946  6532  6603 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,08-31 16:54:10.946   754  1328 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,08-31 16:54:10.946   754  1328 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 16:54:10.946   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
08-31 16:54:10.946   754   754 D WifiHs20Service: reason: 2
08-31 16:54:10.946   754  1333 I WifiHs20Service: Message received 5014
08-31 16:54:10.946   754  1333 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
08-31 16:54:10.946   754  1333 E WifiHs20Service: The changed config is NULL
,08-31 16:54:10.946   754  1328 D WifiConfigStore: setNetworkPriorityDefault: networkId = 0, priority = 1
,08-31 16:54:10.956   754  1328 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 16:54:10.956   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{7f68505: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.956   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{75c595a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.956   754  1328 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-31 16:54:10.956  6549  6549 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:54:10.956  6549  6549 I wpa_supplicant: resume autoscan
08-31 16:54:10.956  6549  6549 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:54:10.956  6549  6549 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:54:10.956  6549  6549 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 16:54:10.956  6549  6549 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-31 16:54:10.956  6549  6549 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:54:10.956  6549  6549 I wpa_supplicant: First Scan Start
,08-31 16:54:10.956   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{b27a78b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.966  6549  6549 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 16:54:10.966   754  1328 D WifiNative-wlan0: Setting external_sim to 1
,08-31 16:54:10.966   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{570e068: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.966   754  1328 D WifiStateMachine: [setCountryCode()] Airplane mode return !!!
,08-31 16:54:10.966   754  1328 D WifiStateMachine: Setting OUI to DA-A1-19
,08-31 16:54:10.966   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{ddf6c81: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.966  6549  6549 I wpa_supplicant: bt_status is set be DISCONNECTED
,08-31 16:54:10.966   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{7f6b126: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.966   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{7673167: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.976   754  1328 E WifiNative-wlan0: do suspend true
,08-31 16:54:10.976   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{4a79b14: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.976   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{2154fbd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.976   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{a8cb9b2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.976   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{2b7d03: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.976   754  1327 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:54:10.986   754  1328 D WifiNative-HAL: Failing getSupportedFeatureset because HAL isn't started
,08-31 16:54:10.986   754   754 D RttService: SCAN_AVAILABLE : 3
,08-31 16:54:10.986   308  1190 D CommandListener: Setting iface cfg
08-31 16:54:10.986   308  1190 D CommandListener: Trying to bring up p2p0
08-31 16:54:10.986   754  1354 E WifiScanningService: could not start HAL
08-31 16:54:10.986   754  1355 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:54:10.986   754  1327 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 16:54:10.986  6652  6652 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:10.986   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{5ed5480: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:10.986  6652  6652 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:10.986   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{cc2ab9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.986   754  1327 D SecContentProvider: insert(), uri = 2
,08-31 16:54:10.986   754  1327 D WifiP2pService: P2pEnablingState
08-31 16:54:10.986   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{8befe: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.986   754  1327 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 16:54:10.986   754  1327 D WifiP2pService: P2p socket connection successful
08-31 16:54:10.986   754  1327 D WifiP2pService: P2pEnabledState
,08-31 16:54:10.986   754  1327 D SecContentProvider: insert(), uri = 2
,08-31 16:54:10.996  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:54:10.996  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:10.996   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{45ee65f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:10.996  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:10.996  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:10.996  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:10.996   754  1327 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,08-31 16:54:10.996   754  1328 D WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 16:54:10.996   754  1328 D WifiStateMachine: [FCC]Airplane on, setFccChannel(0)!!!
08-31 16:54:10.996   754  1328 D WifiStateMachine: setFccChannelNative: channel = 0
08-31 16:54:10.996   754  1328 D WifiNative-wlan0: callSECApiInt - ID [230]
,08-31 16:54:10.996   754   754 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 16:54:10.996   754   893 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 16:54:10.996   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{b7bb975: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.006   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{badcd0a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.006   754   893 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
08-31 16:54:11.006  6652  6652 W ResourcesManager: getTopLevelResources: /system/app/Hs20Provider/Hs20Provider.apk / 1.0 running in com.samsung.hs20provider rsrc of package null
08-31 16:54:11.006   754   893 D WifiDisplayController: disconnect
08-31 16:54:11.006   754   893 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:54:11.006   754  1327 D WifiP2pService: create mNetworkAgent
,08-31 16:54:11.006   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{d35897b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.006   754  1327 D P2pNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:54:11.006  1386  1386 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 16:54:11.006   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{fd13398: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.016   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{95b77f1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.016  6652  6652 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm
,08-31 16:54:11.016   754  1676 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 16:54:11.016   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{171f144: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.016  1386  1386 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 16:54:11.016   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{634254f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.016   754  1327 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:11.026   754  1335 D ConnectivityService: Got NetworkAgent Messenger
,08-31 16:54:11.026   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{7aee9e5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.026   754  1335 E ConnectivityService: updateNetworkInfo()
,08-31 16:54:11.026   754   893 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:11.026  6549  6549 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,08-31 16:54:11.026  6549  6549 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,08-31 16:54:11.036   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{37c76b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.036   754  1335 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:11.036   754  1335 D ConnectivityService: NetworkAgent connected
,08-31 16:54:11.036   754  1335 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 13
,08-31 16:54:11.036   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{e44b2c8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.036   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{693f61: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.046   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{425ba86: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.046   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.046  6652  6662 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
08-31 16:54:11.046  6652  6662 D HotspotProvider: CREDENTIAL
08-31 16:54:11.046  6652  6662 D HotspotProvider: No prepend tags
,08-31 16:54:11.046  6532  6603 I bt_hwcfg: vendor lib fwcfg completed
08-31 16:54:11.046  6532  6603 I bt_vendor: firmware callback
08-31 16:54:11.046  6532  6603 I bt_hci  : firmware_config_callback
08-31 16:54:11.046  1705  1720 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,08-31 16:54:11.046   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{c896f47: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.056  6532  6667 I bt_btu_task: Bluetooth chip preload is complete
,08-31 16:54:11.056   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{e563374: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:54:11.056  6532  6667 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 16:54:11.056   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{e19709d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.056   754  1330 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
08-31 16:54:11.056   754  1330 D HS20StateMachine: enter : DiscoveringState
,08-31 16:54:11.066  6573  6573 I ClientConfig: Set OkHttp cache (max size: 52MB) to /data/user/0/tv.peel.smartremote/cache/peel-cache
,08-31 16:54:11.066   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.076   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{763b8e3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.076   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{a5d12e0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.076   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{ea17999: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.076   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{323945e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.086   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{c0f003f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.086   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{4307d0c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.086   754  1327 E WifiP2pService: Failed to set my phone number info into probe response
,08-31 16:54:11.086   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{2071655: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.096   754  1327 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 16:54:11.096   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{90986a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.096   754  1327 D WifiNative-p2p0: p2pGetDeviceAddress returning ee:1f:72:63:11:86
,08-31 16:54:11.096   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{7fd615b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.096   754   893 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] S5-1
08-31 16:54:11.096   754   893 D WifiDisplayController:  deviceAddress: ee:1f:72:63:11:86
08-31 16:54:11.096   754   893 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 16:54:11.096   754   893 D WifiDisplayController:  secondary type: null
08-31 16:54:11.096   754   893 D WifiDisplayController:  wps: 0
08-31 16:54:11.096   754   893 D WifiDisplayController:  grpcapab: 0
08-31 16:54:11.096   754   893 D WifiDisplayController:  devcapab: 0
08-31 16:54:11.096   754   893 D WifiDisplayController:  status: 3
08-31 16:54:11.096   754   893 D WifiDisplayController:  wfdInfo: null
08-31 16:54:11.096   754   893 D WifiDisplayController:  groupownerAddress: null
08-31 16:54:11.096   754   893 D WifiDisplayController:  GOdeviceName: null
08-31 16:54:11.096   754   893 D WifiDisplayController:  interfaceAddress: 
08-31 16:54:11.096   754   893 D WifiDisplayController:  SConnectInfo : null
08-31 16:54:11.096   754   893 D WifiDisplayController:  contactInfoHash : null
08-31 16:54:11.096   754   893 D WifiDisplayController:  ssDevInfo : 0
08-31 16:54:11.096   754   893 D WifiDisplayController:  iconIdx : 0
,08-31 16:54:11.096   754  1327 D WifiP2pService: DeviceAddress: ee:11:86
,08-31 16:54:11.096   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{1ee5df8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.096   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{8efc2d1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.096   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a17d136: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.106   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{3a6b837: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.106   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{ba761a4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.106   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{edcbb0d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.106   754  1327 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 16:54:11.106   754  1327 D WifiP2pService: InactiveState
08-31 16:54:11.106   754  1327 D P2pNetworkAgent: NetworkAgent: NetworkAgent fully connected
08-31 16:54:11.106   754  1327 D WifiP2pService: InactiveState{ what=143376 }
,08-31 16:54:11.106   754  1327 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 16:54:11.106   754  1327 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
08-31 16:54:11.106   754  1335 E ConnectivityService: updateNetworkInfo()
08-31 16:54:11.106   754  1335 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,08-31 16:54:11.106   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{e07cac2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.116   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{d24a0d3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.116   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7caf410: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.116   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{c26fb09: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.116   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{f0bd10e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.116   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{8e772f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.126   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{253413c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.126  6573  6573 I Fabric  : Initializing Crashlytics 2.3.2.56
,08-31 16:54:11.126   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{bbb3ec5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.126   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{d37f01a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.126   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{a15574b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.126   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ab13528: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.136   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{4787bd4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.136   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{6ff817d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.136   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{7ec6872: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.136   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{1a764c3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.136   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{6cb8140: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.146   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{687716c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.146   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{1c26335: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.146   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{9fc93ca: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.146   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{dcea93b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.156   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7303858: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.156   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{cc2fdb1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.156   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{382296: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.156   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{8749e17: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.156   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{e9c8204: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.166   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{b58c3ed: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.166   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{6cbd222: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.166   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{71b04b3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.166   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{761ba70: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.176   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{e0ab1e9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.176   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{ff8ee6e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.176  6573  6573 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10170, CallingPid : 6573
,08-31 16:54:11.186   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{ec9837a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.186   754  1414 D ConnectivityService: listenForNetwork for Listen from uid/pid:10170/6573 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:11.186   754  3296 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:11.186   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{c38572b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.186   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{4ce6788: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.196   754  1414 I ActivityManager: Killing 4979:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-31 16:54:11.196   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{a9db521: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.196   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{adc5d46: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.196   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e633b07: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.206   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{aa67434: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.206   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{47f825d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.206   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{4f107d2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.206   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{96e80a3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.206   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{509fa0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.216   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{8b6e759: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.216   754  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{833cf1e u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:11.226  2738  2738 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:54:11.226   754  1590 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-31 16:54:11.226  2738  2738 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:54:11.226   754  1704 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:11.226  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 16:54:11.226   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{65e83ff: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.236   754   774 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:11.236   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{8b015cc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.236   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{165a015: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.236  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:54:11.236  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:54:11.236  2738  2738 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 16:54:11.236   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{449bf2a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.246   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{21611b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.246  2738  4210 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 16:54:11.246   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{faec2b8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.246   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{f0d2891: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.256   754  1717 I ActivityManager: Killing 4444:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-31 16:54:11.256  6573  6670 E Fabric  : Error performing auto configuration.
08-31 16:54:11.256  6573  6670 E Fabric  : java.util.concurrent.ExecutionException: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.FutureTask.report(FutureTask.java:94)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.FutureTask.get(FutureTask.java:164)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.u.c(Onboarding.java:105)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.u.f(Onboarding.java:45)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:63)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.p.a(InitializationTask.java:28)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.a.c.c.call(AsyncTask.java:311)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:11.256  6573  6670 E Fabric  : Caused by: java.lang.IllegalStateException: Invalid format of fabric file,.fabric/
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:91)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.k.a(FabricKitsFinder.java:58)
08-31 16:54:11.256  6573  6670 E Fabric  : 	at a.a.a.a.k.call(FabricKitsFinder.java:35)
08-31 16:54:11.256  6573  6670 E Fabric  : 	... 4 more
,08-31 16:54:11.256   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{833cf1e u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d9a9f0d 5451:com.samsung.android.app.FileShareServer/5005}
,08-31 16:54:11.266  5451  5451 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:54:11.266   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{c1ca3f6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.266  5451  5451 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,08-31 16:54:11.266  5451  5451 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-31 16:54:11.266  5451  5451 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
08-31 16:54:11.266  5451  5451 W System.err: 	at com.samsung.android.app.FileShareServer.ServerBroadcastReceiver.onReceive(ServerBroadcastReceiver.java:34)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3634)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.app.ActivityThread.access$2000(ActivityThread.java:221)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1876)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:54:11.266  5451  5451 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-31 16:54:11.266  5451  5451 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:11.266   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{86af3f7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.266  5451  5451 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:54:11.266  5451  5451 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-31 16:54:11.266   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{3e95264: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.286  6532  6667 W bt_l2cap: l2c_link_processs_ble_num_bufs 15
,08-31 16:54:11.286  6532  6667 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb2b394d5
08-31 16:54:11.286  6532  6667 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb2b394d5 
08-31 16:54:11.286  6532  6667 E bt_btm  : btm_ble_set_search_if search_if=4
,08-31 16:54:11.286  6682  6682 E Zygote  : v2
08-31 16:54:11.286  6682  6682 I libpersona: KNOX_SDCARD checking this for 5005
08-31 16:54:11.286  6682  6682 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:11.286  6682  6682 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:11.286  6682  6682 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:11.286   754   846 I ActivityManager: Start proc 6682:com.samsung.android.app.FileShareClient/5005 for broadcast-5 com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver
08-31 16:54:11.286  6532  6587 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 24832 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 1024 mIsExtendedScanSupported = false mIsDebugLogSupported = false mAobleSupported = 0
08-31 16:54:11.286   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{ecabccd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.286  6682  6682 E Zygote  : accessInfo : 0
08-31 16:54:11.296  6682  6682 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.app.FileShareClient 
,08-31 16:54:11.296  6532  6587 E bt_btif : btif_transfer_context() Cal
,08-31 16:54:11.306   754   774 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-31 16:54:11.306  6532  6587 D bt_hci  : do_postload posting postload work item
,08-31 16:54:11.306  6532  6587 E bt_btif_sock: btif_sock_init: !vhci_init
08-31 16:54:11.306  6532  6603 I bt_hci  : event_postload
08-31 16:54:11.306  6532  6603 D bt_vendor: op for 2
08-31 16:54:11.306  6532  6603 D bt_hwcfg: hw_sco_config
08-31 16:54:11.306  6532  6603 I bt_vendor: sco_config_cb
08-31 16:54:11.306  6532  6603 I bt_hci  : sco_config_callback postload finished.
08-31 16:54:11.306  6532  6603 D bt_vendor: op for 6
08-31 16:54:11.306  6532  6603 D bt_upio : upio_set : pio 2 action 2, polarity 0
,08-31 16:54:11.306  6532  6587 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:289 ##
,08-31 16:54:11.306  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.306  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.306  6532  6603 D bt_upio : upio_start_stop_timer : timer_settime success
08-31 16:54:11.306  6532  6603 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-31 16:54:11.316  6532  6587 D bt_bte_conf: Device ID record 1 : primary
08-31 16:54:11.316  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.316  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.316  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.316  6532  6587 D bt_bte_conf:   vendorId            = 0075
08-31 16:54:11.316  6532  6587 D bt_bte_conf:   vendorIdSource      = 0001
08-31 16:54:11.316  6532  6587 D bt_bte_conf:   product             = 0100
08-31 16:54:11.316  6532  6587 D bt_bte_conf:   version             = 0200
08-31 16:54:11.316  6532  6587 D bt_bte_conf:   clientExecutableURL = 
,08-31 16:54:11.316  6532  6587 D bt_bte_conf:   serviceDescription  = 
08-31 16:54:11.316  6532  6587 D bt_bte_conf:   documentationURL    = 
08-31 16:54:11.316  6532  6587 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 16:54:11.316  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.316  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.316  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.316  6532  6578 D bt_stack_manager: event_start_up_stack finished
08-31 16:54:11.316  6532  6587 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
08-31 16:54:11.316  6532  6587 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 7
08-31 16:54:11.316  6532  6587 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24844
08-31 16:54:11.316  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.316  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.316  6532  6603 D bt_upio : BT_WAKE is asserted already
08-31 16:54:11.316  6532  6587 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4354 37.4MHz SEMCO-B80 K-LTE-0353
,08-31 16:54:11.316  6532  6587 D BluetoothDataManager: firmwareVersion from Property : bcm4350_V0353.0727.hcd
08-31 16:54:11.316  6532  6587 E BluetoothAdapterState: stateChangeCallback : 1
08-31 16:54:11.316  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.316  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.316  6532  6603 D bt_upio : BT_WAKE is asserted already
08-31 16:54:11.316  6532  6572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,08-31 16:54:11.316   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{5670982: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.316  6532  6603 I bt_vendor: low_power_mode_cb
08-31 16:54:11.316  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.316  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.316  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.316  6532  6572 D BluetoothAdapterProperties: Setting state to 15
08-31 16:54:11.316  6532  6572 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 16:54:11.326  6532  6572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 16:54:11.326  6532  6572 D BluetoothAdapterService: updateAdapterState state is 15
,08-31 16:54:11.326  6532  6572 D BluetoothAdapterService: Autoconnection is available 
08-31 16:54:11.326  6532  6572 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
08-31 16:54:11.326  6532  6572 I BluetoothAdapterState: Entering BleOnState
,08-31 16:54:11.326  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:11.326  6682  6682 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:11.336   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{2a66aef: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.336   754  1737 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{833cf1e u-1 android.net.wifi.p2p.CONNECTION_STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{94a89fc 6682:com.samsung.android.app.FileShareClient/5005}
,08-31 16:54:11.346   754   892 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:54:11.346   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{618c70b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.356   754   892 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,08-31 16:54:11.356   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{2b449e8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.356  6532  6572 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,08-31 16:54:11.356  6682  6682 W ResourcesManager: getTopLevelResources: /system/app/AllshareFileShareClient/AllshareFileShareClient.apk / 1.0 running in com.samsung.android.app.FileShareClient rsrc of package null
,08-31 16:54:11.366  6532  6572 D BluetoothAdapterProperties: Setting state to 11
,08-31 16:54:11.366  6532  6572 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 16:54:11.366  6532  6572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:54:11.366  6532  6572 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 16:54:11.366   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{6b85801: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.366   754   892 D BluetoothManagerService: Turning On/Off, G state: 2, S state: 2, mBLE count: 0, s BLE count: 0
,08-31 16:54:11.366  6532  6572 D BluetoothAdapterService: Autoconnection is available 
08-31 16:54:11.366  6532  6572 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
08-31 16:54:11.366  6532  6572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:54:11.366  6532  6572 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:54:11.366  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:54:11.386  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:54:11.386   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{8046e00: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.386  6682  6682 W System  : ClassLoader referenced unknown path: /system/app/AllshareFileShareClient/lib/arm
,08-31 16:54:11.386   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:54:11.386   754   754 I InputMethodManagerService: [BT Setting State] State =11
,08-31 16:54:11.386  6532  6532 D HeadsetService: Received start request. Starting profile...
08-31 16:54:11.386  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
,08-31 16:54:11.386  6532  6532 D HeadsetProvider: make
,08-31 16:54:11.386  6532  6532 D HeadsetProvider: HeadsetProvider
08-31 16:54:11.386  1767  1767 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:54:11.386  6532  6532 I HeadsetProvider: clearAllHeadsetSettings(0)
,08-31 16:54:11.396   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
08-31 16:54:11.396   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:11.396   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,08-31 16:54:11.396  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:11.396   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:11.406  6682  6682 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:54:11.406  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 16:54:11.406  1386  1386 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 16:54:11.406  6682  6682 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:54:11.406   754  1713 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,08-31 16:54:11.416   754   774 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 16:54:11.416  1386  1386 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:11.416  1386  1386 D BluetoothTile:  getBluetoothState : 11
,08-31 16:54:11.416  1386  1386 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,08-31 16:54:11.416  1982  1982 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 16:54:11.416  1386  2954 D BluetoothTile:  handleUpdatestate:false name:null
08-31 16:54:11.416  1386  2954 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 16:54:11.416  6532  6532 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:54:11.416  6532  6532 D HeadsetStateMachine: make
,08-31 16:54:11.426  6532  6532 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 16:54:11.426  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:54:11.436   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{781fd18: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.436  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:54:11.436  1386  1386 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 )
,08-31 16:54:11.446  1386  1386 D STATUSBAR-QSTileView: dynamicallyReduceTextSize: 0
,08-31 16:54:11.446   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ed2104 2104:com.samsung.android.providers.context/u0a174}
,08-31 16:54:11.456  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 16:54:11.456  6682  6682 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:54:11.466  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,08-31 16:54:11.476  6532  6532 I bt_bluedroid: get_profile_interface handsfree
,08-31 16:54:11.476   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{6540ccf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.476  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:54:11.486  6532  6572 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:54:11.486  6532  6572 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:54:11.486  6532  6572 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:54:11.486  6532  6572 I BluetoothAdapterState: Entering PendingCommandState
,08-31 16:54:11.486   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c789e4d 1857:com.sec.android.app.shealth:remote/u0a34}
,08-31 16:54:11.496   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{507dd65: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.506   754  1298 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:11.506  6532  6532 I DualScoManager: Instantiating Dual Sco Manager
08-31 16:54:11.506  6532  6532 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:54:11.506  2738  2738 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:54:11.506  6532  6532 D BluetoothAtMessage: createCMTIContentObservers
,08-31 16:54:11.516   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{aec3a3a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.516  6532  6532 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@47a6c4e
,08-31 16:54:11.516   754  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
,08-31 16:54:11.516  6532  6532 D HeadsetProvider: setHeadsetDB - Can't find 300 for 7C:F9:0E:34:8A:XX
,08-31 16:54:11.516  1386  1386 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:54:11.516  1386  1386 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 16:54:11.526   754  1496 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d5556 6532:com.android.bluetooth/1002}
,08-31 16:54:11.526  6549  6549 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
08-31 16:54:11.526   308  1181 D Netd    : Iface wlan0 link up
,08-31 16:54:11.526  6549  6549 I wpa_supplicant: autoscan_samsung_exponential_notify_scan : scan_interval = 8
08-31 16:54:11.526  6549  6549 I wpa_supplicant: autoscan: autoscan_notify_scan, scan_interval = 8
08-31 16:54:11.526  6549  6549 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:54:11.526   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:11.526   754   851 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:54:11.526  6549  6549 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
,08-31 16:54:11.526  6549  6549 I wpa_supplicant:  selected from pick network BSS F4.99.3E ssid='NG700' et= 090,gp=03,cu=987654321,sc=987654321
08-31 16:54:11.526  6549  6549 I wpa_supplicant:    allow  - level is under -85dBm [-43] or selected nid [-1] [0]
,08-31 16:54:11.526  6549  6549 I wpa_supplicant: wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz level=-43) 
,08-31 16:54:11.526   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{32ea6eb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.536   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{67adc48: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.536   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{91deae1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.536   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{a53c006: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.546   754  1414 I ActivityManager: Killing 4855:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-31 16:54:11.546  6532  6532 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 300, 1, true
,08-31 16:54:11.556   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{4cec6c7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.556   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{18574f4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.556  6532  6532 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@b320305
,08-31 16:54:11.556  6532  6532 D HeadsetProvider: setHeadsetDB - Can't find 400 for 7C:F9:0E:34:8A:XX
,08-31 16:54:11.556   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{82d541d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.566  6532  6532 I HeadsetProvider: setHeadsetDB - 7C:F9:0E:34:8A:XX, 400, 1, true
,08-31 16:54:11.566  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,08-31 16:54:11.566  6532  6701 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
08-31 16:54:11.566  6532  6532 E HeadsetService: notifyProfileServiceStateChanged
,08-31 16:54:11.566   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{cd01519: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.566  2104  2104 D BluetoothA2dp: Proxy object connected
,08-31 16:54:11.566  6532  6532 D A2dpService: Received start request. Starting profile...
08-31 16:54:11.566  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
,08-31 16:54:11.566   754   754 D BluetoothA2dp: Proxy object connected
,08-31 16:54:11.566  6532  6532 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 16:54:11.566   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{55cc9de: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.576  6532  6701 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 16:54:11.576  6532  6701 D HeadsetStateMachine: map size, before remove : 0
,08-31 16:54:11.576  6532  6701 D HeadsetStateMachine: map size, after remove: 0
,08-31 16:54:11.576   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.576  6532  6532 I bt_bluedroid: get_profile_interface avrcp
,08-31 16:54:11.576   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{db7c7bf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.576   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{c2b20db: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.576  6532  6532 I Avrcp   : No of Audio players :: 2
,08-31 16:54:11.586  6532  6532 I Avrcp   : App Package name is GM
,08-31 16:54:11.586   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{6c1e778: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.586  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.android.bluetooth rsrc of package null
,08-31 16:54:11.586   754   774 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-31 16:54:11.596  6532  6532 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-31 16:54:11.596  6532  6532 I Avrcp   : App Package name is SM
,08-31 16:54:11.596  6532  6532 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.android.bluetooth rsrc of package null
,08-31 16:54:11.596  6532  6532 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,08-31 16:54:11.596   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{3e64e51: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.596  6532  6532 I Avrcp   : No of Video players :: 2
08-31 16:54:11.596  6532  6532 I Avrcp   : Video App Package name is others
,08-31 16:54:11.596   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{89236b6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.606   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{9b0efb7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.606  6532  6532 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.android.bluetooth rsrc of package null
,08-31 16:54:11.606   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{7ea0324: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.606  6532  6532 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-31 16:54:11.606  6532  6532 I Avrcp   : Video App Package name is others
,08-31 16:54:11.616  6532  6532 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.android.bluetooth rsrc of package null
,08-31 16:54:11.616   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{d707e8d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.616  6549  6549 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 16:54:11.616   308  1181 D Netd    : Iface wlan0 link up
08-31 16:54:11.616   308  1181 D Netd    : Iface wlan0 link up
08-31 16:54:11.616   308  1181 D Netd    : Iface wlan0 link up
,08-31 16:54:11.616   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:11.616   754   851 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:54:11.616  6532  6532 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-31 16:54:11.616  6532  6532 I Avrcp   : Add tempPlayer
08-31 16:54:11.616  6532  6532 V Avrcp   : MediaPlayerInfo: mPlayerId=5
08-31 16:54:11.616  6532  6532 V Avrcp   : no_of_players : 5
08-31 16:54:11.616  6532  6532 I Avrcp   : Total no of players: 5
08-31 16:54:11.616  6532  6532 V Avrcp   : swapping the samsung player with 1st player
,08-31 16:54:11.616   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:11.616   754   851 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:54:11.616  6549  6549 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 16:54:11.616  6549  6549 I wpa_supplicant: wlan0: WPA: RX message 1 of 4-Way Handshake from F4.99.3E (ver=2)
,08-31 16:54:11.616   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{d830842: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.616  6549  6549 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 2/4
,08-31 16:54:11.616   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:11.616   754   851 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:54:11.626   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{25ad053: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.626  6532  6532 D Avrcp   : Compose Browsing Service Candidate
,08-31 16:54:11.626   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.626  6532  6532 D Avrcp   : ResolveInfo info ResolveInfo{693b726 com.google.android.music/.browse.MediaBrowserService m=0x108000}
08-31 16:54:11.626  6532  6532 D Avrcp   : Initialize Media Controller
,08-31 16:54:11.626   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{f562d90: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.626  6549  6549 I wpa_supplicant: wlan0: WPA: RX message 3 of 4-Way Handshake from F4.99.3E (ver=2)
,08-31 16:54:11.626   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.626  6549  6549 I wpa_supplicant: wlan0: WPA: Sending EAPOL-Key 4/4
,08-31 16:54:11.636  6549  6549 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 16:54:11.636  6549  6549 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 16:54:11.636  6532  6532 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-31 16:54:11.636   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{6f37689: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.636  6549  6549 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 16:54:11.636   308  1181 D Netd    : Iface wlan0 link up
,08-31 16:54:11.636   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:11.636   754   851 D Tethering: interfaceStatusChanged wlan0, true
,08-31 16:54:11.636   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{abd668e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.636  6532  6532 E Avrcp   : getActiveSessions
08-31 16:54:11.636  6532  6532 D Avrcp   : pick active media Controller
08-31 16:54:11.636  6532  6532 D Avrcp   : Get the active Media Controller 
08-31 16:54:11.636   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7b81eaf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.636  6532  6532 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:54:11.636  6532  6532 D A2dpStateMachine: make
,08-31 16:54:11.636  6532  6532 I bt_bluedroid: get_profile_interface a2dp
,08-31 16:54:11.636   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{d1892bc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.636  6532  6532 E bt_btif : warning : media task started media_task_refcnt 1 
08-31 16:54:11.636  6532  6532 E bt_btif : warning : no command pending, ignore ack
,08-31 16:54:11.636   754  1328 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:54:11.646   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{993f245: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.646  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
08-31 16:54:11.646  6532  6532 E A2dpService: notifyProfileServiceStateChanged
,08-31 16:54:11.646  6532  6707 D A2dpStateMachine: Enter Disconnected: -2
08-31 16:54:11.646  6532  6532 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:54:11.646   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{2066dc1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.646   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{673b966: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.646  6532  6532 D HidService: Received start request. Starting profile...
08-31 16:54:11.646  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
08-31 16:54:11.646  6532  6532 I bt_bluedroid: get_profile_interface hidhost
08-31 16:54:11.646  6532  6532 D HidService: setHidService(): set to: null
08-31 16:54:11.646  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
08-31 16:54:11.646   754  1328 V AlarmManager:  remove PendingIntent] PendingIntent{ca734a7: PendingIntentRecord{5667d54 android broadcastIntent}}
08-31 16:54:11.646  6532  6532 E HidService: notifyProfileServiceStateChanged
,08-31 16:54:11.646  6532  6532 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:54:11.646   754  1328 D WifiNetworkAgent: NetworkAgent: Registering NetworkAgent
,08-31 16:54:11.646  6532  6532 D HealthService: Received start request. Starting profile...
08-31 16:54:11.646  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
,08-31 16:54:11.656   754   754 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
08-31 16:54:11.656   754   754 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:11.656   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
08-31 16:54:11.656   754  1333 I WifiHs20Service: Message received 5007
,08-31 16:54:11.656  6532  6532 I bt_bluedroid: get_profile_interface health
08-31 16:54:11.656  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
08-31 16:54:11.656  6532  6532 E HealthService: notifyProfileServiceStateChanged
,08-31 16:54:11.656   754  1328 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:54:11.656   754  1335 D ConnectivityService: Got NetworkAgent Messenger
08-31 16:54:11.656   754  1335 E ConnectivityService: updateNetworkInfo()
08-31 16:54:11.656   754  1335 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:11.656   754  1335 D ConnectivityService: NetworkAgent connected
08-31 16:54:11.656   308  1190 D CommandListener: Setting iface cfg
,08-31 16:54:11.666   754  1328 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:54:11.666  6532  6532 I BluetoothPanServiceJni: classInitNative(L113): succeeds
,08-31 16:54:11.666   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{12343ee: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.666   754   754 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:54:11.666   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.666  6532  6532 D PanService: Received start request. Starting profile...
08-31 16:54:11.666  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
08-31 16:54:11.666  6532  6532 D BluetoothPanServiceJni: initializeNative(L118): pan
08-31 16:54:11.666  6532  6532 I bt_bluedroid: get_profile_interface pan
,08-31 16:54:11.676  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
,08-31 16:54:11.676  6532  6532 E PanService: notifyProfileServiceStateChanged
08-31 16:54:11.676   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{2caa08f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.676   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{acc1f1c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.676  6532  6532 D BluetoothMapService: Received start request. Starting profile...
08-31 16:54:11.676  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
,08-31 16:54:11.676   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{40a1108: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.676   754  1328 D WifiNetworkAgent: NetworkAgent: NetworkAgent fully connected
08-31 16:54:11.676   754  1335 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:11.676   754  1335 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:54:11.686  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
08-31 16:54:11.686  6532  6532 E BluetoothMapService: notifyProfileServiceStateChanged
08-31 16:54:11.686   754  1335 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:54:11.686  6532  6532 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 16:54:11.686   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{14be2c6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.686   754  1328 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:54:11.686   754  1496 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:54:11.686   754  1496 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
,08-31 16:54:11.686  6532  6532 D HeadsetStateMachine: Proxy object connected
,08-31 16:54:11.686   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{78c1287: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.686  6532  6532 V SapService: SapBinder()
,08-31 16:54:11.686   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{fb335b4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.686  6532  6532 D SapService: Received start request. Starting profile...
,08-31 16:54:11.686  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
08-31 16:54:11.686  6532  6532 V SapService: start()
,08-31 16:54:11.696   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{6e2e5dd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.696   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{6936552: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.696  6532  6532 D SapService: Disable sap : false
,08-31 16:54:11.696  6532  6532 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
08-31 16:54:11.696   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{15e849e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.696  6532  6532 E SapService: notifyProfileServiceStateChanged
08-31 16:54:11.696  6532  6532 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:54:11.696  6532  6701 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-31 16:54:11.696  6532  6701 E HeadsetStateMachine: Unknown message: 11
08-31 16:54:11.696  6532  6532 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:54:11.696  6532  6701 D HeadsetStateMachine: Disconnected process message: 19, size: 0
,08-31 16:54:11.696  6532  6701 E HeadsetStateMachine: Unknown message: 19
08-31 16:54:11.706  6532  6532 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 16:54:11.706   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{1dacb7f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.706   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{763874c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
,08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:11.706  6532  6532 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 16:54:11.706  6532  6701 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 16:54:11.706  6532  6701 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 16:54:11.706  6532  6701 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:54:11.706  6532  6701 E HeadsetStateMachine: Unknown message: 11
08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOn()=true
,08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:11.706  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
,08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isTurningOn()=true
,08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.706  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:11.706  6532  6532 D BluetoothAdapterService: HID Host service started
,08-31 16:54:11.716   754  2180 I ActivityManager: Start proc 6714:com.google.android.apps.maps/u0a121 for broadcast-3 com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 16:54:11.716  6714  6714 E Zygote  : v2
,08-31 16:54:11.716  6714  6714 I libpersona: KNOX_SDCARD checking this for 10121
08-31 16:54:11.716  6714  6714 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:11.716  6714  6714 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-31 16:54:11.716  6714  6714 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:11.716   754  2180 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:54:11.726  6714  6714 E Zygote  : accessInfo : 0
,08-31 16:54:11.726  6714  6714 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.maps 
,08-31 16:54:11.726   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{961f395: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.726   754  2180 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4255, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-31 16:54:11.726  6532  6532 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:54:11.726   754  2180 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
,08-31 16:54:11.726   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:11.726   754  2180 D BatteryService: stay LED for fully charged
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:11.726   754   754 I MotionRecognitionService: Plugged
08-31 16:54:11.726   754   754 D MotionRecognitionService:   cableConnection= 1
08-31 16:54:11.726   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-31 16:54:11.726   754   754 D MotionRecognitionService: skip setTransmitPower. 
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:11.726  6532  6532 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:54:11.726  6532  6532 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:54:11.726  6532  6701 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 16:54:11.726  6532  6701 E HeadsetStateMachine: Unknown message: 11
08-31 16:54:11.726  6532  6701 D HeadsetStateMachine: Disconnected process message: 19, size: 0
08-31 16:54:11.726  6532  6701 E HeadsetStateMachine: Unknown message: 19
08-31 16:54:11.726  6532  6532 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
08-31 16:54:11.726  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:54:11.726  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:54:11.726  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOff()=false
,08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
,08-31 16:54:11.726  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 16:54:11.726  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 16:54:11.736  6532  6532 E BluetoothAdapterService: handleMessage() - Message: 1
,08-31 16:54:11.736  6532  6532 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
08-31 16:54:11.736  6532  6532 V BluetoothAdapterState: isTurningOff()=false
,08-31 16:54:11.736  6532  6532 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:11.736  6532  6532 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:11.736  6532  6532 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 16:54:11.736  6532  6572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,08-31 16:54:11.736   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{12a4caa: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.736  6532  6532 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:54:11.736  6532  6572 E BluetoothServiceJni: enableBrEdrNative:
08-31 16:54:11.736  6532  6701 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 16:54:11.736  6532  6572 I bt_bluedroid: enable_bredr
,08-31 16:54:11.736   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{7daa09b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.736   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{7e7cc38: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.746  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.746  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.746  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.746  6532  6667 D         : Codec ==> copy capability info [bta_av_co_audio_init:584]
,08-31 16:54:11.746  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.746  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.746  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.746  6532  6603 D bt_vendor: op for 7
,08-31 16:54:11.746  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.746  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.746  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:54:11.746  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:54:11.746  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 16:54:11.746  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.746  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.746  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.746  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.746  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.746  6532  6603 D bt_upio : BT_WAKE is asserted already
08-31 16:54:11.746  6532  6587 I bt_bta_hh: BTA_HhEnable sec_mask:0x24 p_cback:0xb2b0ead1
,08-31 16:54:11.746  6532  6587 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x100048
08-31 16:54:11.746  6532  6587 D BluetoothAdapterProperties: Address is:7C:F9:0E:34:8A:A0
08-31 16:54:11.746  6532  6587 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:54:11.746  6532  6587 I bt_bluedroid: getModelRssiValues
08-31 16:54:11.746  6532  6587 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:54:11.746  6532  6587 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:54:11.746  6532  6587 D BluetoothAdapterProperties: Name is: S5-1
08-31 16:54:11.746   754   754 D SettingsProvider: isChangeAllowed() : name = bluetooth_name
,08-31 16:54:11.756   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{93b3411: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.756  6532  6587 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:54:11.756  6532  6587 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:54:11.756  6532  6587 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:54:11.756  6532  6587 E bt_btif : btif_handle_bluetooth_enable_evt
08-31 16:54:11.756  6532  6587 E bt_btif : ANT+ socket does not initialize.
,08-31 16:54:11.756  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:11.756  6532  6587 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:54:11.756   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{e388976: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.756  6532  6587 D IOP_DB_BT: db_open: db_open : handle 2997526544l, read 17911 bytes onto local cache
08-31 16:54:11.756  6532  6587 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 16:54:11.756  6532  6587 D IOP_DB_BT: db_query: result 1
08-31 16:54:11.756  6532  6587 I         : iop_db_open: iop_db_open status 0
08-31 16:54:11.756  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.756  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.756  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.756  6532  6587 E BluetoothAdapterState: stateChangeCallback : 17
08-31 16:54:11.756  6532  6587 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:54:11.756  6532  6572 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
08-31 16:54:11.756  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.756  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.756  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.756  6532  6572 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:54:11.756  6532  6572 D BluetoothAdapterProperties: State =  11
,08-31 16:54:11.756  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.756  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.756  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.756  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.756  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.756   754  2180 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
08-31 16:54:11.756  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.756  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.756  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.756  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.756   754  1414 D SecContentProvider: insert(), uri = 2
,08-31 16:54:11.766  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.766  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.766  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.766  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.766  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.766  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.766  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.766  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.766  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.766  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.766  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.766  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.766  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.766  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.766  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.776  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.776  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.776  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.776   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{f38ab77: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.776  6532  6587 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:54:11.776  6532  6587 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:54:11.776  6532  6587 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:54:11.776  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.776  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.776  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.776  6532  6572 D BluetoothAdapterProperties: Setting state to 12
08-31 16:54:11.776  6532  6572 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 16:54:11.776  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.776  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.776  6532  6603 D bt_upio : BT_WAKE is asserted already
08-31 16:54:11.776  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.776  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.776  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.776  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.776  6532  6603 D bt_vendor: op for 7
08-31 16:54:11.776  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:11.776  6532  6603 D bt_upio : BT_WAKE is asserted already
08-31 16:54:11.776  6714  6714 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:11.776  6714  6714 D ActivityThread: Added TimaKeyStore provider
08-31 16:54:11.776   754  1328 E WifiNative-wlan0: do suspend false
,08-31 16:54:11.776  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:54:11.776  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:11.776  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:11.776  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:11.776  6444  6444 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 16:54:11.776  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:11.776   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{46973e4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.786  6532  6572 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 16:54:11.786   754  1327 D WifiP2pService: InactiveState{ what=143375 }
08-31 16:54:11.786  6532  6572 D BluetoothAdapterService: updateAdapterState state is 12
08-31 16:54:11.786   754  1327 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:54:11.786  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.786  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.786  6444  6444 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-31 16:54:11.796  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.796  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.796  6444  6444 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 16:54:11.796   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88e004d 6714:com.google.android.apps.maps/u0a121}
,08-31 16:54:11.796  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:11.796  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:54:11.806  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:11.806  6444  6444 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:54:11.806  6730  6730 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 16:54:11.806  6730  6730 I dhcpcd  : version 5.5.6 starting
,08-31 16:54:11.806  6730  6730 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 16:54:11.806   754  3296 D SSRM:n  : SIOP:: AP = 390, PST = 327, CUR = 300, LCD = 0
08-31 16:54:11.806  6532  6572 V BluetoothAdapterService: start opp service
,08-31 16:54:11.816  6532  6532 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 16:54:11.816  6532  6532 I BluetoothPbapService: Handler(): got msg=1
,08-31 16:54:11.816   754  1732 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:54:11.816  6532  6572 D BluetoothAdapterService: Autoconnection is available 
08-31 16:54:11.816  6532  6572 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:54:11.816  6532  6572 D BluetoothAdapterService: starting service from this receiver
,08-31 16:54:11.816   754   892 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.816   754   892 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.826  6532  6550 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.826   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{1c75449: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.826  6532  6550 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.826  2104  2161 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.826  2104  2161 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.826  6072  6082 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:54:11.826  6072  6082 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:54:11.826   754   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:54:11.826  2104  2124 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 16:54:11.826  1691  1703 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.826  1691  1703 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.826  1386  2872 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:54:11.826  1386  2872 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:54:11.826   754   892 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:54:11.826  1705  2517 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 16:54:11.826  6532  6572 D BluetoothAdapterService: BT on, init HID DEV count : 0
08-31 16:54:11.826  6532  6572 I BluetoothAdapterState: Entering OnState
08-31 16:54:11.826  1705  2517 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.836  2021  2568 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.836  2021  2568 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.836  1857  2779 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.836  1857  2779 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.836   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{f27ec05: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.836  6532  6733 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:54:11.836   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{ec7345a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.836   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{460e68b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:11.836  6444  6454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.836  6444  6454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.846  6573  6697 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:54:11.846  6573  6697 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:54:11.846  6532  6733 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:54:11.846  6532  6733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:54:11.846   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{e02b368: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.846   754   754 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:11.846   754   754 I InputMethodManagerService: [BT Setting State] State =12
08-31 16:54:11.846   754   754 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 16:54:11.846  1386  1386 D BluetoothTile:  onBluetoothStateChange:
,08-31 16:54:11.846  1386  1386 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 16:54:11.856  1767  1767 D ucsBai_ConnectionManager: BluetoothReceiver Action android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:54:11.856   754   754 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:54:11.856   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
08-31 16:54:11.856   754   754 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState : true
08-31 16:54:11.856   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:11.856   754   754 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,08-31 16:54:11.866  1982  1982 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:54:11.876  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:11.876  6532  6532 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,08-31 16:54:11.876  6532  6532 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-31 16:54:11.876  6532  6532 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
,08-31 16:54:11.876  6532  6532 W System.err: 	at com.android.bluetooth.opp.BluetoothOppService.onCreate(BluetoothOppService.java:195)
08-31 16:54:11.876  6532  6532 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3807)
08-31 16:54:11.876  6532  6532 W System.err: 	at android.app.ActivityThread.access$2100(ActivityThread.java:221)
,08-31 16:54:11.876  6532  6532 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1882)
08-31 16:54:11.876  6532  6532 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:11.876  6532  6532 W System.err: 	at android.os.Looper.loop(Looper.java:158)
,08-31 16:54:11.876  6532  6532 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-31 16:54:11.876  6532  6532 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:11.876  6532  6532 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
,08-31 16:54:11.876  6532  6532 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-31 16:54:11.876  6532  6532 V BtOppService: isOwner == true
,08-31 16:54:11.886  6532  6733 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-31 16:54:11.886  6532  6603 D bt_vendor: op for 7
,08-31 16:54:11.886  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-31 16:54:11.886  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:11.886   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{ab43c26: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.886   754  1713 D StatusBarManagerService: setIcon slot=bluetooth index=18 icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,08-31 16:54:11.886   754   774 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 16:54:11.886  1386  1386 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:11.886  1386  1386 D BluetoothTile:  getBluetoothState : 12
,08-31 16:54:11.886  1386  1386 D PhoneStatusBar: updateIcon slot=bluetooth index=18 viewIndex=3 old=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) user=0 ) icon=StatusBarIcon(icon=Icon(typ=RESOURCE pkg=com.android.systemui id=0x7f0203c9) visible user=0 )
,08-31 16:54:11.886  6714  6714 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.google.android.apps.maps rsrc of package null
,08-31 16:54:11.896   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{4756067: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.896   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{39e14: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.896   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{e868780: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.906   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{990e1b9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.906  1386  2954 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:54:11.906   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{58ca9fe: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.916   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{954b444: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.916   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{c0ad0b0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.926  1386  2954 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:54:11.926   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{450ab29: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.926  6730  6730 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:54:11.926  6730  6730 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-31 16:54:11.926  6730  6730 I dhcpcd  : bssid match
,08-31 16:54:11.926  6730  6730 I dhcpcd  : wlan0: rebinding lease of 192.168.1.123
,08-31 16:54:11.926  1386  2954 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:54:11.936  6714  6714 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 16:54:11.936  6744  6744 E Zygote  : v2
08-31 16:54:11.936  6744  6744 I libpersona: KNOX_SDCARD checking this for 10162
08-31 16:54:11.936  6744  6744 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:11.936  6744  6744 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:11.936  6744  6744 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:11.946  6744  6744 E Zygote  : accessInfo : 0
,08-31 16:54:11.946   754  1732 I ActivityManager: Start proc 6744:com.android.email/u0a162 for content provider com.android.email/.provider.EmailProvider
08-31 16:54:11.946  6744  6744 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.email 
,08-31 16:54:11.946   754  1326 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-31 16:54:11.946   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ccfe7ba: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.946   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{e84c586: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.956   754   754 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@e5b1e47
08-31 16:54:11.956   754   754 D BluetoothHeadset: registerMessageListener
,08-31 16:54:11.956   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{1efb674: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.956  6532  6729 D HeadsetService: registerMessageListener
,08-31 16:54:11.956  6532  6729 D HeadsetService: registerMessageListener
,08-31 16:54:11.956  6532  6701 D HeadsetStateMachine: Disconnected process message: 70, size: 0
08-31 16:54:11.956  6532  6701 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@f9fc8c8
,08-31 16:54:11.956   754   754 I Telecom : BluetoothManager : register MessageListener
08-31 16:54:11.956   754   754 I Telecom : CallAudioManager: onBluetoothStateChange: no focus
08-31 16:54:11.956  6532  6735 D A2dpStateMachine: getConnectedDevices : size=0
,08-31 16:54:11.956   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{e60379d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.956   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{57b412: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.966   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{62157e3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.966   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{18bc5e0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.976   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{a0db099: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.976  6730  6730 I dhcpcd  : wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,08-31 16:54:11.976   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{2f8ff5e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.976   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{2878f3f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.976  6744  6744 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:11.976  6744  6744 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:11.976   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{b17600c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.986   754  1326 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-31 16:54:11.986   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{d7fbd55: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.996   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{fd1b36a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.996   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{eefe05b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.996  6744  6744 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.android.email rsrc of package null
,08-31 16:54:11.996   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{3e070f8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:11.996   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{cbd9d1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.006   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{bcf9c36: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.006   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{c22737: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.006   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{627a4a4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.006   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{de3420d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.016   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{af145c2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.016   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{207ffd3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.016   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{d8c6710: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.016   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{28ef209: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.026  6730  6730 I dhcpcd  : wlan0: leased 192.168.1.123 for 172800 seconds
,08-31 16:54:12.026   754  1335 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:54:12.046   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{91fc0e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.046   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{9c8c62f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.046   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{e38e43c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.046   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{62ba5c5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.056   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{875cb1a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.056   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{e25964b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.056   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{2ce0828: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.056   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{f25d941: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.066   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{4957ee6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.066   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{c354c27: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.066   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d0f7ed4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.066   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{435c87d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.076   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{baaa372: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.076   754  1717 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:54:12.086   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{1a083c3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.086   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{54fb440: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.086   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{55b6f79: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.096   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{47b84be: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.096   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{3fd991f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.096   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{49bd46c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.096   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{89a8a35: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.106   754  1713 D RCPManagerService: exchangeData() failure , invalid userId
08-31 16:54:12.106   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{9e72eca: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.106   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{1eca83b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.106   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{5a7cb58: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.106   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{67694b1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.116  6532  6693 D bt_upio : ..proc_btwrite_timeout..
08-31 16:54:12.116  6532  6693 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-31 16:54:12.116   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{3b16d96: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.116   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{9f38d17: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.116   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{87a4504: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.116   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{22ecaed: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.126   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{ecd22: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.126   754  1414 D RCPManagerService: exchangeData() failure , invalid userId
08-31 16:54:12.126   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{9f0996e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.126   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{345080f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.126   754  1676 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:54:12.126   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{773309c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.136   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{9836aa5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.136   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{810de7a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.146   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{f54162b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.146   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{5d0ba88: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.146   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{fe50c21: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.156   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{be6846: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.156   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{fbea07: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.166   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{4faf734: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.166   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{c65495d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.166   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{e68c2d2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.176   754  1590 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:54:12.176   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{e631fa3: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.186  6777  6777 E Zygote  : v2
08-31 16:54:12.186  6777  6777 I libpersona: KNOX_SDCARD checking this for 10077
08-31 16:54:12.186  6777  6777 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:12.186  6777  6777 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:12.186  6777  6777 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:12.186  6777  6777 E Zygote  : accessInfo : 0
08-31 16:54:12.186  6777  6777 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,08-31 16:54:12.196   754  1737 I ActivityManager: Start proc 6777:com.sec.android.provider.badge/u0a77 for content provider com.sec.android.provider.badge/.BadgeProvider
,08-31 16:54:12.196   754  1414 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:54:12.196   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{eea52a0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.196   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{6b21e59: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.206   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{ec3a1e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.206   754  1732 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:54:12.206   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{f7e12ff: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.206   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{2b1f8cc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.206   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{95d4715: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.216   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{79dda2a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.216   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{d2ae01b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.216   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{b6bd5b8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.216   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{c583f91: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.226   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{176ef6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.236   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{9e49564: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.236  6777  6777 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:12.236  6777  6777 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:12.256   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{b3043cd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.276  6532  6532 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,08-31 16:54:12.276   754  1717 I ActivityManager: Killing 5463:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-31 16:54:12.276  6532  6799 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:54:12.276  6532  6799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:54:12.286   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{5c38482: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.286  6532  6532 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:54:12.286  6532  6532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:54:12.286  6532  6532 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:54:12.286   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{52b3793: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.286  6532  6532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:54:12.286  6532  6603 D bt_vendor: op for 7
08-31 16:54:12.286  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-31 16:54:12.286  6532  6603 D bt_upio : upio_start_stop_timer : timer_settime success
08-31 16:54:12.286  6532  6603 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-31 16:54:12.286  6532  6799 I BtOppRfcommListener: Accept thread started.
08-31 16:54:12.286  6532  6807 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:54:12.286  6532  6807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:54:12.286  6532  6532 D ObexServerSockets: Succeed to create listening sockets 
08-31 16:54:12.286  6532  6532 D ObexServerSockets: startAccept()
,08-31 16:54:12.286  6532  6807 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,08-31 16:54:12.286  6532  6603 D bt_vendor: op for 7
08-31 16:54:12.286  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:12.286  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:12.296  6532  6807 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 16:54:12.296  6532  6811 D ObexServerSockets: Accepting socket connection for masId0
08-31 16:54:12.296  6532  6810 D ObexServerSockets: Accepting socket connection for masId0
,08-31 16:54:12.296  6532  6532 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 16:54:12.296  6532  6532 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 16:54:12.296  6532  6532 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-31 16:54:12.296  6532  6603 D bt_vendor: op for 7
08-31 16:54:12.296  6532  6603 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-31 16:54:12.296  6532  6603 D bt_upio : BT_WAKE is asserted already
,08-31 16:54:12.296   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{d07a3d0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.296   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{30a4fc9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.306   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{e2966ce: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.306   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{647b9ef: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.306   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{50b2cfc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.306   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{45f1f85: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.316   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{df921da: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.316   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{400060b: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.316   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{d5c1ce8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.316   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{4772f01: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.326   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{2d781a6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.326   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{ba6f7e7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.326   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{94a1f94: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.326   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{aa6ba3d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.336   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{dea1232: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.336  6532  6774 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
08-31 16:54:12.336  6532  6774 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-31 16:54:12.336  6532  6774 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
08-31 16:54:12.336  6532  6774 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,08-31 16:54:12.336   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{2e12b83: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.346   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-31 16:54:12.356   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{f73a100: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.356  6777  6777 W ResourcesManager: getTopLevelResources: /system/priv-app/BadgeProvider_M/BadgeProvider_M.apk / 1.0 running in com.sec.android.provider.badge rsrc of package null
,08-31 16:54:12.356   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{549bd39: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.356   754  1298 I ActivityManager: Killing 5280:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-31 16:54:12.366   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{b231f7e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.366   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{b00fcdf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.366   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{ff1cd2c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.376   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{27ff3f5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.376   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{14db58a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.376   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{e2287fb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.386  6777  6777 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_M/lib/arm
,08-31 16:54:12.386   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{1449018: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.386   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{6d9a056: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.396  6777  6777 D BadgeProvider: onCreate
,08-31 16:54:12.396  6777  6777 D BadgeProvider: DatabaseHelper
,08-31 16:54:12.396   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-31 16:54:12.406   754  1328 E WifiNative-wlan0: do suspend true
,08-31 16:54:12.406   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{ffe95c4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.416   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{a9facad: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.416   754  1327 D WifiP2pService: InactiveState{ what=143375 }
,08-31 16:54:12.416   754  1327 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:54:12.426   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{7676be2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.426   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{cb3fb73: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.426  6777  6794 D BaseReflect: null getOwnClass TEST
08-31 16:54:12.426   754  1335 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,08-31 16:54:12.426  6777  6794 D MethodReflector: android.content.ContentResolver getClass TEST
08-31 16:54:12.426  6777  6794 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,08-31 16:54:12.426  6777  6794 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,08-31 16:54:12.426   754  1328 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 16:54:12.426   754  1328 D WifiStateMachine: VerifyingLinkState enter
08-31 16:54:12.426   754  1335 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:12.426  6777  6794 D MethodReflector: notifyChange is called
,08-31 16:54:12.436  1721  1721 D Launcher.Model: reloadBadges entered.
,08-31 16:54:12.436   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d314a30: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.436   754  1335 E ConnectivityService: updateNetworkInfo()
,08-31 16:54:12.436   754  1335 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 16:54:12.436   754  1335 D ConnectivityService: Adding iface wlan0 to network 502
,08-31 16:54:12.436  6777  6794 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,08-31 16:54:12.436  6777  6794 D BadgeProvider: sendNotify, [notify] : null
08-31 16:54:12.436  6777  6794 D BadgeProvider: update, getCallingPackage() : com.android.email
08-31 16:54:12.436  6777  6794 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
,08-31 16:54:12.436  6777  6794 D BadgeProvider: update, [uri.query] : null
08-31 16:54:12.436  6777  6794 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 16:54:12.436  1721  1721 D Launcher.Model: reloadBadges entered.
,08-31 16:54:12.436  6777  6794 D BadgeProvider: update, [UpdateCount] : 1
,08-31 16:54:12.446   754   754 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
08-31 16:54:12.446   754   754 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.446   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
08-31 16:54:12.446   754   768 I art     : Background partial concurrent mark sweep GC freed 76791(5MB) AllocSpace objects, 25(496KB) LOS objects, 27% free, 42MB/58MB, paused 1.936ms total 179.324ms
,08-31 16:54:12.446   754  1347 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 16:54:12.446   754  1347 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:54:12.446   754  1347 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:54:12.446   754  1347 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:54:12.446   754  1347 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:54:12.456   754  1328 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:54:12.456   754  1333 I WifiHs20Service: Message received 5007
,08-31 16:54:12.456   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{3b766a9: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.466   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{614642e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.466   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{6c8dbcf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.466   754  1347 I WifiManager: isCaptivePortalException
,08-31 16:54:12.466   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{798d95c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.466   754  1347 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,08-31 16:54:12.466   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{776c465: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.466   754  1347 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,08-31 16:54:12.476   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{886953a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.476   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{7a165eb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.476   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{b882f48: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.476   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{11441e1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.486   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{6b8cb06: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.486   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{72e75c7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.486   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{594f7f4: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.486   754  1347 D WifiWatchdogStateMachine: 3Captive portal check should be processed whether SNS option is on or off.
,08-31 16:54:12.486   754  1347 D WifiWatchdogStateMachine.CaptivePortalHandler: [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {eb21b1d}
08-31 16:54:12.486   754  1347 I WifiManager: isCaptivePortalException
,08-31 16:54:12.486   754  1347 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,08-31 16:54:12.486   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{b869192: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.496   754  1347 D WifiStateMachine: isPackageRunning - top:com.test.thalitest.MainActivity
,08-31 16:54:12.496   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{192a763: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.496   754  1335 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,08-31 16:54:12.496   754  1335 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,08-31 16:54:12.496   754  1335 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,08-31 16:54:12.496   754  1328 D WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to CONNECTED
,08-31 16:54:12.496   754  1335 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:54:12.496   754  1335 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,08-31 16:54:12.506   754  1335 V NetworkStats: updateIfacesLocked()
08-31 16:54:12.506   754  1335 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:54:12.506   754  1335 V NetworkStats: performPollLocked() took 2ms
,08-31 16:54:12.506   754  1328 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:54:12.506   754  1328 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:54:12.536  6777  6794 D BadgeProvider: query, [selection] : null
,08-31 16:54:12.556  1386  1386 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02061d/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f02017c/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:54:12.556  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:12.556  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:12.556  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:12.556  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:12.556   754   754 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 16:54:12.556   754   754 I WifiTrafficPoller: mBoosterFLAG : 0
,08-31 16:54:12.556   754   754 I WifiTrafficPoller: current booster mode : FullMode
08-31 16:54:12.556   754   754 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-31 16:54:12.556  6549  6549 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 16:54:12.556  6549  6549 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-31 16:54:12.566   754   754 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,08-31 16:54:12.566   754   754 D HS20StateMachine: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:54:12.566   754   754 D HS20StateMachine: SSID : "NG700"
08-31 16:54:12.566  6714  6779 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/testdata
,08-31 16:54:12.566   754   754 D HS20StateMachine: NetId : 0
08-31 16:54:12.566  6714  6779 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.maps/app_/testdata
,08-31 16:54:12.566   754   754 D HS20StateMachine: checkifOSUAP  null
,08-31 16:54:12.566   754   754 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,08-31 16:54:12.566   754  1333 I WifiHs20Service: Message received 5007
,08-31 16:54:12.566  6549  6549 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 16:54:12.566   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.566   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:12.566   754  1326 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:54:12.576   754  1335 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.576   754  1335 D ConnectivityService: Not required to send intent.
08-31 16:54:12.576   754  1335 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-31 16:54:12.576   754  1335 E ConnectivityService: updateNetworkInfo()
08-31 16:54:12.576   754  1335 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:12.576   754  1335 V NetworkStats: updateIfacesLocked()
08-31 16:54:12.576   754  1335 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:54:12.576   754  1335 V NetworkStats: performPollLocked() took 2ms
,08-31 16:54:12.576   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{45a4c19: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.576   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.576   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:12.576   754  6710 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:54:12.576   754  6710 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Connected
,08-31 16:54:12.576   754  1335 D ConnectivityService: scheduleUnvalidatedPrompt 502
08-31 16:54:12.576   754  1335 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.576   754  1335 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.576   754  1328 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 16:54:12.576   754  1335 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:54:12.576   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: true
,08-31 16:54:12.576   754  6710 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:54:12.576   754  6710 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: Validated
08-31 16:54:12.576   754  1328 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 16:54:12.576   754  1326 D NtpTrustedTime: forceRefresh: no connectivity
,08-31 16:54:12.576   754  1335 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:54:12.586   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{1f834de: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.586   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{87e56bf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.586   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{2f3518c: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.596  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:54:12.596  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,08-31 16:54:12.596   754  1335 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
08-31 16:54:12.596   754  1335 D ConnectivityService: currentScore = 0, newScore = 20
08-31 16:54:12.596   754  1335 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.596   754  1335 D ConnectivityService:    accepting network in place of null
,08-31 16:54:12.596   754  1335 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1327 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 16:54:12.596   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-31 16:54:12.596   754  1327 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.596   754  1335 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:54:12.596   754  1327 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:54:12.596   754  1327 D WIFI_P2P: evalRequest
08-31 16:54:12.596   754  1328 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1328 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.596   754  1328 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.596   754  1328 D WIFI    : evalRequest
08-31 16:54:12.596   754  1328 D WIFI    :   done
08-31 16:54:12.596   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{2ba90d5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.596   754  1328 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1328 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.596   754  1328 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.596   754  1328 D WIFI    : evalRequest
08-31 16:54:12.596   754  1328 D WIFI    :   done
08-31 16:54:12.596   754  1328 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1328 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.596   754  1328 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.596   754  1328 D WIFI_UT : evalRequest
08-31 16:54:12.596   754  1328 D WIFI_UT :   done
08-31 16:54:12.596   754  1356 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.596   754  1356 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
08-31 16:54:12.596   754  1356 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:,54:12.596   754  1356 D Ethernet: evalRequest
08-31 16:54:12.596   754  1356 D Ethernet:   done
08-31 16:54:12.596   754  1327 D WIFI_P2P:   done
08-31 16:54:12.596   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{b4ec0ea: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.606   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{e4b9fdb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.606   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{f49fa78: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.606   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{da06551: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.606   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{9d001b6: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.616   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{6da5eb7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.616   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{c604624: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.616  6777  6794 D BadgeProvider: query, [selection] : null
08-31 16:54:12.616   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{e35058d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.616   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{c528342: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.626   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{a2c2f53: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.626   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{86da090: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.626   308  1190 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 16:54:12.626   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{cf96d89: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.636  6714  6779 W System.err: mkdir failed: EEXIST (File exists) : /storage/emulated/0/Android/data/com.google.android.apps.maps/cache
,08-31 16:54:12.636   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{689918e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.646   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{4c06daf: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.646   308  1190 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 16:54:12.646   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{bb435bc: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.646   754  1335 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,08-31 16:54:12.656   754   892 D EntConnectivity: Not allowed due to - mEnabled false
,08-31 16:54:12.656   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{f825945: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.656   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{211389a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.656   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{1b035cb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.656   754  1335 D ConnectivityService: updateTcpDelayedAckSetting - WiFi setting
08-31 16:54:12.656   754  1335 D ConnectivityService: Setting TCP values: [1] which comes from [net.tcp.usercfg.wifi]
,08-31 16:54:12.656   754  1335 D ConnectivityService: Setting TCP values: [20] which comes from [net.tcp.delack.wifi]
,08-31 16:54:12.656   754  1704 V AlarmManager:  remove PendingIntent] PendingIntent{e6cf1a8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.666   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{5f444c1: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.666   754  1335 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.666   754  1335 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.666   754  1335 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.666   754  1335 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.666   754  1335 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.666   754  1335 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} } for legacy network type 1
08-31 16:54:12.666   754  1335 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,08-31 16:54:12.666   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{43a4466: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.666   754  1335 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:12.676   754   892 D EntConnectivity: Not allowed due to - mEnabled false
,08-31 16:54:12.676   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{a8a63a7: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.676   754  1717 D ConnectivityService: getVpnConfig > userId : 0
,08-31 16:54:12.676   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{1738054: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.676   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{43f6bfd: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.676   754  1326 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: updateDataNetType()
08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-31 16:54:12.686   308  1186 D EnterpriseController: netId is 0
08-31 16:54:12.686   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:54:12.686   754   754 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.686   754  1335 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:12.686   754  1335 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:54:12.686   754  1335 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/754 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.686   754  1335 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.686   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.686   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.686   754   826 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 16:54:12.686   754   826 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.686   754   754 D Tethering: Tethering got CONNECTIVITY_ACTION
,08-31 16:54:12.686   754   892 D Tethering: MasterInitialState.processMessage what=3
08-31 16:54:12.686   754  1335 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 16:54:12.686   754   754 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:54:12.686  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,08-31 16:54:12.686   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.696   754  1336 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,08-31 16:54:12.696  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:54:12.696  1705  1720 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
08-31 16:54:12.696   754  1336 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,08-31 16:54:12.696   754  1335 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [] ]
08-31 16:54:12.696   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.696   754   754 V MARsPolicyManager: DataConnection: true
,08-31 16:54:12.696   754  1335 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.696   754  1648 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:54:12.696   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.696   754  1335 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.696   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.696   308  1186 D EnterpriseController: netId is 0
08-31 16:54:12.696   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-31 16:54:12.696   754  1732 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.696  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 16:54:12.696   754  1335 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.706   754  1335 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 16:54:12.706   754  1335 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] validation  passed
,08-31 16:54:12.706   754  1676 V AlarmManager:  remove PendingIntent] PendingIntent{49640f2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.706   754  1335 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45], newCap = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
08-31 16:54:12.706   754  1335 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:54:12.706   754  1335 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:12.706   754  1335 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-31 16:54:12.706  6444  6444 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-31 16:54:12.706   754  1335 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-31 16:54:12.706   754  1335 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:12.706   754  1335 D ConnectivityService: unneeded: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 16:54:12.706   754  1335 D ConnectivityService: unneeded: NetworkRequestInfo for = Request from uid/pid:1000/754 for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.706   754  1335 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.706  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-31 16:54:12.706   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.706   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
08-31 16:54:12.716   754  1335 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.716   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{8ef9343: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.716   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.716   754  1335 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.716   754  1335 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.716   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{5b24dc0: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.716   754  1335 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.716   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{31bcaf9: PendingIntentRecord{d8775dc com.google.android.gms broadcastIntent}}
,08-31 16:54:12.726   754  1356 D Ethernet: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.726   754  1356 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
08-31 16:54:12.726   754  1356 D Ethernet: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:54:12.726   754  1356 D Ethernet: evalRequest
08-31 16:54:12.726   754  1356 D Ethernet:   done
08-31 16:54:12.726   754  1328 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.726   754  1328 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.726   754  1328 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.726   754  1328 D WIFI    : evalRequest
08-31 16:54:12.726   754  1328 D WIFI    :   done
08-31 16:54:12.726   754  1328 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.726   754  1328 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.726   754  1328 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.726   754  1328 D WIFI    : evalRequest
08-31 16:54:12.726   754  1328 D WIFI    :   done
,08-31 16:54:12.726   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{437a3e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.726   754  1335 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 16:54:12.726   754  1327 D WIFI_P2P: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.726   754  1328 D WIFI_UT : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.726   754  1327 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.726   754  1328 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:54:12.726   754  1328 D WIFI_UT : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 16:54:12.726   754  1327 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 16:54:12.726   754  1328 D WIFI_UT : evalRequest
08-31 16:54:12.726   754  1327 D WIFI_P2P: evalRequest
,08-31 16:54:12.726   754  1328 D WIFI_UT :   done
08-31 16:54:12.726   754  1327 D WIFI_P2P:   done
,08-31 16:54:12.726   754  1335 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,08-31 16:54:12.726   754  1328 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(VALID)
08-31 16:54:12.726   754  1328 D WifiNetworkAgent: NetworkAgent: CMD_REPORT_NETWORK_STATUS(1)
,08-31 16:54:12.726  1386  1386 D StatusBar.NetworkController: EthernetConnected: false
08-31 16:54:12.726  1386  1386 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:54:12.726  1386  1386 D StatusBar.NetworkController: updateDataNetType()
08-31 16:54:12.726  1386  1386 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-31 16:54:12.736   754  1335 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:54:12.736   754  1335 D ConnectivityService: identical MTU - not setting
,08-31 16:54:12.736   754  1335 V NetworkStats: updateIfacesLocked()
,08-31 16:54:12.736   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{5ee209f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.736   754  1335 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:54:12.736  6573  6573 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-31 16:54:12.736  6444  6444 D BluetoothAdapter: STATE_ON
08-31 16:54:12.736  1386  1386 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 16:54:12.736  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,08-31 16:54:12.736  1386  1386 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 16:54:12.736   754  1335 V NetworkStats: performPollLocked() took 6ms
,08-31 16:54:12.746   754  1713 V AlarmManager:  remove PendingIntent] PendingIntent{e4e85ec: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:54:12.746  6444  6444 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 16:54:12.746  6444  6444 D BluetoothAdapter: STATE_ON
,08-31 16:54:12.746  6444  6444 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 16:54:12.746   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:12.746   754  1335 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
,08-31 16:54:12.746   754  1335 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
08-31 16:54:12.746  4288  4288 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(89/llllIIIllIlIIIIllllI)] WiFi Network is connected
08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService: Not required to send intent.
08-31 16:54:12.746   754  1335 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.746   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.746   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.756  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llllIIIllIlIIIIllllI(233/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,08-31 16:54:12.756   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.756   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [] ]
,08-31 16:54:12.756   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{4c51db5: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
08-31 16:54:12.756   754   774 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.756   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.756   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.756  4288  4353 I FOTA_AGENT: [IIIIlIlllIIIlIIlIlIl(213/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
08-31 16:54:12.756   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.756   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:12.756   754  1335 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.756   754  1335 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:12.756   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{5f8fc4a: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.766   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{31e27bb: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.766   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{99414d8: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.766   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{976e031: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.776   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{97d8497: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.776   754   826 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-31 16:54:12.786   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{ca1a684: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.796   754   774 V AlarmManager:  remove PendingIntent] PendingIntent{fa84e6d: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.796   754   826 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-31 16:54:12.796   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{7dccaa2: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.796   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{a0bd333: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.806  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(483/llllllIllIlIlllIIlIl)] Check completed.
,08-31 16:54:12.816   754  1298 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:12.816  4288  4353 I FOTA_AGENT: [lIlIIlIlIlIllllllIII(89/llllIIIllIlIIIIllllI)] WiFi Network is connected
,08-31 16:54:12.816   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{c086469: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.816   754  1351 D WifiWatchdogStateMachine.CaptivePortalHandler: start check captive portal 
,08-31 16:54:12.816   754  2180 V AlarmManager:  remove PendingIntent] PendingIntent{60eeee: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:12.816  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(100/lllIlIlIIIllIIlIllIl)] xdmInitAdpEXTInit
,08-31 16:54:12.816   754  1326 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472655253336 mCachedNtpElapsedRealtime : 308396 mCachedNtpCertainty : 7
,08-31 16:54:12.816   754  1648 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472655253336 mCachedNtpElapsedRealtime : 308396 mCachedNtpCertainty : 7
08-31 16:54:12.816   754  1648 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:54:12.826   754  1648 D AlarmManager: setTime : 1472655253337 calling from uid: 1000 pid :754
,08-31 16:54:12.826   754  1648 D AlarmManagerService: Setting time of day to sec=1472655253
,08-31 16:54:12.826   754  1648 D AlarmManagerService: Trying to open a file
08-31 16:54:12.826   754  1648 E AlarmManagerService: File Open Failed
,08-31 16:54:13.337   754  1648 W AlarmManagerService: Unable to set rtc to 1472655253: Invalid argument
,08-31 16:54:13.337   754  1236 V AlarmManager: Expired Alarm result :65536
08-31 16:54:13.337   754  1648 V AlarmManager:  remove PendingIntent] PendingIntent{e52c734: PendingIntentRecord{828d95d android broadcastIntent}}
,08-31 16:54:13.337   754  1732 V AlarmManager:  remove PendingIntent] PendingIntent{c266f8f: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:13.337  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(452/llIIllllIIlllIIIIlll)] xdmInitAdpChangeDeviceID
,08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:54:13.337   754  1326 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:54:13.337   754  1326 D ConnectivityService: getAllNetworkState networkCapability  = [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]
08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:54:13.337   754  1326 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 16:54:13.337   754  1326 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:54:13.337  1386  1386 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:54:13.337  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:13.347   754   754 I CAE     : handleMessage(CaTimeChangeManager.java:159) - Time Change, auto old:true new:true
,08-31 16:54:13.347  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:13.347  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:54:13.347  1386  1386 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:54:13.347   754   754 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472655253357
,08-31 16:54:13.347   754   754 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-31 16:54:13.357   754   754 V MARsPolicyManager: updateDBResetTimeForTimeChanged -- SystemTime Changed : 504
08-31 16:54:13.357   754   754 V MARsPolicyManager: SystemTime Changed Less than 30 min, didn't care!!
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionTIME_SET
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
08-31 16:54:13.357   754   754 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> SM:1417 [0:0] setClockLayoutContent
,08-31 16:54:13.357  2319  2319 D accuweather: [KK AccuPhone]>>> U:850 [0:0] Locale format : MMM d, y
,08-31 16:54:13.357   754   754 W System.err: java.io.FileNotFoundException: /data/drm/beforeTime.ini: open failed: EACCES (Permission denied)
,08-31 16:54:13.367  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,08-31 16:54:13.367  1386  1386 I PERF    : received broadcast android.intent.action.TIME_SET
,08-31 16:54:13.367   754   754 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:452)
,08-31 16:54:13.367   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77280dc 2021:com.google.android.gms.persistent/u0a11}
08-31 16:54:13.367   754   754 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:54:13.367   754   754 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
,08-31 16:54:13.367   754   754 W System.err: 	at java.io.FileReader.<init>(FileReader.java:66)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.DrmEventService.getBeforeTime(DrmEventService.java:280)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.DrmEventService.handleUserUpdatedTimeUpdation(DrmEventService.java:372)
,08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.DrmEventService.userUpdateHandler(DrmEventService.java:262)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.DrmEventService.access$200(DrmEventService.java:49)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.DrmEventService$3.onReceive(DrmEventService.java:413)
08-31 16:54:13.367   754   754 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:993)
,08-31 16:54:13.367   754   754 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 16:54:13.367   754   754 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 16:54:13.367   754   754 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:508)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:363)
,08-31 16:54:13.367   754   754 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:54:13.367   754   754 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 16:54:13.367   754   754 W System.err: Caused by: android.system.ErrnoException: open failed: EACCES (Permission denied)
,08-31 16:54:13.367   754   754 W System.err: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:13.367   754   754 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:13.367   754   754 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:13.367   754   754 W System.err: 	... 17 more
,08-31 16:54:13.367   754   754 I DrmEventService: handleUserUpdatedTimeUpdation beforeTime -100
,08-31 16:54:13.367   754  1236 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=308401 batch.start=355063
,08-31 16:54:13.377  6444  6514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:54:13.377  6444  6514 I jxcore-log: 
,08-31 16:54:13.377  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(465/IIIIllIlIIlIIIIlllIl)] xdmInitAdpChangeSalesCode
,08-31 16:54:13.397  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.397  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 16:54:13.407  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 16:54:13.407  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 16:54:13.407  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.417  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-31 16:54:13.427   754   826 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-31 16:54:13.427  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(468/IIIIllIlIIlIIIIlllIl)] szDevSalesCode = XEO
,08-31 16:54:13.437  2021  2021 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,08-31 16:54:13.437  2021  2021 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:54:13.437  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(469/IIIIllIlIIlIIIIlllIl)] szDbSalesCode = XEO
,08-31 16:54:13.447  4288  4353 I FOTA_AGENT: [IIllIIIlIllIIIllIIlI(90/llllIIIllIlIIIIllllI)] 
,08-31 16:54:13.447  6744  6776 D skia    : ---- fAsset->read(0) returned 0
,08-31 16:54:13.447  6744  6776 D skia    : ---- fAsset->read(0) returned 0
,08-31 16:54:13.457  6714  6796 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 16:54:13.457  4288  4353 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(3735/lllIIIIllIlIlllllllI)] FUMO_Status : 50
,08-31 16:54:13.457   754  1298 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7670639 u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77280dc 2021:com.google.android.gms.persistent/u0a11}
,08-31 16:54:13.467   754  1496 V AlarmManager:  remove PendingIntent] PendingIntent{9b6a4c: PendingIntentRecord{d8775dc com.google.android.gms broadcastIntent}}
,08-31 16:54:13.477  4288  4353 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5688/lIlIIIlllIlIlIlIIIll)] Get Postpone status : 0
,08-31 16:54:13.487   754  1351 D WifiWatchdogStateMachine.CaptivePortalHandler: result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,08-31 16:54:13.487  4288  4353 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(6445/llllIlllIIIlIlIlIIII)] Initiated Type: 2
,08-31 16:54:13.487  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(123/lllIlIlIIIllIIlIllIl)] nStatus [50]
,08-31 16:54:13.507  4288  4353 I FOTA_AGENT: [llllIllIllIIIllllIIl(278/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,08-31 16:54:13.507  4288  4354 I FOTA_AGENT: [IlIlIlllIIlllIlIlIIl(816/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,08-31 16:54:13.507  4288  4354 I FOTA_AGENT: [lllIllIIlIIllllIIlIl(51/llIIIIlllllIIllIIllI)] 
,08-31 16:54:13.517  4288  4354 I FOTA_AGENT: [lllllllIlIllIIlllIIl(52/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:30928561
,08-31 16:54:13.517  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.llllIIIllIlIIIIllllI(277/llIlIIIIlIIIIIlIlIII)] 
08-31 16:54:13.517  4288  4353 I FOTA_AGENT: [IIIIlIlllIIIlIIlIlIl(265/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,08-31 16:54:13.527  4288  4353 I FOTA_AGENT: [IIIIlIlllIIIlIIlIlIl(1979/llllIIIllIlIIIIllllI)] 
,08-31 16:54:13.527  4288  4353 I FOTA_AGENT: [com.samsung.android.app.syncmldm.DMSecBroadcastReceiver(580/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,08-31 16:54:13.537   754   826 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,08-31 16:54:13.537  4288  4353 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.llllIIIllIlIIIIllllI(571/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,08-31 16:54:13.537  4115  6840 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-31 16:54:13.537  4115  6840 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 16:54:13.547  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5387/IIlIIIlllllIIlIIIlII)] Data Margin : 500
,08-31 16:54:13.567  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5507/llIIlIIlIllIllIlllII)] Data App Weight : 0.0
,08-31 16:54:13.567   754  3329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:54:13.577  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.llllIIIllIlIIIIllllI(201/llIIIIlllllIIllIIllI)] ### Need free space for install - data margin: 524288000, app margin: 0, sum:524288000
,08-31 16:54:13.577  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.llllIIIllIlIIIIllllI(291/llIlIIIIlIIIIIlIlIII)] ### need : 524288000, now has : 10294165504... Memory SUFFICIENT...
,08-31 16:54:13.577  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llIIllllIIlllIIIIlll(1358/handleMessage)] event ->220
,08-31 16:54:13.587  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(662/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,08-31 16:54:13.587  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(744/IlIlIlIIIIIllllIlIIl)] xdmCallUiFotaInstall
08-31 16:54:13.587  6532  6693 D bt_upio : ..proc_btwrite_timeout..
08-31 16:54:13.587  6532  6693 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-31 16:54:13.597  1705  1716 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 phoneId=0
08-31 16:54:13.597  1705  1716 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=2147483643 retVal=true
,08-31 16:54:13.597   754   826 D TelephonyManager: getDataEnabled: retVal=true
,08-31 16:54:13.597  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5147/lIIllllllIlllllIlIIl)] Get Autoinstall status : false
,08-31 16:54:13.597  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5153/IIIIllIlIIlIIIIlllIl)] Set Autoinstall status : false
,08-31 16:54:13.607  1705  1720 D TelephonyProvider: query: url=content://telephony/carriers/preferapn, projectionIn=[Ljava.lang.String;@2df4fe9, selection=nullselectionArgs=null, sort=name ASC
08-31 16:54:13.607  2021  2021 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,08-31 16:54:13.607  1705  1720 D TelephonyProvider: query: match = 5
,08-31 16:54:13.617   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cbba80 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
,08-31 16:54:13.627   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
,08-31 16:54:13.637  1705  1720 D TelephonyProvider: query: selection modified to edited!=2 and edited!=3 and edited!=5 and edited!=6
,08-31 16:54:13.637  4288  4354 I FOTA_AGENT: [IlIlIlllIIlllIlIlIIl(747/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
08-31 16:54:13.637  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(477/lllIIIlllIllIlIllIIl)] 
,08-31 16:54:13.637  4288  4288 E FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(485/lllIIIlllIllIlIllIIl)] didn't register
,08-31 16:54:13.637   754  1704 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:13.637  4288  4288 E FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(486/lllIIIlllIllIlIllIIl)] java.lang.IllegalArgumentException: Receiver not registered: com.samsung.android.app.syncmldm.llIIIIlllllIIllIIllI@8e59d61
,08-31 16:54:13.637  2738  2738 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:54:13.637  2738  2738 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 16:54:13.637   754  1676 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:13.637  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 16:54:13.647   754  2180 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:13.647  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:54:13.647  2738  2738 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,08-31 16:54:13.647  2738  2738 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:54:13.657   754   826 E GpsLocationProvider: No APN found to select.
,08-31 16:54:13.657  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(672/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-31 16:54:13.657   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ea5d84 6573:tv.peel.smartremote/u0a170}
,08-31 16:54:13.667   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:13.667  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5347/IlIllIIIIllllllIlIIl)] Get Priority : 0
,08-31 16:54:13.677   754   775 V AlarmManager:  remove PendingIntent] PendingIntent{485045f: PendingIntentRecord{d8775dc com.google.android.gms broadcastIntent}}
,08-31 16:54:13.677  6532  6845 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.samsung.android.qconnect
,08-31 16:54:13.677  6532  6845 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-31 16:54:13.687  6532  6845 W System.err: 	at com.samsung.android.qconnect.adapter.FileShareUiAdapter.isSupportedCommonUi(FileShareUiAdapter.java:36)
08-31 16:54:13.687  6532  6845 W System.err: 	at com.android.bluetooth.opp.BluetoothOppNotification$NotificationUpdateThread.run(BluetoothOppNotification.java:250)
,08-31 16:54:13.687  2738  2738 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:54:13.687  6846  6846 E Zygote  : v2
08-31 16:54:13.687  6846  6846 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:13.687  6846  6846 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:13.687  6846  6846 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:13.687  6846  6846 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:13.687  6846  6846 E Zygote  : accessInfo : 0
,08-31 16:54:13.687   754   846 I ActivityManager: Start proc 6846:com.sec.android.diagmonagent/1000 for broadcast-5 com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,08-31 16:54:13.707   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8ed2104 2104:com.samsung.android.providers.context/u0a174}
,08-31 16:54:13.707  2738  2738 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
08-31 16:54:13.707  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5187/lIIIIIIIlllllllIIlll)] Get Force status : 0
,08-31 16:54:13.717  2738  2738 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,08-31 16:54:13.717  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:13.717  6846  6846 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:13.717  2738  2738 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,08-31 16:54:13.727  4288  4354 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5147/lIIllllllIlllllIlIIl)] Get Autoinstall status : false
,08-31 16:54:13.727  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(780/IlIlIlIlIlIIlllllIlI)] UI_id:223
,08-31 16:54:13.727  4288  4288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:720 android.content.ContextWrapper.startActivity:345 com.samsung.android.app.syncmldm.XDMService.IlIlIlIlIlIIlllllIlI:786 com.samsung.android.app.syncmldm.XDMService.llIIllllIIlllIIIIlll:87 com.samsung.android.app.syncmldm.llIIllllIIlllIIIIlll.handleMessage:1201 
,08-31 16:54:13.727  4288  4288 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:732 android.app.ContextImpl.startActivity:721 android.content.ContextWrapper.startActivity:345 com.samsung.android.app.syncmldm.XDMService.IlIlIlIlIlIIlllllIlI:786 com.samsung.android.app.syncmldm.XDMService.llIIllllIIlllIIIIlll:87 
08-31 16:54:13.727  4288  4288 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:308808
,08-31 16:54:13.737   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c789e4d 1857:com.sec.android.app.shealth:remote/u0a34}
,08-31 16:54:13.747   754  1737 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.MessageCompose newState = 1 callingPackage = 10162
,08-31 16:54:13.747   754  1590 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.activity.AccountShortcutPicker newState = 2 callingPackage = 10162
,08-31 16:54:13.747   754  1496 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8152057 6846:com.sec.android.diagmonagent/1000}
,08-31 16:54:13.757   754  1713 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.MailService newState = 2 callingPackage = 10162
08-31 16:54:13.757   754  1732 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in null rsrc of package null
,08-31 16:54:13.757   754  1414 D PackageManager: setEnabledSetting : userId = 0 packageName = com.android.email cmp = com.android.email.service.AttachmentDownloadService newState = 2 callingPackage = 10162
,08-31 16:54:13.767   754  1732 D ActivityManager: mDVFSHelper.acquire()
,08-31 16:54:13.767   754  1732 V WindowManager: addAppToken: AppWindowToken{c2ee962 token=Token{f08b02d ActivityRecord{b237744 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIDialogActivity t169}}} to stack=1 task=169 at 0
,08-31 16:54:13.767   754  1732 D ActivityManager:  Launching com.wssyncmldm, updated priority
,08-31 16:54:13.767  6846  6846 W ResourcesManager: getTopLevelResources: /system/priv-app/DiagMonAgent/DiagMonAgent.apk / 1.0 running in com.sec.android.diagmonagent rsrc of package null
,08-31 16:54:13.777   754   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.wssyncmldm
,08-31 16:54:13.787  6846  6846 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm
,08-31 16:54:13.787   754  1732 D InputDispatcher: Focused application set to: xxxx
,08-31 16:54:13.787   754  1732 D InputDispatcher: Focus left window: 6444
,08-31 16:54:13.787   754   893 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
,08-31 16:54:13.787   754   893 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:54:13.787  4288  4288 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
08-31 16:54:13.787   754   893 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
08-31 16:54:13.787   754   893 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 16:54:13.797  4288  4288 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,08-31 16:54:13.797   754  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:13.797   754  1704 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 16:54:13.797  2738  2738 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:54:13.807  2738  2738 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:54:13.817  2738  2738 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:54:13.817  2738  2738 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:54:13.817  2738  2738 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:54:13.817  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIDialogActivity(2018/onResume)] 
,08-31 16:54:13.827  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIDialogActivity(2037/llIlIIIIlIIIIIlIlIII)] id 223
,08-31 16:54:13.827   754  3296 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:13.827  4288  4288 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:308901
,08-31 16:54:13.837   754  3296 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:13.837   754  2180 D ActivityManager: mDVFSHelper.acquire()
,08-31 16:54:13.847   754  2180 V WindowManager: addAppToken: AppWindowToken{c55ed61 token=Token{45f58c8 ActivityRecord{51d456b u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t169}}} to stack=1 task=169 at 1
,08-31 16:54:13.847   754  2180 D InputDispatcher: Focused application set to: xxxx
,08-31 16:54:13.847  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIDownloadProgressActivity(355/llllIIIllIlIIIIllllI)] 
,08-31 16:54:13.847  2738  2738 D BluetoothSap: Create BluetoothSap proxy object
,08-31 16:54:13.857  6846  6846 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 16:54:13.857   754  2180 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-31 16:54:13.857   754  2180 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:54:13.857   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:54:13.857  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIDialogActivity(2010/onPause)] 
,08-31 16:54:13.857   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
08-31 16:54:13.857   754   754 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-31 16:54:13.867   754   846 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.wssyncmldm
,08-31 16:54:13.877  4288  4288 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.wssyncmldm rsrc of package null
,08-31 16:54:13.887  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5347/IlIllIIIIllllllIlIIl)] Get Priority : 0
,08-31 16:54:13.887  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(84/onCreate)] PolicyType : -1
,08-31 16:54:13.897  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5187/lIIIIIIIlllllllIIlll)] Get Force status : 0
,08-31 16:54:13.897  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(845/lllIlIlIIIllIIlIllIl)] Check Force Install : false
,08-31 16:54:13.907  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5688/lIlIIIlllIlIlIlIIIll)] Get Postpone status : 0
,08-31 16:54:13.907  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(672/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-31 16:54:13.917  4115  6860 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,08-31 16:54:13.917  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.IlllIlIIIlIIIllIllII(374/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-31 16:54:13.927  2738  2738 D LocalBluetoothProfileManager: PANU : true
,08-31 16:54:13.937  2738  2738 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
08-31 16:54:13.937  2738  2738 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:54:13.937  2738  2738 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,08-31 16:54:13.937  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5347/IlIllIIIIllllllIlIIl)] Get Priority : 0
,08-31 16:54:13.947  4115  6844 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 16:54:13.947  2738  2738 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:54:13.957  2738  2738 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:54:13.957   754   774 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-31 16:54:13.957  1386  1386 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:13.957  1386  1386 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:54:13.957   754  1298 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
08-31 16:54:13.967  2738  2738 D BluetoothA2dp: Proxy object connected
,08-31 16:54:13.967  6444  6514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:54:13.967  6444  6514 I jxcore-log: 
,08-31 16:54:13.977  2738  2738 D A2dpProfile: Bluetooth service connected
,08-31 16:54:13.977   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39d5556 6532:com.android.bluetooth/1002}
,08-31 16:54:13.977  6532  6532 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fe8e25
,08-31 16:54:13.977  6532  6532 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:54:13.977  6777  6790 D BadgeProvider: query, [selection] : null
,08-31 16:54:13.987  1386  1403 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:13.987   754   754 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : com.wssyncmldm
,08-31 16:54:13.987  6532  6735 D A2dpStateMachine: getConnectedDevices : size=0
,08-31 16:54:13.987  2738  2738 D BluetoothMap: Proxy object connected
,08-31 16:54:13.987  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
08-31 16:54:13.987  2738  2738 D MapProfile: Bluetooth service connected
08-31 16:54:13.987  2738  2738 D BluetoothMap: getConnectedDevices()
,08-31 16:54:13.997  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:13.997  6444  6514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:54:13.997  6444  6514 I jxcore-log: 
,08-31 16:54:13.997   754  1737 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{88e004d 6714:com.google.android.apps.maps/u0a121}
,08-31 16:54:14.007  2738  2738 D BluetoothPbap: Proxy object connected
,08-31 16:54:14.007   754  1737 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77280dc 2021:com.google.android.gms.persistent/u0a11}
,08-31 16:54:14.007  2738  2738 D PbapServerProfile: Bluetooth service connected
,08-31 16:54:14.007  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(6529/IlIlIlIllIlllIllllll)] get noti count : 1
08-31 16:54:14.007  2021  2021 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver bqHint=4 (has extras) }.
,08-31 16:54:14.007   754   826 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 38328, reason: UserStart, SyncResult: databaseError: true stats []
,08-31 16:54:14.017   754   826 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 340993, reason: UserStart
,08-31 16:54:14.017  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(6445/llllIlllIIIlIlIlIIII)] Initiated Type: 2
,08-31 16:54:14.017  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(465/lllllIIlIIIlIlIIIllI)] show dialog
,08-31 16:54:14.027  2021  6868 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 16:54:14.027   754   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a9c94fe u-1 android.bluetooth.adapter.action.STATE_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77280dc 2021:com.google.android.gms.persistent/u0a11}
,08-31 16:54:14.027  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:14.027  2021  2021 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver bqHint=4 (has extras) }.
,08-31 16:54:14.037  2738  2738 D BluetoothSap: Proxy object connected
,08-31 16:54:14.037  2738  2738 D SapProfile: Bluetooth service connected
08-31 16:54:14.037  2738  2738 D BluetoothInputDevice: Proxy object connected
,08-31 16:54:14.037  2738  2738 D HidProfile: Bluetooth service connected
,08-31 16:54:14.047  1386  1386 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
08-31 16:54:14.057  6869  6869 E Zygote  : v2
08-31 16:54:14.057  6869  6869 I libpersona: KNOX_SDCARD checking this for 10163
08-31 16:54:14.057  6869  6869 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:14.057   754  1717 I ActivityManager: Start proc 6869:com.android.exchange/u0a163 for broadcast-3 com.android.exchange/.service.ExchangeBroadcastReceiver
08-31 16:54:14.057  6869  6869 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:14.057  6869  6869 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:14.057  6869  6869 E Zygote  : accessInfo : 0
08-31 16:54:14.057  6869  6869 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.android.exchange 
08-31 16:54:14.057  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:14.057  3068  3086 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-31 16:54:14.057  3068  3086 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-31 16:54:14.057  3068  3086 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-31 16:54:14.057  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:14.067  3068  3086 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-31 16:54:14.067  1386  1386 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,08-31 16:54:14.077   754  1713 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-31 16:54:14.087  1386  1386 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:14.087  2738  2738 D HeadsetProfile: Bluetooth service connected
,08-31 16:54:14.097  1386  1386 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 16:54:14.107  2738  2738 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:54:14.107  2738  2738 D PanProfile: Bluetooth service connected
,08-31 16:54:14.117  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5625/IIllIlIIlIlllIIllIII)] Get Postpone Count : 0
,08-31 16:54:14.117  2021  6868 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 16:54:14.117  1386  1386 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 16:54:14.117  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:14.117  6869  6869 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:14.127  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5647/llIllllIlllIIIllIIIl)] Get Postpone Max Count : -1
,08-31 16:54:14.127  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(5187/lIIIIIIIlllllllIIlll)] Get Force status : 0
,08-31 16:54:14.127  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(845/lllIlIlIIIllIIlIllIl)] Check Force Install : false
,08-31 16:54:14.137  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.lIIlllIlIIlIlIllIlIl(569/onCreateDialog)] Postpone Disable : false
,08-31 16:54:14.137   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5f9da10 u0 com.android.email.intent.action.CHANGE_LOGGING qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{432e909 6869:com.android.exchange/u0a163}
,08-31 16:54:14.147  6869  6869 W ResourcesManager: getTopLevelResources: /system/app/SecExchange/SecExchange.apk / 1.0 running in com.android.exchange rsrc of package null
,08-31 16:54:14.177  6869  6869 W System  : ClassLoader referenced unknown path: /system/app/SecExchange/lib/arm
,08-31 16:54:14.197  4288  4288 D SecWifiDisplayUtil: Metadata value : none
,08-31 16:54:14.197  4288  4288 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{a019e15 V.E...... R.....I. 0,0-0,0}
,08-31 16:54:14.197  4288  6881 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 16:54:14.207   754  1717 D ISSUE_DEBUG: InputChannelName : 3980cc5 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity
,08-31 16:54:14.207   754   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3980cc5 u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-31 16:54:14.207   754  1717 D InputDispatcher: Focus entered window: 4288
,08-31 16:54:14.207  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(754/onResume)] 
,08-31 16:54:14.207   754   893 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
,08-31 16:54:14.207   754   893 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:54:14.207   754   893 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
08-31 16:54:14.207   754   893 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 16:54:14.207  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-31 16:54:14.207  6846  6846 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:54:14.217   754  1732 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:54:14.217  6846  6846 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(72/onCreate)] DiagMon DM Application Start !
,08-31 16:54:14.217  4288  4288 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{84f4864 I.E...... R.....I. 0,0-0,0}
,08-31 16:54:14.227  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:54:14.227   754  1676 D ISSUE_DEBUG: InputChannelName : 391d54b com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity
,08-31 16:54:14.227  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:54:14.227  6846  6846 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
08-31 16:54:14.227  6846  6846 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 16:54:14.237  6883  6883 E Zygote  : v2
,08-31 16:54:14.237   754   775 I ActivityManager: Start proc 6883:com.sec.knox.switcher/1000 for broadcast-5 com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
08-31 16:54:14.237  6883  6883 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:14.247  6883  6883 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:14.247  6883  6883 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:14.247  6883  6883 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:14.247  6883  6883 E Zygote  : accessInfo : 0
,08-31 16:54:14.257   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8152057 6846:com.sec.android.diagmonagent/1000}
,08-31 16:54:14.257  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:54:14.257  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:54:14.257  6846  6846 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,08-31 16:54:14.257  6846  6846 W DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 16:54:14.257   754  1298 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-31 16:54:14.257   754  1298 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:54:14.257   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-31 16:54:14.257  4288  4288 I FOTA_AGENT: [com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity(747/onPause)] 
08-31 16:54:14.257   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
08-31 16:54:14.257   754   754 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-31 16:54:14.277  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:14.277  6883  6883 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:14.297  6532  6603 D bt_vendor: op for 7
08-31 16:54:14.297  6532  6603 D bt_upio : upio_set : pio 0 action 1, polarity 1
08-31 16:54:14.297  6532  6603 D bt_upio : BT_WAKE is de-asserted already
,08-31 16:54:14.307   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
,08-31 16:54:14.307   293   293 I SurfaceFlinger: id=22 createSurf (145x145),1 flag=4, YUIInstallC
,08-31 16:54:14.307   754  1717 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6209e6 6883:com.sec.knox.switcher/1000}
,08-31 16:54:14.317   754  1496 I ActivityManager: Killing 5315:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-31 16:54:14.317  6883  6883 W ResourcesManager: getTopLevelResources: /system/app/KnoxSwitcher/KnoxSwitcher.apk / 1.0 running in com.sec.knox.switcher rsrc of package null
,08-31 16:54:14.327  4288  6881 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:54:14.327  4288  6881 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:54:14.327  4288  6881 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:54:14.327  4288  6881 I Adreno-EGL: Local Branch: ss
08-31 16:54:14.327  4288  6881 I Adreno-EGL: Remote Branch: 
08-31 16:54:14.327  4288  6881 I Adreno-EGL: Local Patches: 
08-31 16:54:14.327  4288  6881 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:54:14.337  4288  6881 D libEGL  : eglInitialize EGLDisplay = 0xade3f7c4
08-31 16:54:14.337  4288  6881 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:54:14.347  6883  6883 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm
,08-31 16:54:14.347   754  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:14.347  2738  2738 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:54:14.347  2738  2738 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:54:14.357  6883  6883 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
08-31 16:54:14.357  6883  6883 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,08-31 16:54:14.367   754  1717 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-31 16:54:14.367   754  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6209e6 6883:com.sec.knox.switcher/1000}
,08-31 16:54:14.377  6883  6883 I usagelog: received in receiver
,08-31 16:54:14.377  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,08-31 16:54:14.377  6883  6883 I KnoxUsageLogPro: premStatus:2
,08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: isEulaShown : false
,08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-31 16:54:14.387  6883  6883 I usagelog: received in receiver
,08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: premStatus:2
,08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: isEulaShown : false
08-31 16:54:14.387  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-31 16:54:14.407   293   293 I SurfaceFlinger: id=23 createSurf (145x145),1 flag=4, YUIInstallC
,08-31 16:54:14.417   754   775 I ActivityManager: Start proc 6896:com.samsung.android.sm.policy/u0a203 for broadcast-5 com.samsung.android.sm.policy/.PolicyBroadCastReceiver
,08-31 16:54:14.417  6896  6896 E Zygote  : v2
08-31 16:54:14.417  6896  6896 I libpersona: KNOX_SDCARD checking this for 10203
08-31 16:54:14.417  6896  6896 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:14.417  6896  6896 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:14.417  6896  6896 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:14.417  6896  6896 E Zygote  : accessInfo : 0
,08-31 16:54:14.417  6896  6896 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,08-31 16:54:14.417  4288  4288 V ActivityThread: updateVisibility : ActivityRecord{7750b token=android.os.BinderProxy@a18e52a {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-31 16:54:14.427   754  1713 I ActivityManager: Killing 5706:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
,08-31 16:54:14.437   293   345 I SurfaceFlinger: id=22 Removed YUIInstallC (8/10)
,08-31 16:54:14.437   293  1792 I SurfaceFlinger: id=22 Removed YUIInstallC (-2/10)
,08-31 16:54:14.437   754  1737 D InputDispatcher: Focus left window: 4288
,08-31 16:54:14.437   754  1737 D InputDispatcher: Focus entered window: 4288
,08-31 16:54:14.437   754   893 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
,08-31 16:54:14.437   754   893 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:54:14.437   754   893 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
,08-31 16:54:14.437   754   893 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-31 16:54:14.437   754  1704 V WindowStateAnimator: Finishing drawing window Window{391d54b u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,08-31 16:54:14.447  4288  4288 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-31 16:54:14.447  4288  4288 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 16:54:14.447   754  1298 I ActivityManager: Killing 5894:com.google.android.partnersetup/u0a14 (adj 15): DHA:empty #37
,08-31 16:54:14.447   754   774 V WindowStateAnimator: Finishing drawing window Window{391d54b u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=HAS_DRAWN
,08-31 16:54:14.447   754  1732 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:54:14.457  4288  4288 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a18e52a time:309530
,08-31 16:54:14.457   754   847 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{391d54b u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}
,08-31 16:54:14.457   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ea5d84 6573:tv.peel.smartremote/u0a170}
,08-31 16:54:14.457   754   893 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:54:14.457   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-31 16:54:14.457   754   893 I ActivityManager: Displayed com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity: +587ms (total +693ms)
,08-31 16:54:14.457   754   754 I KnoxTimeoutHandler: SD activityfalse
08-31 16:54:14.457   754   893 D ActivityManager: mDVFSHelper.release()
08-31 16:54:14.457   754   893 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{51d456b u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t169} time:309538
,08-31 16:54:14.467  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,08-31 16:54:14.467  1982  1982 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-31 16:54:14.477  6896  6896 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:14.477  6896  6896 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:14.487   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8152057 6846:com.sec.android.diagmonagent/1000}
,08-31 16:54:14.487  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,08-31 16:54:14.487  6846  6846 I DIAGMON_AGENT: [lllIIIIIIlllIlIIIIII(52/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:54:14.487  6846  6846 I DIAGMON_AGENT: ./bssid: f4:f2:6d:22:99:3e
,08-31 16:54:14.487  6846  6846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 android.content.ContextWrapper.sendBroadcast:410 android.content.ContextWrapper.sendBroadcast:410 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3634 
,08-31 16:54:14.497   754  1414 D ActivityManager: isAutoRunBlockedApp:: com.google.android.partnersetup, Auto Run ON
,08-31 16:54:14.507   754  1704 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{89198b9 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee6fbe 6896:com.samsung.android.sm.policy/u0a203}
,08-31 16:54:14.507   754  1732 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,08-31 16:54:14.517  6896  6896 W ResourcesManager: getTopLevelResources: /system/app/SCPMClient/SCPMClient.apk / 1.0 running in com.samsung.android.sm.policy rsrc of package null
,08-31 16:54:14.517   754  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3781d1d 1386:com.android.systemui/u0a58}
,08-31 16:54:14.527   754  1732 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 16:54:14.527   754  1676 D SecContentProvider2: query(), uri = 15 selection = getToastGravityEnabledState
,08-31 16:54:14.537   754  1737 D SecContentProvider2: query(), uri = 15 selection = getToastEnabledState
,08-31 16:54:14.537  6896  6896 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient/lib/arm
,08-31 16:54:14.537   754  1414 D SecContentProvider2: query(), uri = 15 selection = getToastShowPackageNameState
,08-31 16:54:14.547  1386  1386 D ViewRootImpl: #1 mView = android.widget.LinearLayout{142d55c V.E...... ......I. 0,0-0,0 #10203a7 android:id/toast_layout_root}
,08-31 16:54:14.557   754  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d4d8545 2738:com.android.settings/1000}
,08-31 16:54:14.557   754  1414 D ISSUE_DEBUG: InputChannelName : 96eb135 Toast
,08-31 16:54:14.557  2738  2738 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:54:14.557  2738  2738 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:54:14.557   754  1414 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,08-31 16:54:14.567   754  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6209e6 6883:com.sec.knox.switcher/1000}
,08-31 16:54:14.567  6883  6883 I usagelog: received in receiver
08-31 16:54:14.567  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
08-31 16:54:14.567  6883  6883 I KnoxUsageLogPro: premStatus:2
,08-31 16:54:14.567  6883  6883 I KnoxUsageLogPro: isEulaShown : false
08-31 16:54:14.567  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-31 16:54:14.567   293   293 I SurfaceFlinger: id=24 createSurf (1x1),1 flag=4, Uoast
,08-31 16:54:14.567   754  1590 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{471b041 u-1 android.net.wifi.STATE_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee6fbe 6896:com.samsung.android.sm.policy/u0a203}
,08-31 16:54:14.577   754  1732 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754
,08-31 16:54:14.587   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ee6fbe 6896:com.samsung.android.sm.policy/u0a203}
,08-31 16:54:14.587  1386  1386 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-31 16:54:14.607  1386  1386 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-31 16:54:14.617   754  1713 V WindowStateAnimator: Finishing drawing window Window{96eb135 u0 d0 Toast}: mDrawState=DRAW_PENDING
,08-31 16:54:14.617   754   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{97fe740 u-1 android.net.wifi.STATE_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ea5d84 6573:tv.peel.smartremote/u0a170}
,08-31 16:54:14.627   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef39364
,08-31 16:54:14.627   754   774 I ActivityManager: Killing 5909:com.samsung.groupcast/u0a15 (adj 15): DHA:empty #37
,08-31 16:54:14.637   754  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8d8ff2 6444:com.test.thalitest/u0a4}
,08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 0 : [type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 2 : [type: MOBILE_MMS[] - MOBILE_MMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 3 : [type: MOBILE_SUPL[] - MOBILE_SUPL, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 4 : [type: MOBILE_DUN[] - MOBILE_DUN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 5 : [type: MOBILE_HIPRI[] - MOBILE_HIPRI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 7 : [type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 10 : [type: MOBILE_FOTA[] - MOBILE_FOTA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 11 : [type: MOBILE_IMS[] - MOBILE_IMS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 12 : [type: MOBILE_CBS[] - MOBILE_CBS, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 13 : [type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 14 : [type: MOBILE_IA[] - MOBILE_IA, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 15 : [type: MOBILE_EMERGENCY[] - MOBILE_EMERGENCY, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
08-31 16:54:14.637   754  1704 D ConnectivityService: returning getNetworkInfo for network type 17 : [type: VPN[] - VPN, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,08-31 16:54:14.647   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a623dbe 754:system/1000}
,08-31 16:54:14.647   754  1414 D ActivityManager: isAutoRunBlockedApp:: com.samsung.groupcast, Auto Run ON
,08-31 16:54:14.657   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{77280dc 2021:com.google.android.gms.persistent/u0a11}
,08-31 16:54:14.667   754  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4330672 4115:com.google.android.gms/u0a11}
,08-31 16:54:14.667   308  1186 D EnterpriseController: netId is 0
08-31 16:54:14.667   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:54:14.677  4115  6917 I iu.SyncManager: SYNC; picasa accounts
,08-31 16:54:14.687  4115  4115 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 16:54:14.687  4115  4115 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:54:14.687  4115  6917 I iu.UploadsManager: num queued entries: 0
,08-31 16:54:14.687  4115  6917 I iu.UploadsManager: num updated entries: 0
,08-31 16:54:14.687  4115  6917 I iu.SyncManager: NEXT; no task
,08-31 16:54:14.697   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4330672 4115:com.google.android.gms/u0a11}
,08-31 16:54:14.717   754  1704 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.AccountsChangedReceiver newState = 2 callingPackage = 10011
,08-31 16:54:14.727   754  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{34b5e58 2319:com.sec.android.widgetapp.ap.hero.accuweather/u0a70}
,08-31 16:54:14.727  2319  2319 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:54:14.737  2319  2319 D accuweather: [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,08-31 16:54:14.737  2319  2319 D accuweather: [KK AccuPhone]>>> UIMEM:91 [0:0] getInstance
,08-31 16:54:14.737  2319  2319 D accuweather: [KK AccuPhone]>>> UIMEM:79 [0:0] UIManager : create ui manager
,08-31 16:54:14.737  2319  2319 D accuweather: [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,08-31 16:54:14.737  2319  2319 D accuweather: [KK AccuPhone]>>> RM:136 [0:0]  V init 
,08-31 16:54:14.747  1517  2446 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:54:14.747  2319  2319 D accuweather: [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,08-31 16:54:14.747  1517  1528 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-31 16:54:14.757  2319  2319 D accuweather: [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,08-31 16:54:14.757  1517  1529 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:54:14.757  2319  2319 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,08-31 16:54:14.757  2319  2319 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,08-31 16:54:14.777   754   846 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a623dbe 754:system/1000}
,08-31 16:54:14.777   754   754 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e9c44 4145:com.samsung.klmsagent/u0a18}
,08-31 16:54:14.787  4145  4145 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 } | timestamp: Wed Aug 31 16:54:14 GMT+02:00 2016
,08-31 16:54:14.797  6919  6919 E Zygote  : v2
,08-31 16:54:14.797  6919  6919 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:14.797  6919  6919 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:14.797   754   846 I ActivityManager: Start proc 6919:com.policydm/1000 for broadcast-5 com.policydm/.XDMBroadcastReceiver
,08-31 16:54:14.797  6919  6919 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:14.797  6919  6919 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:14.797  6919  6919 E Zygote  : accessInfo : 0
,08-31 16:54:14.797   754  3297 W ResourcesManager: getTopLevelResources: /system/priv-app/FotaAgent/FotaAgent.apk / 1.0 running in null rsrc of package null
,08-31 16:54:14.797  4145  4145 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:54:14.807   754  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{599b78 5562:com.sec.android.app.shealth/u0a34}
,08-31 16:54:14.807  4145  4145 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
,08-31 16:54:14.807  4145  4145 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:54:14.817  4145  4145 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:54:14.817  4145  6930 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 }
,08-31 16:54:14.817  4145  6930 D KLMS-2.6.032: : KLMSIntentService(): TIME_CHANGED
,08-31 16:54:14.817  4145  6930 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().START : Wed Aug 31 16:54:14 GMT+02:00 2016
,08-31 16:54:14.827  6919  6919 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:14.827  6919  6919 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:14.837  4145  6930 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,08-31 16:54:14.837  4145  6930 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().START
08-31 16:54:14.837  4145  6930 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,08-31 16:54:14.837  4145  6930 I KLMS-2.6.032: : Systemprocess(): ModifySetAlarm().END
,08-31 16:54:14.837  4145  6930 I KLMS-2.6.032: : Systemprocess(): dateTimeChanged().END
,08-31 16:54:14.837   754  1676 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef4c2b3 6919:com.policydm/1000}
,08-31 16:54:14.847   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c789e4d 1857:com.sec.android.app.shealth:remote/u0a34}
,08-31 16:54:14.847  4145  4145 I KLMS-2.6.032: : KLMSIntentService(): onDestroy()
,08-31 16:54:14.857  6919  6919 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package null
,08-31 16:54:14.867   754  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c789e4d 1857:com.sec.android.app.shealth:remote/u0a34}
,08-31 16:54:14.877   754  1713 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:14.877  4934  6933 D PicasaService: start picasa sync
,08-31 16:54:14.887  6919  6919 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,08-31 16:54:14.887  4934  6933 D PicasaService: end picasa sync
,08-31 16:54:14.947  1857  1857 D HealthDataStore: Service for HealthDataStore is connected
,08-31 16:54:14.947   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef4c2b3 6919:com.policydm/1000}
,08-31 16:54:14.957  1857  1857 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-31 16:54:14.977  6919  6919 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,08-31 16:54:14.997  1857  1857 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-31 16:54:14.997  1857  1857 E HealthDataStore: disconnectService: Context instance is invalid
,08-31 16:54:15.067  6919  6919 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
,08-31 16:54:15.077  6919  6919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,08-31 16:54:15.087  2021  6915 I qtaguid : Tagging socket 41 with tag 1000040700000000{268436487,0} uid -1, pid: 2021, getuid(): 10011
,08-31 16:54:15.087  2021  6915 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-31 16:54:15.097   754   774 I ActivityManager: Start proc 6941:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-31 16:54:15.097  6919  6919 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,08-31 16:54:15.097  6941  6941 E Zygote  : v2
08-31 16:54:15.097  6941  6941 I libpersona: KNOX_SDCARD checking this for 10210
08-31 16:54:15.097  6941  6941 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:15.097  6941  6941 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.097  6941  6941 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:15.097  6941  6941 E Zygote  : accessInfo : 0
,08-31 16:54:15.097  6941  6941 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-31 16:54:15.117  2021  6915 I GCM     : GCM config loaded
,08-31 16:54:15.137  6919  6919 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,08-31 16:54:15.137  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:15.137  6941  6941 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:15.157   754  1737 V AlarmManager:  remove PendingIntent] PendingIntent{8ac7dd2: PendingIntentRecord{d8775dc com.google.android.gms broadcastIntent}}
,08-31 16:54:15.157  6919  6919 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,08-31 16:54:15.157  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,08-31 16:54:15.157  6941  6941 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-31 16:54:15.157  6919  6919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6316 
,08-31 16:54:15.177  6941  6941 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-31 16:54:15.177  6941  6941 D AASAservice: onCreate()
,08-31 16:54:15.187  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,08-31 16:54:15.207  6919  6919 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,08-31 16:54:15.227  6919  6919 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,08-31 16:54:15.237  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,08-31 16:54:15.237   754   775 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:15.237  6919  6960 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
08-31 16:54:15.237  6919  6960 I DBG_POLICYDM: [com.policydm.XDMService(382/lllIlIlIIIllIIlIllIl)] a previous network is 0, current network is 2
,08-31 16:54:15.237   754  1704 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ef4c2b3 6919:com.policydm/1000}
,08-31 16:54:15.237  6919  6960 E DBG_POLICYDM: [com.policydm.XDMService(384/lllIlIlIIIllIIlIllIl)] network changed.... 
,08-31 16:54:15.247  6919  6960 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : true
,08-31 16:54:15.247  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.intent.action.TIME_SET
,08-31 16:54:15.247  6919  6960 I DBG_POLICYDM: [com.policydm.lllIlIlIIIllIIlIllIl(93/run)] SPD SERVICE Start!!
,08-31 16:54:15.247  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,08-31 16:54:15.247  6919  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.policydm.lllIlIlIIIllIIlIllIl.run:94 java.lang.Thread.run:818 
,08-31 16:54:15.247  6919  6960 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(196/llIIIIlllllIIllIIllI)] DM Not Init
,08-31 16:54:15.257  6919  6919 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
,08-31 16:54:15.257  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
,08-31 16:54:15.257  6919  6919 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/09/12/23:56:58
,08-31 16:54:15.267  6919  6960 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,08-31 16:54:15.267  1457  1457 D Recents : onTaskStackChanged
,08-31 16:54:15.267  6919  6919 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,08-31 16:54:15.277  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,08-31 16:54:15.277  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,08-31 16:54:15.277   754  1298 V AlarmManager:  remove PendingIntent] PendingIntent{b30a51e: PendingIntentRecord{abdd91c com.android.bluetooth broadcastIntent}}
,08-31 16:54:15.277  6919  6919 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,08-31 16:54:15.277  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
,08-31 16:54:15.277  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,08-31 16:54:15.287   754  2180 I ActivityManager: Start proc 6964:com.samsung.android.scloud/5009 for broadcast-3 com.samsung.android.scloud/.receivers.SCloudReceiver
,08-31 16:54:15.287  6964  6964 E Zygote  : v2
08-31 16:54:15.287  6964  6964 I libpersona: KNOX_SDCARD checking this for 5009
08-31 16:54:15.287  6964  6964 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:15.287  6964  6964 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.287  6964  6964 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:15.287  6964  6964 E Zygote  : accessInfo : 0
,08-31 16:54:15.287  6964  6964 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.scloud 
,08-31 16:54:15.287   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{939a1ff: PendingIntentRecord{8fa35f0 com.google.android.apps.plus broadcastIntent}}
,08-31 16:54:15.297  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-31 16:54:15.317   754  1717 V AlarmManager:  remove PendingIntent] PendingIntent{71fdbcc: PendingIntentRecord{950ee15 com.google.android.apps.plus broadcastIntent}}
,08-31 16:54:15.327  6919  6919 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
,08-31 16:54:15.327  6919  6961 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,08-31 16:54:15.327  6919  6961 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,08-31 16:54:15.327  6919  6961 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,08-31 16:54:15.347  6964  6964 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:15.347  6964  6964 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:15.347  6919  6961 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,08-31 16:54:15.347  6919  6961 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,08-31 16:54:15.347  6919  6960 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,08-31 16:54:15.357   754  1414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{55f5691 6964:com.samsung.android.scloud/5009}
,08-31 16:54:15.357  6919  6960 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,08-31 16:54:15.357   754  1414 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-31 16:54:15.357  6919  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.XDMService.llllIIIllIlIIIIllllI:288 com.policydm.lllIlIlIIIllIIlIllIl.run:98 
08-31 16:54:15.357  6919  6961 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,08-31 16:54:15.357  6919  6961 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,08-31 16:54:15.367  6919  6960 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(324/llllIIIllIlIIIIllllI)] bNetworkChange : false
,08-31 16:54:15.367  6919  6961 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,08-31 16:54:15.367  6964  6964 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in com.samsung.android.scloud rsrc of package null
,08-31 16:54:15.377  6919  6919 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,08-31 16:54:15.387  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,08-31 16:54:15.387  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,08-31 16:54:15.387  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,08-31 16:54:15.387  6964  6964 W System  : ClassLoader referenced unknown path: /system/priv-app/SCloudService/lib/arm
,08-31 16:54:15.387  6919  6919 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-31 16:54:15.397  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:15.397  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,08-31 16:54:15.397  6919  6919 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(110/llIlIIIIlIIIIIlIlIII)] Polling time is vaild
08-31 16:54:15.397  6919  6919 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(274/llIIIIlllllIIllIIllI)] Heartbeat settings is activated.
08-31 16:54:15.397  6919  6919 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/09/12/23:56:58
08-31 16:54:15.397  6919  6961 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
08-31 16:54:15.407  6979  6979 E Zygote  : v2
08-31 16:54:15.407  6979  6979 I libpersona: KNOX_SDCARD checking this for 10011
08-31 16:54:15.407  6979  6979 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:15.407   754  1676 I ActivityManager: Start proc 6979:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-31 16:54:15.407  6979  6979 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.407  6979  6979 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:15.407  6979  6979 E Zygote  : accessInfo : 0
08-31 16:54:15.407  6979  6979 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-31 16:54:15.407  6919  6961 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
08-31 16:54:15.407  6919  6919 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,08-31 16:54:15.417  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,08-31 16:54:15.427  6919  6919 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,08-31 16:54:15.427  6992  6992 E Zygote  : v2
08-31 16:54:15.427  6992  6992 I libpersona: KNOX_SDCARD checking this for 10044
08-31 16:54:15.427  6992  6992 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.427  6992  6992 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:15.427  6992  6992 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:15.427  6992  6992 E Zygote  : accessInfo : 0
08-31 16:54:15.427  6992  6992 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.osp.app.signin 
,08-31 16:54:15.427   754  1298 I ActivityManager: Start proc 6992:com.osp.app.signin/u0a44 for broadcast-5 com.osp.app.signin/.OspReceiver
,08-31 16:54:15.437   754  1737 I ActivityManager: Killing 5960:com.samsung.android.provider.shootingmodeprovider/u0a169 (adj 15): DHA:empty #37
,08-31 16:54:15.437   754  1737 I ActivityManager: Killing 5945:com.sec.android.app.myfiles/u0a50 (adj 15): DHA:empty #37
,08-31 16:54:15.437  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:15.437  6979  6979 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:15.467  6979  6979 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-31 16:54:15.467  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:15.467  6992  6992 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:15.477   754  1496 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ebff82 6992:com.osp.app.signin/u0a44}
,08-31 16:54:15.487  6919  6961 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,08-31 16:54:15.497   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{9e19693: PendingIntentRecord{311cacd com.google.android.gms broadcastIntent}}
,08-31 16:54:15.497  6919  6961 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,08-31 16:54:15.497  6919  6962 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,08-31 16:54:15.497  6919  6961 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,08-31 16:54:15.497   754  1676 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:15.507  6919  6962 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,08-31 16:54:15.507  6992  6992 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in com.osp.app.signin rsrc of package null
,08-31 16:54:15.507  6919  6962 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
08-31 16:54:15.517  6979  6979 I MultiDex: VM with version 2.1.0 has multidex support
08-31 16:54:15.517  6979  6979 I MultiDex: install
08-31 16:54:15.517  6979  6979 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,08-31 16:54:15.517  6919  6962 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
,08-31 16:54:15.517   754   775 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.provider.shootingmodeprovider, Auto Run ON
,08-31 16:54:15.527  6964  6964 I ExternalOEMControlProvider: onCreate
,08-31 16:54:15.537   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.myfiles, Auto Run ON
,08-31 16:54:15.547  6964  6964 I SCloudService: onCreate
,08-31 16:54:15.547  6992  6992 W System  : ClassLoader referenced unknown path: /system/priv-app/Samsungservice2_xxhdpi/lib/arm
,08-31 16:54:15.557  6919  6962 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,08-31 16:54:15.567  6979  6979 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-31 16:54:15.587  6979  6979 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-31 16:54:15.587  6979  6979 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-31 16:54:15.597  6979  6979 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:54:15.607  6919  6961 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,08-31 16:54:15.607  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,08-31 16:54:15.617  6992  6992 I SA      : [SSP] onCreated
,08-31 16:54:15.627  6964  6964 I SCloudService: SCloudService Version Info : 1.4.13
,08-31 16:54:15.627  6964  6964 I SCloudReceiver: onReceive : android.intent.action.TIME_SET
,08-31 16:54:15.627  6979  6979 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 16:54:15.627   754  1590 I ActivityManager: Killing 5974:com.samsung.android.sm.devicesecurity/5012 (adj 15): DHA:empty #37
,08-31 16:54:15.637  6919  6962 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,08-31 16:54:15.647  6992  6992 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@f020333
,08-31 16:54:15.647   754  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ebff82 6992:com.osp.app.signin/u0a44}
,08-31 16:54:15.647  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
,08-31 16:54:15.647  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,08-31 16:54:15.657   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sm.devicesecurity, Auto Run ON
,08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : Time Difference not stored. 
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLongForUser(Settings.java:2031)
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : 	at android.provider.Settings$System.getLong(Settings.java:2021)
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.utils.TimeManager.updateTimeSettings(TimeManager.java:89)
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : 	at com.samsung.android.scloud.receivers.SCloudReceiver$5.run(SCloudReceiver.java:188)
08-31 16:54:15.657  6964  7011 E SCLOUD_ERR- Time Manager : 	at java.lang.Thread.run(Thread.java:818)
,08-31 16:54:15.657  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,08-31 16:54:15.657  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,08-31 16:54:15.657  6919  6961 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 16:54:15.687  6919  6961 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(235/lllIlIlIIIllIIlIllIl)] Start resumecase for INIT
,08-31 16:54:15.697  6979  6979 D ChimeraCfgMgr: Reading stored module config
,08-31 16:54:15.717  6992  6992 I SA      : [TPM] There is no property file
,08-31 16:54:15.727  6992  6992 I SA      : [SCU] isHaveSA() - false
,08-31 16:54:15.737  6992  6992 I SA      : [TPM] getModelProperty : null
,08-31 16:54:15.747  6992  6992 I SA      : [TPM] getCSCProperty : null
,08-31 16:54:15.747   754  1590 I ActivityManager: Killing 5015:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-31 16:54:15.747  6992  6992 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-31 16:54:15.747  6992  6992 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 16:54:15.747  6992  6992 I SA      : [DM] TFT FEATURE: false
08-31 16:54:15.747  6992  6992 I SA      : [DM] init START
,08-31 16:54:15.747  6444  6514 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:54:15.747  6444  6514 I jxcore-log: 
,08-31 16:54:15.747  6979  6989 W art     : Suspending all threads took: 5.780ms
,08-31 16:54:15.757   754  1737 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:15.767  6919  6961 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,08-31 16:54:15.777  6979  6989 I art     : Background sticky concurrent mark sweep GC freed 39407(2MB) AllocSpace objects, 3(144KB) LOS objects, 31% free, 17MB/25MB, paused 6.576ms total 49.155ms
,08-31 16:54:15.797   754   768 I art     : Background partial concurrent mark sweep GC freed 100129(5MB) AllocSpace objects, 15(300KB) LOS objects, 27% free, 42MB/58MB, paused 1.937ms total 140.080ms
,08-31 16:54:15.797   322   322 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6979)
,08-31 16:54:15.807   754  1732 D CountryDetector: No listener is left
,08-31 16:54:15.807  6992  6992 I SA      : [DM] This device is not a Vodafone
,08-31 16:54:15.807  6979  7012 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 16:54:15.817   754   774 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-31 16:54:15.817  6919  6961 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,08-31 16:54:15.827  6919  6961 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,08-31 16:54:15.837  6992  6992 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 16:54:15.837  6992  6992 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 16:54:15.837  6992  6992 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 16:54:15.837  6992  6992 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-31 16:54:15.837  6992  6992 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:54:15.847  6992  6992 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
08-31 16:54:15.847  6992  6992 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 16:54:15.847  6992  6992 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-31 16:54:15.857  6992  6992 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 16:54:15.867  6992  6992 I SA      : [SCU] isHaveSA() - false
08-31 16:54:15.867  6992  6992 I SA      : support phone number id : false
08-31 16:54:15.867  6992  6992 I SA      : [DM] Supports Ref Jpn : true
,08-31 16:54:15.867  6992  6992 I SA      : [DM] init END
,08-31 16:54:15.867  6992  6992 I SA      : [OR] onReceive log=[SA = 2.1.0300 V = 23 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = MMB29M M = SM-G900F OKLEFT false DIS MMB29M.G900FXXS1CPG9 PSS = 5.219788042639568  ]
,08-31 16:54:15.867  6992  6992 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-31 16:54:15.867  6992  6992 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 16:54:15.867  6992  6992 I SA      : [SLFUCHKMGR] constructor called
,08-31 16:54:15.877   322   322 D WVCdm   : Instantiating CDM.
,08-31 16:54:15.887   322   960 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6979)
08-31 16:54:15.887   322   960 I WVCdm   : CdmEngine::OpenSession
08-31 16:54:15.887   322   960 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-31 16:54:15.887  6992  6992 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:54:15.887  6992  6992 I SA      : [OR] == isSIMCardReady false ==
,08-31 16:54:15.897  6992  6992 I SA      : [SCU] == networkStateCheck == true
,08-31 16:54:15.897  6992  6992 I SA      : [DM] getCountryCodeFromCSC : PL
08-31 16:54:15.897  6992  6992 I SA      : isChinaCountryCode : false
08-31 16:54:15.897  6992  6992 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 16:54:15.897  6992  6992 I SA      : [OR] == networkStateCheck true ==
,08-31 16:54:15.897   322   960 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 16:54:15.897   322   960 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,08-31 16:54:15.897   322   960 D DrmWidevineDash: Service_Initialize: starts!
08-31 16:54:15.897   322   960 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-31 16:54:15.897   322   960 D QSEECOMAPI: : App is not loaded in QSEE
08-31 16:54:15.897   322   960 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-31 16:54:15.897   322   960 E QSEECOMAPI: : Error::Loading image failed with ret = -1
,08-31 16:54:15.897   322   960 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-31 16:54:15.897   322   960 D QSEECOMAPI: : App is not loaded in QSEE
08-31 16:54:15.897   322   960 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-31 16:54:15.897   322   960 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-31 16:54:15.897   322   960 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-31 16:54:15.897   322   960 D QSEECOMAPI: : App is not loaded in QSEE
,08-31 16:54:15.907  6992  6992 I SA      : [OR] GetMyCountryZoneTask
,08-31 16:54:15.917  6992  6992 I SA      : [OR] onReceive END
,08-31 16:54:15.917  6992  6992 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,08-31 16:54:15.927  7024  7024 E Zygote  : v2
08-31 16:54:15.927  7024  7024 I libpersona: KNOX_SDCARD checking this for 10002
08-31 16:54:15.927  7024  7024 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:15.927  7024  7024 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.927   754  1737 I ActivityManager: Start proc 7024:com.sec.android.cloudagent/u0a2 for broadcast-5 com.sec.android.cloudagent/.detector.DetectorReceiver
08-31 16:54:15.927  7024  7024 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:15.927  7024  7024 E Zygote  : accessInfo : 0
08-31 16:54:15.927  7024  7024 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.cloudagent 
,08-31 16:54:15.937  6992  7023 I SA      : [SRS_HTTPURLCONNECTION] prepareGetMyCountryZone
,08-31 16:54:15.947   322   960 D QSEECOMAPI: : Loaded image: APP id = 2
,08-31 16:54:15.957   322   960 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-31 16:54:15.957   322   960 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef82000
08-31 16:54:15.957   322   960 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef82000
,08-31 16:54:15.957  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:15.957  7024  7024 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:15.967   322   960 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-31 16:54:15.967   322   960 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-31 16:54:15.967   322   960 D DrmWidevineDash: hlos api version =  10
08-31 16:54:15.967   322   960 D DrmWidevineDash: tz api version =  10
08-31 16:54:15.967   322   960 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-31 16:54:15.967   322   960 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-31 16:54:15.967  7036  7036 E Zygote  : v2
08-31 16:54:15.967  7036  7036 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:15.967  7036  7036 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:15.967  7036  7036 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:15.967  7036  7036 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:15.967  7036  7036 E Zygote  : accessInfo : 0
,08-31 16:54:15.977   754  2180 I ActivityManager: Start proc 7036:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.service.ContextAgentReceiver
,08-31 16:54:15.977  6992  7023 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:54:15.977  6992  7023 I SA      : [SSP] query invoked
,08-31 16:54:15.987   754  1496 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea74d32 7024:com.sec.android.cloudagent/u0a2}
,08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-31 16:54:15.997   322   960 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaf1af924
,08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1ddd858, dataLength=8
08-31 16:54:15.997   322   960 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-31 16:54:15.997  6979  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:54:15.997  6979  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:54:16.007   322   960 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xae9f5000, wrapped_rsa_key_length=1280
,08-31 16:54:16.007   308  1186 D EnterpriseController: netId is 0
08-31 16:54:16.007   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:54:16.007  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:16.007  7036  7036 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:16.007   322   960 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-31 16:54:16.007   322   960 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 16:54:16.017   754  3313 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:54:16.017   322  1217 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 16:54:16.017   322  1217 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-31 16:54:16.017   322  1217 I WVCdm   : CdmEngine::GenerateKeyRequest
08-31 16:54:16.017   322  1217 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb00bfc20, idLength=0xaf0adf2c
,08-31 16:54:16.017   754  1732 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d6d4a83 7036:com.samsung.android.sm/1000}
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-31 16:54:16.027   322  1217 D DrmWidevineDash: hlos api version =  10
08-31 16:54:16.027   322  1217 D DrmWidevineDash: tz api version =  10
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-31 16:54:16.027   322  1217 D WVCdm   : PrepareKeyRequest: nonce=258995105
08-31 16:54:16.027   322  1217 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d43c00
,08-31 16:54:16.027   322  1217 D DrmWidevineDash: message_length=1630, signature=0xaf5263c0, signature_length=2936725508
,08-31 16:54:16.027  7024  7024 W ResourcesManager: getTopLevelResources: /system/priv-app/CloudAgent/CloudAgent.apk / 1.0 running in com.sec.android.cloudagent rsrc of package null
,08-31 16:54:16.037  6992  7023 I SA      : [TPMU] GetMccFromDB : null
08-31 16:54:16.037  6992  7023 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 16:54:16.037  6992  7023 I SA      : [LBE] isSupportCheckDomainRegion : true
,08-31 16:54:16.037  6992  7023 I SA      : [TPM] isNoProxy(default) : true
,08-31 16:54:16.047   754  1732 I ActivityManager: Killing 5992:com.samsung.android.bbc.bbcagent/1000 (adj 15): DHA:empty #37
,08-31 16:54:16.047   754  3313 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-31 16:54:16.047   754  3313 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-31 16:54:16.047  7024  7024 W System  : ClassLoader referenced unknown path: /system/priv-app/CloudAgent/lib/arm
,08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):isSBSettingEnabled false
08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):isShipBuild true
08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):getDebugLevel 0x4f4c
08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):Smart Bonding Setting is false
08-31 16:54:16.067   754  3313 I System.out: Thread-173(ApacheHTTPLog):SmartBonding Setting is false, SHIP_BUILD is true, log to file is false, DBG is false, DEBUG_LEVEL (1-LOW, 2-MID, 3-HIGH) is 1
,08-31 16:54:16.067   308  1186 D EnterpriseController: netId is 0
08-31 16:54:16.067   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:54:16.067  6919  6962 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:54:16.077  7036  7036 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-31 16:54:16.077   754  1717 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.bbc.bbcagent, Auto Run ON
,08-31 16:54:16.077  6444  6514 I jxcore-log: ERROR runTests: 
08-31 16:54:16.077  6444  6514 I jxcore-log: 
,08-31 16:54:16.077  6444  6514 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:54:16.077  6444  6514 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:54:16.077  6444  6514 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:54:16.077  6444  6514 I jxcore-log: 
,08-31 16:54:16.087  6919  6962 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,08-31 16:54:16.087  6444  6514 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _functionName: 'loadFile',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _lineNumber: '26',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _columnNumber: '11',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:54:16.087  6444  6514 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _functionName: '',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _lineNumber: '38',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _columnNumber: '7',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:54:16.087  6444  6514 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _functionName: '',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _lineNumber: '35',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _columnNumber: '3',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:54:16.087  6444  6514 I jxcore-log:   { _fileName: 'module.js',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _lineNumber: '621',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _columnNumber: '8',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:54:16.087  6444  6514 I jxcore-log:   { _fileName: 'module.js',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _lineNumber: '651',
08-31 16:54:16.087  6444  6514 I jxcore-log:     _columnNumber: '1',
08-31 16:54:16.087  6444  6514 I jxcore-log:    
08-31 16:54:16.087  6444  6514 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:54:16.087  6444  6514 I jxcore-log: 
,08-31 16:54:16.097  6444  6514 E jxcore-log: Error: 
08-31 16:54:16.097  6444  6514 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:54:16.097  6444  6514 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:54:16.097  6444  6514 E jxcore-log: 
08-31 16:54:16.097  6992  7023 E File    : fail readDirectory() errno=2
08-31 16:54:16.097  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:54:16.097  6444  6514 I jxcore-log: 
08-31 16:54:16.097  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:54:16.097  6444  6514 I jxcore-log: 
,08-31 16:54:16.107  6444  6514 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:54:16.107  6444  6514 I jxcore-log: 
,08-31 16:54:16.117   322  1217 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-31 16:54:16.117   322   322 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6979)
,08-31 16:54:16.117   322   322 I WVCdm   : CdmEngine::CloseSession
08-31 16:54:16.117   322   322 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-31 16:54:16.117   322   322 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-31 16:54:16.117   322   322 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-31 16:54:16.117   322   322 D DrmWidevineDash: Service_Uninitialize: starts!
08-31 16:54:16.117   322   322 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-31 16:54:16.117   322   322 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
08-31 16:54:16.117   322   322 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-31 16:54:16.117   322   322 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-31 16:54:16.137  7056  7056 E Zygote  : v2
08-31 16:54:16.137  7056  7056 I libpersona: KNOX_SDCARD checking this for 10049
08-31 16:54:16.137  7056  7056 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:16.137   754   774 I ActivityManager: Start proc 7056:com.android.mms/u0a49 for broadcast-3 com.android.mms/.transaction.MessagingNotification
,08-31 16:54:16.137  7056  7056 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:16.137  7056  7056 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:16.137   754   774 I ActivityManager: Killing 6017:com.google.android.apps.docs/u0a97 (adj 15): DHA:empty #37
08-31 16:54:16.137  7056  7056 E Zygote  : accessInfo : 0
08-31 16:54:16.137  7056  7056 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-31 16:54:16.147   754  1676 I ActivityManager: Killing 6047:com.sec.android.automotive.drivelink/u0a98 (adj 15): DHA:empty #37
,08-31 16:54:16.157   754  1676 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ecbaa0 4288:com.wssyncmldm/1000}
,08-31 16:54:16.167  2021  7053 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 16:54:16.167  2021  6973 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 16:54:16.167   754   775 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.docs, Auto Run ON
,08-31 16:54:16.187  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:16.187  7056  7056 D ActivityThread: Added TimaKeyStore provider
08-31 16:54:16.187   754   774 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.automotive.drivelink, Auto Run ON
,08-31 16:54:16.187  6979  6990 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6979, getuid(): 10011
,08-31 16:54:16.197  4288  7070 I FOTA_AGENT: [com.samsung.android.app.fotaclient.llIlIIIIlIIIIIlIlIII(87/llIIIIlllllIIllIIllI)] Nothing to do action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:16.197   754  1704 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3520bff 3639:com.sec.spp.push/u0a37}
,08-31 16:54:16.207  3639  3639 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
08-31 16:54:16.207  3639  3639 E SPPClientService: [SystemStateMoniter] Current Time : 311278
,08-31 16:54:16.207   754  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9f90a7e 7056:com.android.mms/u0a49}
,08-31 16:54:16.207  7056  7056 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-31 16:54:16.217  2021  7053 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 16:54:16.217  2021  6973 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 16:54:16.217  3639  3639 E SPPClientService: [SystemStateMoniter] No Connect : false
,08-31 16:54:16.227   754  1414 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{eaffa6d 2666:android.process.media/u0a46}
,08-31 16:54:16.227  2666  2666 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:16.247   754  1676 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e771a23 3068:com.android.contacts/u0a19}
,08-31 16:54:16.247   754  1717 D SecContentProvider2: query(), uri = 15 selection = getAppBlockDownloadState
,08-31 16:54:16.247  2021  7053 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 16:54:16.247  2021  6973 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 16:54:16.247  7056  7056 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-31 16:54:16.257  2021  6973 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-31 16:54:16.257  7056  7056 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-31 16:54:16.257  7072  7072 E Zygote  : v2
08-31 16:54:16.267  7072  7072 I libpersona: KNOX_SDCARD checking this for 10199
08-31 16:54:16.267  7072  7072 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:16.267  7072  7072 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:16.267  7072  7072 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:16.267  2021  6973 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-31 16:54:16.267  7072  7072 E Zygote  : accessInfo : 0
08-31 16:54:16.267  7072  7072 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.photos 
,08-31 16:54:16.267   754  1676 I ActivityManager: Start proc 7072:com.google.android.apps.photos/u0a199 for broadcast-5 com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 16:54:16.287  7056  7056 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-31 16:54:16.297  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:16.297  7072  7072 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:16.297  7056  7085 D Mms/ArtClassLoader: init before art second
,08-31 16:54:16.297  7056  7056 D Mms/TelephonyPermission: start operation mode monitor
,08-31 16:54:16.297  7056  7056 D Mms/TelephonyPermission: User ID is null set current User Id
,08-31 16:54:16.307   754  1704 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3386fb 7072:com.google.android.apps.photos/u0a199}
,08-31 16:54:16.317  7072  7072 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.google.android.apps.photos rsrc of package null
,08-31 16:54:16.317  7056  7084 D Mms/ArtClassLoader: init before art first
,08-31 16:54:16.317  7056  7086 D Mms/ArtClassLoader: init before art third
,08-31 16:54:16.327  7056  7056 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-31 16:54:16.327  7056  7056 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-31 16:54:16.327  7056  7086 D Mms/ArtClassLoader: init [DONE] art
,08-31 16:54:16.337  7072  7072 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 16:54:16.347  7056  7056 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,08-31 16:54:16.347  7056  7056 D Mms/TelephonyPermission: isDefault true
08-31 16:54:16.347  7056  7056 D Mms/MmsApp: onCreate() com.android.mms
,08-31 16:54:16.386  7056  7056 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-31 16:54:16.396  7056  7056 D Mms/MmsApp: [start]    initCountryIso consume time = 116.224738
,08-31 16:54:16.406   754  1732 D CountryDetector: The first listener is added
,08-31 16:54:16.417  7056  7056 D Mms/MmsApp: [end]    initCountryIso consume time = 12.619324
,08-31 16:54:16.417  7056  7056 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.200469
,08-31 16:54:16.427  7056  7056 D Mms/MmsConfig: before partial update
,08-31 16:54:16.497   754  1717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 16:54:16.517  7056  7084 D Mms/ArtClassLoader: init [DONE] art
,08-31 16:54:16.527  7056  7056 D Mms/MmsConfig: Load Resize quality : 80
,08-31 16:54:16.577  2021  6973 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-31 16:54:16.577  7056  7056 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-31 16:54:16.577  7056  7056 D EasySignUpManager_1.0.5: isAuth is false
08-31 16:54:16.577  7056  7056 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-31 16:54:16.577  7056  7056 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-31 16:54:16.577  7056  7056 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-31 16:54:16.587  7056  7056 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-31 16:54:16.587  7056  7056 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-31 16:54:16.587  7056  7056 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-31 16:54:16.587  7056  7056 D EasySignUpManager_1.0.5: isAuth is false
08-31 16:54:16.587  7056  7056 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-31 16:54:16.587  7056  7056 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-31 16:54:16.587  7056  7085 D Mms/ArtClassLoader: init [DONE] art
,08-31 16:54:16.597  1705  1720 D TP/MmsSmsProvider: query, match:2117, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.597  1705  1720 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 2.754 ms
,08-31 16:54:16.617  7056  7056 E CscParser: mps_code.dat does not exist
08-31 16:54:16.617  7056  7056 E CscParser: customer_path =/system/csc/customer.xml
08-31 16:54:16.617  7056  7056 E CscParser: fileName + /system/csc/customer.xml
,08-31 16:54:16.637  7056  7056 E CscParser: mps_code.dat does not exist
08-31 16:54:16.637  7056  7056 E CscParser: customer_path =/system/csc/customer.xml
08-31 16:54:16.637  7056  7056 E CscParser: fileName + /system/csc/customer.xml
,08-31 16:54:16.657  7056  7056 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-31 16:54:16.657  7056  7056 D Mms/MmsConfig:  enable multiwindow = true
,08-31 16:54:16.657  7056  7056 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-31 16:54:16.657  7056  7056 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-31 16:54:16.657  7056  7056 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-31 16:54:16.657  7056  7056 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-31 16:54:16.657  7056  7056 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-31 16:54:16.657  7056  7056 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-31 16:54:16.657  7056  7056 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-31 16:54:16.667  7056  7056 D Mms/MmsConfig: [end]    init() consume time = 249.733958
,08-31 16:54:16.667  7056  7056 D Mms/Contact: [start]    init() consume time = 3.904271
,08-31 16:54:16.687  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:54:16.687  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:54:16.687   308  1186 D EnterpriseController: netId is 0
08-31 16:54:16.687   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 16:54:16.687  7056  7056 D Mms/Contact: [end]    init consume time = 20.046562
,08-31 16:54:16.687  1705  1930 D TP/MmsSmsProvider: query, match:13, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.697  1705  1930 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.305 ms
,08-31 16:54:16.697  7056  7094 D Mms/DraftCache: [start]    rebuildCache consume time = 8.905573
,08-31 16:54:16.697  7056  7056 D Mms:transaction: roaming -> false (slotId = 0)
08-31 16:54:16.697  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-31 16:54:16.697  7056  7056 D Mms:transaction: auto download without roaming -> true
08-31 16:54:16.697  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-31 16:54:16.697  7056  7056 D Mms:transaction: roaming -> false (slotId = 1)
08-31 16:54:16.697  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-31 16:54:16.697  7056  7056 D Mms:transaction: auto download without roaming -> true
08-31 16:54:16.697  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-31 16:54:16.697  7056  7056 D Mms:transaction: auto download during roaming secondary -> false
08-31 16:54:16.697  7056  7056 D Mms:transaction: mAutoDownload ------> true
,08-31 16:54:16.697   754  3313 I System.out: Category Thread calls detatch()
,08-31 16:54:16.707  1705  1716 D TP/MmsSmsProvider: query, match:12, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.707  1705  1716 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.006 ms
,08-31 16:54:16.707  7056  7094 D Mms/DraftCache: [end]    rebuildCache consume time = 13.817552
,08-31 16:54:16.727  7056  7056 D ComposerPerformance: 1472655256738 ms / [DONE] Composer constructor
,08-31 16:54:16.727  7056  7056 D CII     : Log Level [5]
,08-31 16:54:16.727  2021  6973 I qtaguid : Tagging socket 56 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2021, getuid(): 10011
08-31 16:54:16.727  7056  7056 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-31 16:54:16.737  7056  7056 I Mms/ReservationManager: ReservationManager()
,08-31 16:54:16.737  6979  6990 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6979, getuid(): 10011
08-31 16:54:16.737  7056  7056 I Mms/ReservationManager: resetAfterConnected()
,08-31 16:54:16.737  7056  7097 D Mms/Conversation: [start]    init() consume time = 26.130156
,08-31 16:54:16.737  1705  1930 D TP/MmsSmsProvider: delete, match:1, calling pid = 7056
08-31 16:54:16.737  1705  1930 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-31 16:54:16.737  1705  1930 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-31 16:54:16.737  1705  1930 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-31 16:54:16.737  1705  1930 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-31 16:54:16.737  1705  1930 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-31 16:54:16.747  1705  1930 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-31 16:54:16.757  1705  2517 D TP/MmsSmsProvider: query, match:7, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.757  1705  2517 D TP/MmsSmsProvider: query, match 7:Elapsed time : 1.166 ms
,08-31 16:54:16.757  1705  1930 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-31 16:54:16.757  1705  1930 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-31 16:54:16.757  1705  1930 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-31 16:54:16.757  1705  1930 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 2.630 ms
08-31 16:54:16.757  1705  1930 D TP/MmsSmsProvider: need read changed broadcast:false
,08-31 16:54:16.757  7056  7056 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-31 16:54:16.757  7056  7097 D Mms/Conversation: [end]    init consume time = 21.885677
,08-31 16:54:16.757  7056  7056 D Mms/MmsApp: [end]    onCreate() consume time = 2.824167
08-31 16:54:16.757  6730  6730 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 16:54:16.757  7056  7056 D Mms/MmsApp: [end]    onCreate() consume time = 0.075
,08-31 16:54:16.767  7056  7097 D Mms/MessagingNotification: [start]    init() consume time = 1.307032
,08-31 16:54:16.767  7056  7097 D Mms/MessagingNotification: [end]    init consume time = 1.375572
,08-31 16:54:16.767  7056  7100 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.852605
,08-31 16:54:16.767  7056  7101 D Mms/Synchronizer: [start]    doSync consume time = 2.817291
,08-31 16:54:16.767   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b6209e6 6883:com.sec.knox.switcher/1000}
08-31 16:54:16.777  7056  7056 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
08-31 16:54:16.777  1705  1720 D TP/MmsSmsProvider: query, match:0, calling pid = 7056, accessRestricted = false
08-31 16:54:16.777  1705  1720 V TP/MmsSmsProvider: getSimpleConversations entered.
08-31 16:54:16.777  1705  1720 D TP/MmsSmsProvider: query, match 0:Elapsed time : 0.752 ms
08-31 16:54:16.777  7056  7056 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-31 16:54:16.777  7056  7056 D Mms:transaction: roaming -> false (slotId = 0)
08-31 16:54:16.777  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-31 16:54:16.777  7056  7056 D Mms:transaction: auto download without roaming -> true
08-31 16:54:16.777  7056  7056 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-31 16:54:16.777  7056  7056 D Mms:transaction: mAutoDownload ------> true
08-31 16:54:16.777  1705  1716 D TP/MmsSmsProvider: update, match:300, calling pid = 7056
08-31 16:54:16.777  1705  1716 V TP/MmsSmsProvider: syncDBData start
,08-31 16:54:16.787  6883  6883 I usagelog: received in receiver
08-31 16:54:16.787  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.TIME_SET myUserId=0
08-31 16:54:16.787  6883  6883 I KnoxUsageLogPro: premStatus:2
08-31 16:54:16.787  1705  1716 V TP/MmsSmsProvider: syncDBData sms end
,08-31 16:54:16.787  6883  6883 I KnoxUsageLogPro: isEulaShown : false
,08-31 16:54:16.787  6883  6883 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-31 16:54:16.787  1705  1716 V TP/MmsSmsProvider: syncDBData mms end
,08-31 16:54:16.787  1705  1930 D TP/MmsSmsProvider: query, match:400, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.787  1705  1716 V TP/MmsSmsProvider: syncDBData end
,08-31 16:54:16.787  1705  1716 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.301 ms
,08-31 16:54:16.787  7056  7100 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 22.559114
,08-31 16:54:16.797  7102  7102 E Zygote  : v2
08-31 16:54:16.797  7102  7102 I libpersona: KNOX_SDCARD checking this for 10112
08-31 16:54:16.797  7102  7102 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:16.797  7102  7102 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:16.797  7102  7102 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:16.797  7102  7102 E Zygote  : accessInfo : 0
,08-31 16:54:16.797  7102  7102 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.GeoLookout 
,08-31 16:54:16.817   754  1732 I ActivityManager: Start proc 7102:com.sec.android.GeoLookout/u0a112 for broadcast-3 com.sec.android.GeoLookout/.widget.SafetyCareWidget
,08-31 16:54:16.817   754  1732 I ActivityManager: Killing 6072:com.vlingo.midas/u0a32 (adj 15): DHA:empty #37
,08-31 16:54:16.837  7056  7101 D Mms/Synchronizer: [end]    doSync consume time = 47.186615
,08-31 16:54:16.847  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:16.847  7102  7102 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:16.847   754  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d64bcaf 7102:com.sec.android.GeoLookout/u0a112}
,08-31 16:54:16.857   754  1298 D ActivityManager: isAutoRunBlockedApp:: com.vlingo.midas, Auto Run ON
,08-31 16:54:16.857  7102  7102 W ResourcesManager: getTopLevelResources: /system/app/GeoLookout/GeoLookout.apk / 1.0 running in com.sec.android.GeoLookout rsrc of package null
,08-31 16:54:16.867  6777  6794 D BadgeProvider: query, [selection] : package=?
,08-31 16:54:16.867  7056  7097 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-31 16:54:16.887  6549  6549 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
08-31 16:54:16.887  1705  1930 D TP/SmsProvider: query,matched:26, calling pid = 7056
08-31 16:54:16.887  1705  1930 D TP/SmsProvider: query, match 26:Elapsed time : 1.161 ms
08-31 16:54:16.887  7102  7102 W System  : ClassLoader referenced unknown path: /system/app/GeoLookout/lib/arm
,08-31 16:54:16.887   308  1181 D Netd    : Iface wlan0 link up
,08-31 16:54:16.887   754   851 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:54:16.887   754  1327 D WifiP2pService: InactiveState{ what=147461 }
08-31 16:54:16.887   754   851 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:54:16.887   754  1327 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-31 16:54:16.887   754  1327 D WifiP2pService: DefaultState{ what=147461 }
,08-31 16:54:16.897  1705  2517 D TP/MmsSmsProvider: query, match:6, calling pid = 7056, accessRestricted = false
,08-31 16:54:16.907  1705  2517 D TP/MmsSmsProvider: query, match 6:Elapsed time : 4.281 ms
,08-31 16:54:16.907  2021  6973 I qtaguid : Tagging socket 58 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2021, getuid(): 10011
,08-31 16:54:16.917  7102  7102 D GeoLookout: H: CVccN35zteEo7uWDJ0cWTbsuAnPmDHBG4p+ywI/gN9j8cnobeOUVeZgeK/+93LDsu89EQ821mpIbyCdOp1WNyQ==
,08-31 16:54:16.917  7102  7102 W GeoLookout: H: zOXtzplbN+8pOR8lXMN+zi7kXd24xZXWuIjld2hFBv004DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,08-31 16:54:16.917  7102  7102 I GeoLookout: H: zOXtzplbN+8pOR8lXMN+zm/QpcPruwLHDXz9jGj9RlOeGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,08-31 16:54:16.927  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,08-31 16:54:16.937  7116  7116 E Zygote  : v2
08-31 16:54:16.937  7116  7116 I libpersona: KNOX_SDCARD checking this for 10024
08-31 16:54:16.937  7116  7116 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:16.937  7116  7116 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:16.937  7116  7116 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:16.937   754   774 I ActivityManager: Start proc 7116:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-31 16:54:16.937  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,08-31 16:54:16.937  7116  7116 E Zygote  : accessInfo : 0
,08-31 16:54:16.937  7116  7116 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-31 16:54:16.947  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,08-31 16:54:16.957  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,08-31 16:54:16.957  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:16.957  7116  7116 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:16.957   754  1496 I ActivityManager: Killing 6086:com.samsung.android.app.filterinstaller/1000 (adj 15): DHA:empty #37
,08-31 16:54:16.967  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,08-31 16:54:16.967  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,08-31 16:54:16.967  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1Gkj0KYZpO99f1rsYZnglZtCc+mJqVQceay8W/Aon4dQ==
,08-31 16:54:16.967  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3NyUiHu5cWdT4SPPZ0OxqJQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,08-31 16:54:16.967  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2G1kMmI09JBmwwj0mFkR2L4tvU5wsp5Dwccfz++DFQoQ==
,08-31 16:54:16.977  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2sH9Musae3FSSYRxL/dVLnM4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,08-31 16:54:16.977  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2C8R3qbaE3iKzVn5nYcXDsaba68PSLy9IpSfBXGHVgOg==
,08-31 16:54:16.977  7116  7116 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-31 16:54:16.977   754  1298 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d64bcaf 7102:com.sec.android.GeoLookout/u0a112}
,08-31 16:54:16.987  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,08-31 16:54:16.987  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDkvkgPm5dotWx3IPNd1bDZ3HtYRASO8LE3XMTl+CWy7mA0iuhqjXXzZB9tx1thU84s=
,08-31 16:54:16.987  7102  7102 D GeoLookout: H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,08-31 16:54:16.987   754  1713 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.filterinstaller, Auto Run ON
,08-31 16:54:17.007  7131  7131 E Zygote  : v2
08-31 16:54:17.007  7131  7131 I libpersona: KNOX_SDCARD checking this for 10148
08-31 16:54:17.007  7131  7131 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:17.007  7131  7131 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:17.007  7131  7131 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:17.007   754  1298 I ActivityManager: Start proc 7131:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 for broadcast-3 com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider
08-31 16:54:17.007  7131  7131 E Zygote  : accessInfo : 0
08-31 16:54:17.007   754  1298 I ActivityManager: Killing 6102:com.samsung.helphub/1000 (adj 15): DHA:empty #37
08-31 16:54:17.007  7131  7131 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.widgetapp.SPlannerAppWidget 
,08-31 16:54:17.007  7116  7116 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-31 16:54:17.027   754  1717 D ActivityManager: isAutoRunBlockedApp:: com.samsung.helphub, Auto Run ON
,08-31 16:54:17.037  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:17.037  7131  7131 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:17.047   754  1676 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1ca74cb 7131:com.sec.android.widgetapp.SPlannerAppWidget/u0a148}
,08-31 16:54:17.057  7131  7131 W ResourcesManager: getTopLevelResources: /system/app/SPlannerWidget_M_OS_UPG/SPlannerWidget_M_OS_UPG.apk / 1.0 running in com.sec.android.widgetapp.SPlannerAppWidget rsrc of package null
,08-31 16:54:17.077  6979  6990 I qtaguid : Untagging socket 21
,08-31 16:54:17.077  7072  7072 W Primes  : Memory instrumentations are turned off.
,08-31 16:54:17.087  7131  7131 W System  : ClassLoader referenced unknown path: /system/app/SPlannerWidget_M_OS_UPG/lib/arm
,08-31 16:54:17.087  7072  7072 W Primes  : Timer instrumentations are turned off.
,08-31 16:54:17.087  7116  7116 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-31 16:54:17.087  7072  7072 W Primes  : Crash monitoring is turned off.
,08-31 16:54:17.097  7072  7072 W Primes  : Network monitoring is turned off.
,08-31 16:54:17.097  7072  7072 W Primes  : Package metrics are turned off by default
,08-31 16:54:17.097  7056  7097 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-31 16:54:17.117   754  2180 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c3386fb 7072:com.google.android.apps.photos/u0a199}
,08-31 16:54:17.117  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-31 16:54:17.127  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-31 16:54:17.137  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-31 16:54:17.137   754  1590 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{44e3643 6558:com.samsung.android.securitylogagent/1000}
,08-31 16:54:17.137  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-31 16:54:17.137  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 16:54:17.137  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:54:17.137  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:54:17.137  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-31 16:54:17.137  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-31 16:54:17.137   754  1713 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:17.137  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-31 16:54:17.147   754  1704 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-31 16:54:17.147   754  1676 I ActivityManager: Start proc 7147:com.google.android.apps.magazines/u0a127 for broadcast-5 com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
08-31 16:54:17.147  7147  7147 E Zygote  : v2
08-31 16:54:17.147  7147  7147 I libpersona: KNOX_SDCARD checking this for 10127
08-31 16:54:17.147  7147  7147 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:17.147  7147  7147 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:17.147  7147  7147 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-31 16:54:17.147   754  1676 I ActivityManager: Killing 6114:com.samsung.android.app.mirrorlink/1000 (adj 15): DHA:empty #37
08-31 16:54:17.147  7147  7147 E Zygote  : accessInfo : 0
08-31 16:54:17.147  7147  7147 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.magazines 
08-31 16:54:17.147  6979  6990 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-31 16:54:17.147  6979  6990 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-31 16:54:17.157  7116  7116 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-31 16:54:17.167   754  1298 I ActivityManager: Start proc 7158:com.sec.android.app.taskmanager/u0a175 for broadcast-3 com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver
,08-31 16:54:17.167  7158  7158 E Zygote  : v2
08-31 16:54:17.167  7158  7158 I libpersona: KNOX_SDCARD checking this for 10175
08-31 16:54:17.167  7158  7158 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:17.167  7158  7158 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:17.167  7158  7158 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.167  7158  7158 E Zygote  : accessInfo : 0
,08-31 16:54:17.167  7158  7158 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.taskmanager 
,08-31 16:54:17.167   754  1298 I ActivityManager: Killing 6128:com.sec.kidsplat.installer/u0a165 (adj 15): DHA:empty #37
,08-31 16:54:17.187  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:17.187  7147  7147 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:17.197  7158  7158 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:17.197  7158  7158 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:17.217   754  1717 V BroadcastQueue: [deferred] Process cur broadcast BroadcastRecord{666a73b u-1 android.net.conn.CONNECTIVITY_CHANGE qIdx=3}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b8992a7 7147:com.google.android.apps.magazines/u0a127}
,08-31 16:54:17.227  7147  7147 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,08-31 16:54:17.227   754  2180 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.mirrorlink, Auto Run ON
,08-31 16:54:17.237   754  1713 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2867bf2 7158:com.sec.android.app.taskmanager/u0a175}
,08-31 16:54:17.237   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.sec.kidsplat.installer, Auto Run ON
,08-31 16:54:17.247  7158  7158 W ResourcesManager: getTopLevelResources: /system/app/TaskManager/TaskManager.apk / 1.0 running in com.sec.android.app.taskmanager rsrc of package null
,08-31 16:54:17.267  2062  2062 E audit   : type=1400 msg=audit(1472655257.267:289): avc:  denied  { execmod } for  pid=7067 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:54:17.267  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.267  2062  2062 E audit   : type=1300 msg=audit(1472655257.267:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f5b000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=7067 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:54:17.267  2062  2062 E audit   : type=1327 msg=audit(1472655257.267:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-31 16:54:17.267  2062  2062 E audit   : type=1320 msg=audit(1472655257.267:289): 
,08-31 16:54:17.267  7158  7158 W System  : ClassLoader referenced unknown path: /system/app/TaskManager/lib/arm
,08-31 16:54:17.277  7147  7147 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 16:54:17.287  7175  7175 E Zygote  : v2
08-31 16:54:17.287  7175  7175 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:54:17.287  7175  7175 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:17.287  7175  7175 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:17.287  7175  7175 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.297   754  1298 I ActivityManager: Start proc 7175:com.qualcomm.timeservice/1000 for broadcast-3 com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-31 16:54:17.297  7175  7175 E Zygote  : accessInfo : 0
,08-31 16:54:17.317  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:54:17.317  7175  7175 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:17.317  2062  2062 E audit   : type=1400 msg=audit(1472655257.317:290): avc:  denied  { execmod } for  pid=7067 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:54:17.317  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.327  2062  2062 E audit   : type=1300 msg=audit(1472655257.317:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f1b000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=7067 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:54:17.327  2062  2062 E audit   : type=1327 msg=audit(1472655257.317:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-31 16:54:17.327  2062  2062 E audit   : type=1320 msg=audit(1472655257.317:290): 
,08-31 16:54:17.327   754   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c32b243 7175:com.qualcomm.timeservice/1000}
,08-31 16:54:17.337  7175  7175 W ResourcesManager: getTopLevelResources: /system/app/TimeService/TimeService.apk / 1.0 running in com.qualcomm.timeservice rsrc of package null
,08-31 16:54:17.347   754  1704 I ActivityManager: Killing 6140:com.sec.android.app.sbrowser/u0a142 (adj 15): DHA:empty #37
,08-31 16:54:17.367   754  1496 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sbrowser, Auto Run ON
,08-31 16:54:17.367  2062  2062 E audit   : type=1400 msg=audit(1472655257.367:291): avc:  denied  { execmod } for  pid=7067 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-31 16:54:17.367  2062  2062 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.367  2062  2062 E audit   : type=1300 msg=audit(1472655257.367:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f1b000 a1=51000 a2=5 a3=4 items=0 ppid=3432 ppcomm=adbd pid=7067 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-31 16:54:17.367  2062  2062 E audit   : type=1327 msg=audit(1472655257.367:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-31 16:54:17.367  2062  2062 E audit   : type=1320 msg=audit(1472655257.367:291): 
08-31 16:54:17.367  7067  7067 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 16:54:17.387  7067  7067 D AndroidRuntime: CheckJNI is OFF
,08-31 16:54:17.387  7067  7067 D AndroidRuntime: readGMSProperty: start
08-31 16:54:17.387  7067  7067 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:54:17.387  7067  7067 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:54:17.387  7067  7067 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:54:17.387  7067  7067 D AndroidRuntime: readGMSProperty: end
08-31 16:54:17.387  7067  7067 D AndroidRuntime: addProductProperty: start
,08-31 16:54:17.387  7067  7067 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 16:54:17.387  7067  7067 W art     : af0cd000-b1ff3000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:54:17.387  7067  7067 W art     : b1ff3000-b4262000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:54:17.387  7067  7067 W art     : b4262000-b4263000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
08-31 16:54:17.387  7067  7067 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
08-31 16:54:17.387  7067  7067 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
08-31 16:54:17.387  7067  7067 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
08-31 16:54:17.387  7067  7067 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-31 16:54:17.387  7067  7067 W art     : b47c0000-b47e9000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
08-31 16:54:17.387  7067  7067 W art     : b47e9000-b47ec000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:54:17.387  7067  7067 W art     : b47ec000-b47ed000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:54:17.387  7067  7067 W art     : b47ed000-b47ee000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-31 16:54:17.387  7067  7067 W art     : b47ee000-b47ef000 r--p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b47ef000-b480f000 r--s 00000000 00:0b 6700       /dev/__properties__
08-31 16:54:17.387  7067  7067 W art     : b480f000-b5220000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
08-31 16:54:17.387  7067  7067 W art     : b5220000-b5221000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5221000-b526a000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
08-31 16:54:17.387  7067  7067 W art     : b526a000-b526b000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
08-31 16:54:17.387  7067  7067 W art     : b526b000-b5273000 rw-p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5273000-b52a8000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:54:17.387  7067  7067 W art     : b52a8000-b52a9000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b52a9000-b52aa000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:54:17.387  7067  7067 W art     : b52aa000-b52ab000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
08-31 16:54:17.387  7067  7067 W art     : b52ab000-b5303000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
08-31 16:54:17.387  7067  7067 W art     : b5303000-b5304000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5304000-b5305000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
08-31 16:54:17.387  7067  7067 W art     : b5305000-b5306000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
08-31 16:54:17.387  7067  7067 W art     : b5307000-b530d000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:54:17.387  7067  7067 W art     : b530d000-b530e000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:54:17.387  7067  7067 W art     : b530e000-b530f000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-31 16:54:17.387  7067  7067 W art     : b530f000-b5311000 rw-p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5312000-b531c000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 16:54:17.387  7067  7067 W art     : b531c000-b531f000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-31 16:54:17.387  7067  7067 W art     : b531f000-b5320000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-,31 16:54:17.387  7067  7067 W art     : b5321000-b5338000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:54:17.387  7067  7067 W art     : b5338000-b5339000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5339000-b533a000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:54:17.387  7067  7067 W art     : b533a000-b533b000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-31 16:54:17.387  7067  7067 W art     : b533c000-b5346000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:54:17.387  7067  7067 W art     : b5346000-b5347000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:54:17.387  7067  7067 W art     : b5347000-b5348000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-31 16:54:17.387  7067  7067 W art     : b5348000-b534c000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:54:17.387  7067  7067 W art     : b534c000-b534d000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:54:17.387  7067  7067 W art     : b534d000-b534e000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-31 16:54:17.387  7067  7067 W art     : b534e000-b5364000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-31 16:54:17.387  7067  7067 W art     : b5364000-b5365000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-31 16:54:17.387  7067  7067 W art     : b5365000-b5366000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-31 16:54:17.387  7067  7067 W art     : b5366000-b5373000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:54:17.387  7067  7067 W art     : b5373000-b5374000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:54:17.387  7067  7067 W art     : b5374000-b5375000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-31 16:54:17.387  7067  7067 W art     : b5375000-b53d5000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-31 16:54:17.387  7067  7067 W art     : b53d5000-b53d8000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-31 16:54:17.387  7067  7067 W art     : b53d8000-b53dc000 rw-p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b53dc000-b543d000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-31 16:54:17.387  7067  7067 W art     : b543d000-b543e000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-31 16:54:17.387  7067  7067 W art     : b543e000-b548d000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:54:17.387  7067  7067 W art     : b548d000-b548f000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:54:17.387  7067  7067 W art     : b548f000-b5490000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-31 16:54:17.387  7067  7067 W art     : b5490000-b5491000 rw-p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5491000-b5498000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 16:54:17.387  7067  7067 W art     : b5498000-b5499000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-31 16:54:17.387  7067  7067 W art     : b5499000-b549a000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-31 16:54:17.387  7067  7067 W art     : avc_common.so
08-31 16:54:17.387  7067  7067 W art     : b549b000-b549e000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 16:54:17.387  7067  7067 W art     : b549e000-b549f000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-31 16:54:17.387  7067  7067 W art     : b549f000-b54a0000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-31 16:54:17.387  7067  7067 W art     : enc_common.so
08-31 16:54:17.387  7067  7067 W art     : b54a1000-b54a5000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-31 16:54:17.387  7067  7067 W art     : b54a5000-b54a6000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b54a6000-b54a7000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-31 16:54:17.387  7067  7067 W art     : b54a7000-b54a8000 rw-p 00005000 b3:17 2510       /syste
08-31 16:54:17.387  7067  7067 W art     : m/lib/libpowermanager.so
08-31 16:54:17.387  7067  7067 W art     : b54a9000-b54c6000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:54:17.387  7067  7067 W art     : b54c6000-b54c7000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:54:17.387  7067  7067 W art     : b54c7000-b54c8000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
08-31 16:54:17.387  7067  7067 W art     : b54c9000-b54ce000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:54:17.387  7067  7067 W art     : b54ce000-b54cf000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:54:17.387  7067  7067 W art     : b54cf000-b54d0000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
08-31 16:54:17.387  7067  7067 W art     : b54d1000-b5502000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:54:17.387  7067  7067 W art     : b5502000-b5503000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5503000-b5506000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:54:17.387  7067  7067 W art     : b5506000-b5507000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
08-31 16:54:17.387  7067  7067 W art     : b5508000-b5543000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-31 16:54:17.387  7067  7067 W art     : b5543000-b5544000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-31 16:54:17.387  7067  7067 W art     : b5544000-b5545000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-31 16:54:17.387  7067  7067 W art     : b5546000-b554d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:54:17.387  7067  7067 W art     : b554d000-b554e000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b554e000-b554f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:54:17.387  7067  7067 W art     : b554f000-b5550000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-31 16:54:17.387  7067  7067 W art     : b5550000-b5551000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.387  7067  7067 W art     : b5551000-b5568000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:54:17.387  7067  7067 W art     : b5568000-b5569000 ---p 00000000 00:00 0 
08-31 16:54:17.387  7067  7067 W art     : b5569000-b556c000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:54:17.397  7067  7067 W art     : b556c000-b556d000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-31 16:54:17.397  7067  7067 W art     : b556d000-b558c000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
08-31 16:54:17.397  7067  7067 W art     : b558c000-b558d000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
08-31 16:54:17.397  7067  7067 W art     : b558d000-b558e000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
08-31 16:54:17.397  7067  7067 W art     : b558e000-b55cc000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
08-31 16:54:17.397  7067  7067 W art     : b55cc000-b55cd000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b55cd000-b55cf000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
08-31 16:54:17.397  7067  7067 W art     : b55cf000-b55d0000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
08-31 16:54:17.397  7067  7067 W art     : b55d1000-b55d8000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:54:17.397  7067  7067 W art     : b55d8000-b55d9000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:54:17.397  7067  7067 W art     : b55d9000-b55da000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-31 16:54:17.397  7067  7067 W art     : b55db000-b55de000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:54:17.397  7067  7067 W art     : b55de000-b55df000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:54:17.397  7067  7067 W art     : b55df000-b55e0000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-31 16:54:17.397  7067  7067 W art     : b55e0000-b55e6000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b55e6000-b55e7000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b55e7000-b55e8000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b55e8000-b55e9000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b55e9000-b55f2000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:54:17.397  7067  7067 W art     : b55f2000-b55f3000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:54:17.397  7067  7067 W art     : b55f3000-b55f4000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-31 16:54:17.397  7067  7067 W art     : b55f4000-b5685000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:54:17.397  7067  7067 W art     : b5685000-b5686000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5686000-b5691000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:54:17.397  7067  7067 W art     : b5691000-b5692000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
08-31 16:54:17.397  7067  7067 W art     : b5693000-b56a5000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-31 16:54:17.397  7067  7067 W art     : b56a5000-b56a6000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-31 16:54:17.397  7067  7067 W art     : b56a6000-b56a7000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-31 16:54:17.397  7067  7067 W art     : b56a8000-b56ad000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:54:17.397  7067  7067 W art     : b56ad000-b56ae000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:54:17.397  7067  7067 W art     : b56ae000-b56af000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-31 16:54:17.397  7067  7067 W art     : b56b0000-b571d000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:54:17.397  7067  7067 W art     : b571d000-b571e000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b571e000-b5720000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:54:17.397  7067  7067 W art     : b5720000-b5721000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-31 16:54:17.397  7067  7067 W art     : b5721000-b5722000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5722000-b5729000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:54:17.397  7067  7067 W art     : b5729000-b572a000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:54:17.397  7067  7067 W art     : b572a000-b572b000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-31 16:54:17.397  7067  7067 W art     : b572c000-b57ac000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:54:17.397  7067  7067 W art     : b57ac000-b57ad000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b57ad000-b57ae000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:54:17.397  7067  7067 W art     : b57ae000-b57af000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-31 16:54:17.397  7067  7067 W art     : b57af000-b57c6000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b57c6000-b57fd000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:54:17.397  7067  7067 W art     : b57fd000-b57fe000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:54:17.397  7067  7067 W art     : b57fe000-b57ff000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-31 16:54:17.397  7067  7067 W art     : b57ff000-b581b000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:54:17.397  7067  7067 W art     : b581b000-b581c000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:54:17.397  7067  7067 W art     : b581c000-b581d000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-31 16:54:17.397  7067  7067 W art     : b581e000-b587f000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
08-31 16:54:17.397  7067  7067 W art     : b587f000-b5881000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
08-31 16:54:17.397  7067  7067 W art     : b5881000-b5882000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
08-31 16:54:17.397  7067  7067 W art     : b5883000-b58a8000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
08-31 16:54:17.397  7067  7067 W art     : b58a8000-b58a9000 r--p 00024000 b3:17 126        /system/lib/libpng.so
08-31 16:54:17.397  7067  7067 W art     : b58a9000-b58aa000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
08-31 16:54:17.397  7067  7067 W art     : b58ab000-b58b3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:54:17.397  7067  7067 W art     : b58b3000-b58b5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:54:17.397  7067  7067 W art     : b58b5000-b58b6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-31 16:54:17.397  7067  7067 W art     : b58b7000-b58ba000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-31 16:54:17.397  7067  7067 W art     : b58ba000-b58bb000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-31 16:54:17.397  7067  7067 W art     : b58bb000-b58bc000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-31 16:54:17.397  7067  7067 W art     : b58bc000-b58c0000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:54:17.397  7067  7067 W art     : b58c0000-b58c1000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b58c1000-b58c2000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:54:17.397  7067  7067 W art     : b58c2000-b58c3000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-31 16:54:17.397  7067  7067 W art     : b58c3000-b58d3000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-31 16:54:17.397  7067  7067 W art     : b58d3000-b58d4000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-31 16:54:17.397  7067  7067 W art     : b58d4000-b58d5000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-31 16:54:17.397  7067  7067 W art     : b58d5000-b591b000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b591b000-b5924000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
08-31 16:54:17.397  7067  7067 W art     : b5924000-b5925000 r--p 00008000 b3:17 982        /system/lib/libbase.so
08-31 16:54:17.397  7067  7067 W art     : b5925000-b5926000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
08-31 16:54:17.397  7067  7067 W art     : b5927000-b592c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-31 16:54:17.397  7067  7067 W art     : b592c000-b592d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-31 16:54:17.397  7067  7067 W art     : b592d000-b592e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-31 16:54:17.397  7067  7067 W art     : b592e000-b5931000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:54:17.397  7067  7067 W art     : b5931000-b5932000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5932000-b5933000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:54:17.397  7067  7067 W art     : b5933000-b5934000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
08-31 16:54:17.397  7067  7067 W art     : b5934000-b5935000 rw-p 00000000 00:00 0          [anon:linker_alloc_vect
08-31 16:54:17.397  7067  7067 W art     : or]
08-31 16:54:17.397  7067  7067 W art     : b5935000-b594d000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 16:54:17.397  7067  7067 W art     : b594d000-b594e000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b594e000-b594f000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
08-31 16:54:17.397  7067  7067 W art     : b594f000-b5950000 rw-p 00019000 b3:
08-31 16:54:17.397  7067  7067 W art     : 17 2789       /system/lib/libstagefright_foundation.so
08-31 16:54:17.397  7067  7067 W art     : b5951000-b5aeb000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
08-31 16:54:17.397  7067  7067 W art     : b5aeb000-b5aec000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5aec000-b5af9000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
08-31 16:54:17.397  7067  7067 W art     : b5af9000-b5afa000 rw-p 001a7000 b3:17 604        /system/
08-31 16:54:17.397  7067  7067 W art     : lib/libstagefright.so
08-31 16:54:17.397  7067  7067 W art     : b5afa000-b5afe000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-31 16:54:17.397  7067  7067 W art     : b5afe000-b5aff000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5aff000-b5b00000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-31 16:54:17.397  7067  7067 W art     : b5b00000-b5b01000 rw-p 00005000 b3:17 2676       /system/lib/libp
08-31 16:54:17.397  7067  7067 W art     : ersona.so
08-31 16:54:17.397  7067  7067 W art     : b5b01000-b5b14000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:54:17.397  7067  7067 W art     : b5b14000-b5b15000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:54:17.397  7067  7067 W art     : b5b15000-b5b16000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-31 16:54:17.397  7067  7067 W art     : b5b17000-b5b62000 r
08-31 16:54:17.397  7067  7067 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:54:17.397  7067  7067 W art     : b5b62000-b5b63000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:54:17.397  7067  7067 W art     : b5b63000-b5b64000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-31 16:54:17.397  7067  7067 W art     : b5b64000-b5b66000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5b66000-b5b67000 r--p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5b67000-b5b78000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:54:17.397  7067  7067 W art     : b5b78000-b5b79000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5b79000-b5b7a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:54:17.397  7067  7067 W art     : b5b7a000-b5b7b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-31 16:54:17.397  7067  7067 W art     : b5b7b000-b5b7c000 r--p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5b7c000-b5b86000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:54:17.397  7067  7067 W art     : b5b86000-b5b88000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:54:17.397  7067  7067 W art     : b5b88000-b5b89000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-31 16:54:17.397  7067  7067 W art     : b5b89000-b5ba2000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:54:17.397  7067  7067 W art     : b5ba2000-b5ba3000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:54:17.397  7067  7067 W art     : b5ba3000-b5ba6000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-31 16:54:17.397  7067  7067 W art     : b5ba6000-b5baa000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5baa000-b5c1e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-31 16:54:17.397  7067  7067 W art     : b5c1e000-b5c1f000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5c1f000-b5c22000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-31 16:54:17.397  7067  7067 W art     : b5c22000-b5c23000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-31 16:54:17.397  7067  7067 W art     : b5c23000-b5c24000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c24000-b5c27000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:54:17.397  7067  7067 W art     : b5c27000-b5c28000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:54:17.397  7067  7067 W art     : b5c28000-b5c29000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-31 16:54:17.397  7067  7067 W art     : b5c29000-b5c2a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c2a000-b5c2f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:54:17.397  7067  7067 W art     : b5c2f000-b5c30000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:54:17.397  7067  7067 W art     : b5c30000-b5c31000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-31 16:54:17.397  7067  7067 W art     : b5c31000-b5c32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c32000-b5c35000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b5c35000-b5c36000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b5c36000-b5c37000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b5c37000-b5c38000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:54:17.397  7067  7067 W art     : b5c38000-b5c3c000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:54:17.397  7067  7067 W art     : b5c3c000-b5c3d000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:54:17.397  7067  7067 W art     : b5c3d000-b5c3e000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
08-31 16:54:17.397  7067  7067 W art     : b5c3e000-b5c3f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c3f000-b5c43000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:54:17.397  7067  7067 W art     : b5c43000-b5c44000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:54:17.397  7067  7067 W art     : b5c44000-b5c45000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-31 16:54:17.397  7067  7067 W art     : b5c45000-b5c46000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c46000-b5c54000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-31 16:54:17.397  7067  7067 W art     : b5c54000-b5c55000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b5c55000-b5c56000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-31 16:54:17.397  7067  7067 W art     : b5c56000-b5c57000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-31 16:54:17.397  7067  7067 W art     : b5c57000-b5c61000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:54:17.397  7067  7067 W art     : b5c61000-b5c64000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:54:17.397  7067  7067 W art     : b5c64000-b5c65000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-31 16:54:17.397  7067  7067 W art     : b5c65000-b5c66000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c66000-b5c70000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-31 16:54:17.397  7067  7067 W art     : b5c70000-b5c73000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-31 16:54:17.397  7067  7067 W art     : b5c73000-b5c74000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-31 16:54:17.397  7067  7067 W art     : b5c74000-b5c78000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:54:17.397  7067  7067 W art     : b5c78000-b5c79000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:54:17.397  7067  7067 W art     : b5c79000-b5c7a000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
08-31 16:54:17.397  7067  7067 W art     : b5c7a000-b5c7b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b5c7b000-b5c88000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:54:17.397  7067  7067 W art     : b5c88000-b5c8a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:54:17.397  7067  7067 W art     : b5c8a000-b5c8b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-31 16:54:17.397  7067  7067 W art     : b5c8b000-b609d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-31 16:54:17.397  7067  7067 W art     : b609d000-b609e000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b609e000-b60a7000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-31 16:54:17.397  7067  7067 W art     : b60a7000-b60ab000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-31 16:54:17.397  7067  7067 W art     : b60ab000-b60ac000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b60ac000-b60b3000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:54:17.397  7067  7067 W art     : b60b3000-b60b4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:54:17.397  7067  7067 W art     : b60b4000-b60b5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-31 16:54:17.397  7067  7067 W art     : b60b5000-b60b6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b60b6000-b60d1000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-31 16:54:17.397  7067  7067 W art     : b60d1000-b60d2000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-31 16:54:17.397  7067  7067 W art     : b60d2000-b60d3000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-31 16:54:17.397  7067  7067 W art     : b60d3000-b60d4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b60d4000-b6120000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:54:17.397  7067  7067 W art     : b6120000-b6121000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6121000-b6122000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:54:17.397  7067  7067 W art     : b6122000-b6123000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-31 16:54:17.397  7067  7067 W art     : b6123000-b6124000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6124000-b6128000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:54:17.397  7067  7067 W art     : b6128000-b6129000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6129000-b612a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:54:17.397  7067  7067 W art     : b612a000-b612b000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-31 16:54:17.397  7067  7067 W art     : b612b000-b6163000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:54:17.397  7067  7067 W art     : b6163000-b6164000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:54:17.397  7067  7067 W art     : b6164000-b6165000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-31 16:54:17.397  7067  7067 W art     : b6165000-b6166000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6166000-b6205000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
08-31 16:54:17.397  7067  7067 W art     : b6205000-b6223000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
08-31 16:54:17.397  7067  7067 W art     : b6223000-b6224000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
08-31 16:54:17.397  7067  7067 W art     : b6224000-b6397000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:54:17.397  7067  7067 W art     : b6397000-b63a2000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:54:17.397  7067  7067 W art     : b63a2000-b63a3000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-31 16:54:17.397  7067  7067 W art     : b63a3000-b64ba000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:54:17.397  7067  7067 W art     : b64ba000-b64c5000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:54:17.397  7067  7067 W art     : b64c5000-b64c6000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-31 16:54:17.397  7067  7067 W art     : b64c6000-b64ca000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b64ca000-b64ee000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-31 16:54:17.397  7067  7067 W art     : b64ee000-b64f0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-31 16:54:17.397  7067  7067 W art     : b64f0000-b64f1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-31 16:54:17.397  7067  7067 W art     : b64f1000-b6597000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
08-31 16:54:17.397  7067  7067 W art     : b6597000-b65a4000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
08-31 16:54:17.397  7067  7067 W art     : b65a4000-b65a5000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
08-31 16:54:17.397  7067  7067 W art     : b65a5000-b65a6000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b65a6000-b65f9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:54:17.397  7067  7067 W art     : b65f9000-b65fa000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b65fa000-b65fb000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:54:17.397  7067  7067 W art     : b65fb000-b65fc000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-31 16:54:17.397  7067  7067 W art     : b65fc000-b6601000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6601000-b6613000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-31 16:54:17.397  7067  7067 W art     : b6613000-b6614000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6614000-b6615000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-31 16:54:17.397  7067  7067 W art     : b6615000-b6616000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-31 16:54:17.397  7067  7067 W art     : b6616000-b661d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:54:17.397  7067  7067 W art     : b661d000-b661e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:54:17.397  7067  7067 W art     : b661e000-b661f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-31 16:54:17.397  7067  7067 W art     : b661f000-b6620000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6620000-b6623000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-31 16:54:17.397  7067  7067 W art     : b6623000-b6624000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-31 16:54:17.397  7067  7067 W art     : b6624000-b6625000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-31 16:54:17.397  7067  7067 W art     : b6625000-b6629000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-31 16:54:17.397  7067  7067 W art     : b6629000-b662a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-31 16:54:17.397  7067  7067 W art     : b662a000-b662b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-31 16:54:17.397  7067  7067 W art     : b662b000-b6639000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:54:17.397  7067  7067 W art     : b6639000-b663a000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b663a000-b663b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:54:17.397  7067  7067 W art     : b663b000-b663c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-31 16:54:17.397  7067  7067 W art     : b663c000-b6645000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:54:17.397  7067  7067 W art     : b6645000-b6646000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:54:17.397  7067  7067 W art     : b6646000-b6647000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-31 16:54:17.397  7067  7067 W art     : b6647000-b66ad000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-31 16:54:17.397  7067  7067 W art     : b66ad000-b66ae000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b66ae000-b66b0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-31 16:54:17.397  7067  7067 W art     : b66b0000-b66b9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-31 16:54:17.397  7067  7067 W art     : b66b9000-b66bc000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b66bc000-b6753000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-31 16:54:17.397  7067  7067 W art     : b6753000-b6755000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-31 16:54:17.397  7067  7067 W art     : b6755000-b6756000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-31 16:54:17.397  7067  7067 W art     : b6756000-b6757000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6757000-b6a75000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
08-31 16:54:17.397  7067  7067 W art     : b6a75000-b6a76000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6a76000-b6a91000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
08-31 16:54:17.397  7067  7067 W art     : b6a91000-b6a95000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
08-31 16:54:17.397  7067  7067 W art     : b6a95000-b6a9a000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6a9a000-b6aa2000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b6aa2000-b6aa3000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b6aa3000-b6aa4000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-31 16:54:17.397  7067  7067 W art     : b6aa4000-b6ad2000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:54:17.397  7067  7067 W art     : b6ad2000-b6ad3000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6ad3000-b6ada000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:54:17.397  7067  7067 W art     : b6ada000-b6adb000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-31 16:54:17.397  7067  7067 W art     : b6adb000-b6b21000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:54:17.397  7067  7067 W art     : b6b21000-b6b22000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6b22000-b6b25000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:54:17.397  7067  7067 W art     : b6b25000-b6b26000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
08-31 16:54:17.397  7067  7067 W art     : b6b26000-b6b41000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-31 16:54:17.397  7067  7067 W art     : b6b41000-b6b45000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-31 16:54:17.397  7067  7067 W art     : b6b45000-b6b46000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-31 16:54:17.397  7067  7067 W art     : b6b46000-b6b93000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
,08-31 16:54:17.397  7067  7067 W art     : b6b93000-b6b94000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6b94000-b6ba0000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
08-31 16:54:17.397  7067  7067 W art     : b6ba0000-b6ba1000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
08-31 16:54:17.397  7067  7067 W art     : b6ba1000-b6bae000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
08-31 16:54:17.397  7067  7067 W art     : b6bae000-b6baf000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6baf000-b6bb0000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
08-31 16:54:17.397  7067  7067 W art     : b6bb0000-b6bb1000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
08-31 16:54:17.397  7067  7067 W art     : b6bb1000-b6bb9000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:54:17.397  7067  7067 W art     : b6bb9000-b6bba000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6bba000-b6bbb000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:54:17.397  7067  7067 W art     : b6bbb000-b6bbc000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-31 16:54:17.397  7067  7067 W art     : b6bbc000-b6bc3000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b6bc3000-b6bc4000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b6bc4000-b6bc5000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
08-31 16:54:17.397  7067  7067 W art     : b6bc5000-b6bd9000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-31 16:54:17.397  7067  7067 W art     : b6bd9000-b6bdb000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-31 16:54:17.397  7067  7067 W art     : b6bdb000-b6bdc000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-31 16:54:17.397  7067  7067 W art     : b6bdc000-b6c04000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:54:17.397  7067  7067 W art     : b6c04000-b6c06000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:54:17.397  7067  7067 W art     : b6c06000-b6c07000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
08-31 16:54:17.397  7067  7067 W art     : b6c07000-b6c0a000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:54:17.397  7067  7067 W art     : b6c0a000-b6c0b000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:54:17.397  7067  7067 W art     : b6c0b000-b6c0c000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-31 16:54:17.397  7067  7067 W art     : b6c0c000-b6c15000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:54:17.397  7067  7067 W art     : b6c15000-b6c16000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:54:17.397  7067  7067 W art     : b6c16000-b6c17000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-31 16:54:17.397  7067  7067 W art     : b6c17000-b6c37000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-31 16:54:17.397  7067  7067 W art     : b6c37000-b6c38000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-31 16:54:17.397  7067  7067 W art     : b6c38000-b6c39000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-31 16:54:17.397  7067  7067 W art     : b6c39000-b6cac000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
08-31 16:54:17.397  7067  7067 W art     : b6cac000-b6cb0000 r--p 00072000 b3:17 1016       /system/lib/libc.so
08-31 16:54:17.397  7067  7067 W art     : b6cb0000-b6cb3000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
08-31 16:54:17.397  7067  7067 W art     : b6cb3000-b6cbd000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6cbd000-b6d45000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
08-31 16:54:17.397  7067  7067 W art     : b6d45000-b6d46000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6d46000-b6d4a000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
08-31 16:54:17.397  7067  7067 W art     : b6d4a000-b6d4b000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
08-31 16:54:17.397  7067  7067 W art     : b6d4b000-b6d4c000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6d4c000-b6d75000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:54:17.397  7067  7067 W art     : b6d75000-b6d76000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6d76000-b6d79000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:54:17.397  7067  7067 W art     : b6d79000-b6d7a000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-31 16:54:17.397  7067  7067 W art     : b6d7a000-b6e54000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:54:17.397  7067  7067 W art     : b6e54000-b6e5b000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:54:17.397  7067  7067 W art     : b6e5b000-b6e63000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-31 16:54:17.397  7067  7067 W art     : b6e63000-b6e64000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6e64000-b6e65000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:54:17.397  7067  7067 W art     : b6e65000-b6e66000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-31 16:54:17.397  7067  7067 W art     : b6e66000-b6e67000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6e67000-b6e6a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6e6a000-b6e8f000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
08-31 16:54:17.397  7067  7067 W art     : b6e8f000-b6e90000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6e90000-b6e97000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
08-31 16:54:17.397  7067  7067 W art     : b6e97000-b6e98000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
08-31 16:54:17.397  7067  7067 W art     : b6e98000-b6e9f000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-31 16:54:17.397  7067  7067 W art     : b6e9f000-b6ea0000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-31 16:54:17.397  7067  7067 W art     : b6ea0000-b6ea1000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-31 16:54:17.397  7067  7067 W art     : b6ea1000-b6ea2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6ea2000-b6eba000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-31 16:54:17.397  7067  7067 W art     : b6eba000-b6ebb000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6ebb000-b6ebc000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-31 16:54:17.397  7067  7067 W art     : b6ebc000-b6ebd000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-31 16:54:17.397  7067  7067 W art     : b6ebd000-b6ecb000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-31 16:54:17.397  7067  7067 W art     : b6ecb000-b6ecc000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6ecc000-b6ecd000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-31 16:54:17.397  7067  7067 W art     : b6ecd000-b6ece000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-31 16:54:17.397  7067  7067 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:54:17.397  7067  7067 W art     : b6ecf000-b6ed1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6ed1000-b6ed2000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-31 16:54:17.397  7067  7067 W art     : b6ed3000-b6ed4000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-31 16:54:17.397  7067  7067 W art     : b6ed4000-b6ed5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-31 16:54:17.397  7067  7067 W art     : b6ed5000-b6ef5000 r--s 00000000 00:0b 6700       /dev/__properties__
08-31 16:54:17.397  7067  7067 W art     : b6ef5000-b6ef6000 r--p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6ef6000-b6ef7000 ---p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6ef7000-b6ef9000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-31 16:54:17.397  7067  7067 W art     : b6ef9000-b6efa000 r-xp 00000000 00:00 0          [sigpage]
08-31 16:54:17.397  7067  7067 W art     : b6efa000-b6f15000 r-xp 00000000 b3:17 341        /system/bin/linker
08-31 16:54:17.397  7067  7067 W art     : b6f15000-b6f16000 r--p 0001a000 b3:17 341        /system/bin/linker
08-31 16:54:17.397  7067  7067 W art     : b6f16000-b6f18000 rw-p 0001b000 b3:17 341        /system/bin/linker
08-31 16:54:17.397  7067  7067 W art     : b6f18000-b6f1a000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : b6f1a000-b6f1f000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-31 16:54:17.397  7067  7067 W art     : b6f1f000-b6f20000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-31 16:54:17.397  7067  7067 W art     : b6f20000-b6f21000 rw-p 00000000 00:00 0 
08-31 16:54:17.397  7067  7067 W art     : bed0d000-bed2e000 rw-p 00000000 00:00 0          [stack]
08-31 16:54:17.397  7067  7067 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-31 16:54:17.407  7175  7175 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
08-31 16:54:17.437  7147  7147 I MultiDex: VM with version 2.1.0 has multidex support
08-31 16:54:17.437  7147  7147 I MultiDex: install
08-31 16:54:17.437  7147  7147 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 16:54:17.447  7067  7067 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 16:54:17.457  7175  7175 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472655257463
08-31 16:54:17.457  7175  7175 D         : TimeServiceNative: User Time to be set is 1472655257465
08-31 16:54:17.457  7175  7175 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-31 16:54:17.457  7175  7175 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-31 16:54:17.457  7175  7175 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472655257465
08-31 16:54:17.457   376   684 D QC-time-services: Daemon: Connection accepted:time_genoff
08-31 16:54:17.457  7175  7175 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472655257465
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472655257465, operation = 0
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/8/71 19:35:40
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:Value read from RTC seconds = 32211340000
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:new time 1472655257465 
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon: delta 1440443917465 genoff 1440443917465 
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440443917465 to memory
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-31 16:54:17.467   376  7188 D QC-time-services: Updating the TOD offset
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440443917465 to memory
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-31 16:54:17.467   376  7188 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-31 16:54:17.477   376  7188 E QC-time-services: Daemon:Update to modem bit set
08-31 16:54:17.477   376  7188 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-31 16:54:17.477   376  7188 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124479117465
,08-31 16:54:17.477  7175  7175 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-31 16:54:17.477   754   775 I ActivityManager: Killing 6159:com.sec.android.app.samsungapps/u0a39 (adj 15): DHA:empty #37
,08-31 16:54:17.477   376   682 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-31 16:54:17.477   376   684 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-31 16:54:17.487   754   775 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1addc95 1517:com.sec.android.daemonapp/u0a181}
,08-31 16:54:17.507  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-31 16:54:17.507  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-31 16:54:17.507  1517  1517 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:54:17.517   754  1298 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.samsungapps, Auto Run ON
,08-31 16:54:17.517  1517  1517 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-31 16:54:17.527  1517  1517 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionTIME_SET, run:true
,08-31 16:54:17.527  1517  1517 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-31 16:54:17.527  1517  1517 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-31 16:54:17.527  1517  1517 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-31 16:54:17.527  7067  7067 I Radio-JNI: register_android_hardware_Radio DONE
08-31 16:54:17.527  1517  1517 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-31 16:54:17.527  1517  1517 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-31 16:54:17.527  1517  1517 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-31 16:54:17.537  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:1609 [0:0] PakNme size = 5
,08-31 16:54:17.537  7067  7067 E AffinityControl: AffinityControl: registerfunction enter
,08-31 16:54:17.547  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-31 16:54:17.547  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-31 16:54:17.547  1517  1517 D daemonapp: [MSC_Daemon]>>> WU:1613 [0:0] CP Name cp_eng
,08-31 16:54:17.547  1517  1517 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-31 16:54:17.557  7067  7067 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:54:17.557  1517  1517 E daemonapp: [MSC_Daemon]>>> WU:1593 [0:0] [NameNotFoundException] !!
,08-31 16:54:17.567   754  1704 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1addc95 1517:com.sec.android.daemonapp/u0a181}
,08-31 16:54:17.577   754  1713 D PackageManager: START PACKAGE DELETE: observer{112754880}
08-31 16:54:17.577   754  1713 D PackageManager: pkg{<packageName>}
08-31 16:54:17.577   754  1713 D PackageManager: user{0}
08-31 16:54:17.577   754  1713 D PackageManager: caller{2000}
08-31 16:54:17.577   754  1713 D PackageManager: flags{2}
,08-31 16:54:17.577   754  1713 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-31 16:54:17.577   754  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 16:54:17.577   754  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-31 16:54:17.577   754  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 16:54:17.577   754  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 16:54:17.577   754   917 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 16:54:17.577   754   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 16:54:17.577   754   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-31 16:54:17.577   754   917 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 16:54:17.577   754   917 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:54:17.577   304   304 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6cca030
,08-31 16:54:17.577   304   304 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-31 16:54:17.577   304   304 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 16:54:17.577   304   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229453008)
,08-31 16:54:17.587   754  2180 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 16:54:17.587   754   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-31 16:54:17.587   754   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 16:54:17.597   754   917 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,08-31 16:54:17.597   754   846 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
,08-31 16:54:17.597   754   846 I ActivityManager: Killing 6444:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-31 16:54:17.597   754   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,08-31 16:54:17.597   754   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-31 16:54:17.607   754   846 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 16:54:17.637   304   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-31 16:54:17.637   304   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-31 16:54:17.637   304   620 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229453008) wakelock released: 1, error no: 0
08-31 16:54:17.637   304   620 I rmt_storage: 
,08-31 16:54:17.647   304   304 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6cca030
,08-31 16:54:17.657   754   846 I ActivityManager: Start proc 7198:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-31 16:54:17.657  7198  7198 E Zygote  : v2
08-31 16:54:17.657  7198  7198 I libpersona: KNOX_SDCARD checking this for 10004
08-31 16:54:17.657  7198  7198 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:17.657  7198  7198 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:17.657  7198  7198 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:17.657   754   846 I ActivityManager:   Force finishing activity ActivityRecord{47a6132 u0 com.test.thalitest/.MainActivity t168}
08-31 16:54:17.657  7198  7198 E Zygote  : accessInfo : 0
,08-31 16:54:17.657  7198  7198 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-31 16:54:17.657   754  1414 D GraphicsStats: Buffer count: 5
,08-31 16:54:17.657   754   775 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@84981f9)
,08-31 16:54:17.657   754  1335 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:17.667   754  1335 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:17.667   754  1335 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:17.667   754  1713 I WindowState: WIN DEATH: Window{6fe22db u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:54:17.667   293  1300 I SurfaceFlinger: id=21 Removed NainActivit (4/10)
,08-31 16:54:17.667   293   345 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
08-31 16:54:17.667   293  1792 I SurfaceFlinger: id=21 Removed NainActivit (-2/10)
,08-31 16:54:17.667   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
,08-31 16:54:17.677  1517  1517 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-31 16:54:17.677  1517  1517 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-31 16:54:17.677  7195  7195 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-31 16:54:17.687  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:17.687  7198  7198 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:17.697   754   917 D AASAinstall: there is not AASApackages.xml file
,08-31 16:54:17.817  7195  7195 I dex2oat : ----------------------------------------------------
08-31 16:54:17.817  7195  7195 I dex2oat : <SS>: S T A R T I N G . . .
08-31 16:54:17.817  7195  7195 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-31 16:54:17.827  7195  7195 I dex2oat : dex2oat took 142.879ms (threads: 4) arena alloc=280KB java alloc=75KB native alloc=1797KB free=1530KB
,08-31 16:54:17.827  6979  6990 W System  : ClassLoader referenced unknown path: 
,08-31 16:54:17.837  6979  6990 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-31 16:54:17.837  6979  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:54:17.837  6979  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:54:17.837  6979  6990 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:54:17.837  6979  6990 I Adreno-EGL: Local Branch: ss
08-31 16:54:17.837  6979  6990 I Adreno-EGL: Remote Branch: 
08-31 16:54:17.837  6979  6990 I Adreno-EGL: Local Patches: 
08-31 16:54:17.837  6979  6990 I Adreno-EGL: Reconstruct Branch: 
,08-31 16:54:17.837  6979  6990 D libEGL  : eglInitialize EGLDisplay = 0xb308d264
,08-31 16:54:17.887  6992  7023 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,08-31 16:54:17.897  6979  6990 D libEGL  : eglTerminate EGLDisplay = 0xb308d2bc
,08-31 16:54:17.907  6979  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:54:17.907  6979  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:54:17.907  6979  6990 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:54:17.907  6979  6990 I Adreno-EGL: Local Branch: ss
08-31 16:54:17.907  6979  6990 I Adreno-EGL: Remote Branch: 
08-31 16:54:17.907  6979  6990 I Adreno-EGL: Local Patches: 
08-31 16:54:17.907  6979  6990 I Adreno-EGL: Reconstruct Branch: 
08-31 16:54:17.907  6979  6990 D libEGL  : eglInitialize EGLDisplay = 0xb308d264
,08-31 16:54:17.907  6992  7023 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,08-31 16:54:17.907  6992  7023 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:54:17.907  6992  7023 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:54:17.917   308  1186 D EnterpriseController: netId is 0
08-31 16:54:17.917   308  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10044
,08-31 16:54:17.947  6979  6990 D libEGL  : eglTerminate EGLDisplay = 0xb308d2bc
,08-31 16:54:17.957  6979  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-31 16:54:17.957  6979  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-31 16:54:17.957  6979  6990 I Adreno-EGL: Build Date: 01/28/16 Thu
08-31 16:54:17.957  6979  6990 I Adreno-EGL: Local Branch: ss
08-31 16:54:17.957  6979  6990 I Adreno-EGL: Remote Branch: 
08-31 16:54:17.957  6979  6990 I Adreno-EGL: Local Patches: 
08-31 16:54:17.957  6979  6990 I Adreno-EGL: Reconstruct Branch: 
08-31 16:54:17.957  6979  6990 D libEGL  : eglInitialize EGLDisplay = 0xb308d264
,08-31 16:54:17.967   754   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-31 16:54:17.997  6979  6990 D libEGL  : eglTerminate EGLDisplay = 0xb308d2bc
,08-31 16:54:18.057  1386  1386 D ViewRootImpl: #3 mView = null
,08-31 16:54:18.057   293  1300 I SurfaceFlinger: id=24 Removed Uoast (8/9)
,08-31 16:54:18.057   293   341 I SurfaceFlinger: id=24 Removed Uoast (-2/9)
,08-31 16:54:18.067   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
,08-31 16:54:18.067   754  1414 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 754) eventTime = 313138
08-31 16:54:18.067   754   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-31 16:54:18.067   754  1414 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=754 (0x0)
,08-31 16:54:18.077   754  1414 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=754, ws=WorkSource{10058}) (elapsedTime=3503)
,08-31 16:54:18.087   329   329 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-31 16:54:18.087   754  1704 I ActivityManager: Start proc 7216:com.sec.android.app.clockpackage/u0a90 for broadcast-3 com.sec.android.app.clockpackage/.alarm.AlarmReceiver,
,08-31 16:54:18.087  7216  7216 E Zygote  : v2
08-31 16:54:18.087  7216  7216 I libpersona: KNOX_SDCARD checking this for 10090
08-31 16:54:18.087  7216  7216 I libpersona: KNOX_SDCARD not a persona
,08-31 16:54:18.087  7216  7216 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:18.087  7216  7216 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:18.087  7216  7216 E Zygote  : accessInfo : 0
,08-31 16:54:18.087  7216  7216 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.clockpackage 
,08-31 16:54:18.107   754   917 I art     : Starting a blocking GC Explicit
08-31 16:54:18.107   754  1737 I ActivityManager: Killing 5650:com.android.defcontainer/u0a5 (adj 15): DHA:empty #37
,08-31 16:54:18.127  7216  7216 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:18.127  7216  7216 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:18.127   754  1298 D ActivityManager: isAutoRunBlockedApp:: com.android.defcontainer, Auto Run ON
08-31 16:54:18.127  7198  7198 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-31 16:54:18.137  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:54:18.137  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:54:18.137  2021  6973 I qtaguid : Tagging socket 56 with tag 11065c0800000000{285629448,0} uid -1, pid: 2021, getuid(): 10011
,08-31 16:54:18.137  7198  7198 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-31 16:54:18.137  7198  7198 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
08-31 16:54:18.137  7198  7198 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-31 16:54:18.137  7198  7198 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-31 16:54:18.137   754  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c42f9f 7216:com.sec.android.app.clockpackage/u0a90}
,08-31 16:54:18.147  7216  7216 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_MUPG/ClockPackage_MUPG.apk / 1.0 running in com.sec.android.app.clockpackage rsrc of package null
,08-31 16:54:18.157  7198  7198 D AndroidRuntime: Shutting down VM
,08-31 16:54:18.157  7198  7198 E AndroidRuntime: FATAL EXCEPTION: main
08-31 16:54:18.157  7198  7198 E AndroidRuntime: Process: com.test.thalitest, PID: 7198
08-31 16:54:18.157  7198  7198 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-31 16:54:18.157  7198  7198 E AndroidRuntime: 	... 9 more
,08-31 16:54:18.177  7198  7198 I Process : Sending signal. PID: 7198 SIG: 9
,08-31 16:54:18.187  7147  7147 I GAv4    : Google Analytics 8.2.98 is starting up. To enable debug logging on a device run:
08-31 16:54:18.187  7147  7147 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:54:18.187  7147  7147 I GAv4    :   adb logcat -s GAv4
,08-31 16:54:18.197   754  1732 I ActivityManager: Process com.test.thalitest (pid 7198)(adj 9) has died(158,731)
,08-31 16:54:18.197   754  1732 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 16:54:18.197   754  1732 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-31 16:54:18.197   754  1732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26698 com.android.server.am.ActivityManagerService.appDiedLocked:7560 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-31 16:54:18.197   754   846 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-31 16:54:18.197   754   846 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-31 16:54:18.207  7147  7147 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.google.android.apps.magazines rsrc of package null
,08-31 16:54:18.207  7216  7216 W System  : ClassLoader referenced unknown path: /system/app/ClockPackage_MUPG/lib/arm
,08-31 16:54:18.207   754  1590 V AlarmManager:  remove PendingIntent] PendingIntent{9c626bb: PendingIntentRecord{8cda7d8 com.google.android.apps.magazines broadcastIntent}}
,08-31 16:54:18.217  7147  7147 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:18.217  7147  7147 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:18.237  7147  7235 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:18.277   754  1713 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 16:54:18.277   754  1414 V AlarmManager:  remove PendingIntent] PendingIntent{d63c525: PendingIntentRecord{92a66fa com.sec.android.app.clockpackage broadcastIntent}}
,08-31 16:54:18.277   754   775 D SettingsProvider: isChangeAllowed() : name = next_alarm_formatted
,08-31 16:54:18.277   754   775 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:54:18.277   754   775 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:54:18.277   754   775 D SettingsProvider: selectionArgs: false
08-31 16:54:18.277   754   775 D SettingsProvider: selectionArgs: 10090
,08-31 16:54:18.277   754   775 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-31 16:54:18.287   754   775 D SettingsProvider: ret = -1
,08-31 16:54:18.297  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:54:18.297  2021  6973 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:54:18.297  2021  6973 I qtaguid : Tagging socket 56 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2021, getuid(): 10011
,08-31 16:54:18.297   754   917 I art     : Explicit concurrent mark sweep GC freed 102376(5MB) AllocSpace objects, 12(464KB) LOS objects, 27% free, 42MB/58MB, paused 1.717ms total 194.965ms
,08-31 16:54:18.327   754   917 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 16:54:18.327   754   917 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,08-31 16:54:18.337   754   917 D AASAinstall: there is not AASApackages.xml file
,08-31 16:54:18.337   754   917 D PackageManager: result of delete: 1{112754880}
,08-31 16:54:18.347  7067  7067 I art     : System.exit called, status: 0
08-31 16:54:18.347  7067  7067 I AndroidRuntime: VM exiting with result code 0.
,08-31 16:54:18.347   754   917 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:54:18.347   754   917 D PackageManager: userId{-1}
08-31 16:54:18.347   754   917 D PackageManager: andCode{true}
,08-31 16:54:18.387  7251  7251 E Zygote  : v2
08-31 16:54:18.387  7251  7251 I libpersona: KNOX_SDCARD checking this for 10005
08-31 16:54:18.387  7251  7251 I libpersona: KNOX_SDCARD not a persona
08-31 16:54:18.387  7251  7251 E libpersona: scanKnoxPersonas
08-31 16:54:18.387  7251  7251 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,08-31 16:54:18.387  7251  7251 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-31 16:54:18.387  7251  7251 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-31 16:54:18.387  7251  7251 E Zygote  : accessInfo : 0
08-31 16:54:18.387  7251  7251 E libpersona: scanKnoxPersonas
08-31 16:54:18.387  7251  7251 E libpersona: Couldn't open the File - /data/system/users/0/personalist.xml - No such file or directory
,08-31 16:54:18.417  7251  7251 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:54:18.417  7251  7251 D ActivityThread: Added TimaKeyStore provider
,08-31 16:54:18.427   754   917 I ActivityManager: Start proc 7251:com.android.defcontainer/u0a5 for service com.android.defcontainer/.DefaultContainerService
,08-31 16:54:18.427   754   774 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{de62bb1 u-1 android.intent.action.TIME_SET qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{34b5e58 2319:com.sec.android.widgetapp.ap.hero.accuweather/u0a70}
,08-31 16:54:18.427  2319  2319 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-31 16:54:18.427  2319  2319 D accuweather: [KK AccuPhone]>>> UIMEM:107 [0:0] The widget does not exist in idle!!
,08-31 16:54:18.437   754   917 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-31 16:54:18.437  7251  7251 W ResourcesManager: getTopLevelResources: /system/priv-app/DefaultContainerService/DefaultContainerService.apk / 1.0 running in com.android.defcontainer rsrc of package null
,08-31 16:54:18.497   754   754 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.497  7251  7266 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-31 16:54:18.507  7251  7266 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-31 16:54:18.507  7251  7266 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-31 16:54:18.507   754   754 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.507  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-31 16:54:18.507  1386  1386 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-31 16:54:18.507   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.517   754   893 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.517   754   826 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.517  1982  1982 E SamsungIME: mOCRHelper is null
,08-31 16:54:18.527   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,08-31 16:54:18.527   754   754 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x8dfd2174 in tid 754 (system_server)
08-31 16:54:18.527   754   893 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
08-31 16:54:18.527  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
08-31 16:54:18.527  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.537  2021  2484 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:54:18.547  7147  7267 E NSDepend: Could not load library: pdflib.dex.jar
08-31 16:54:18.547  7147  7267 E NSDepend: java.io.FileNotFoundException: /data/user/0/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:212)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:200)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:126)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:1447)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:1394)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.apps.dots.android.newsstand.NSDepend$3.doInBackground(NSDepend.java:1427)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.util.concurrent.TrustedListenableFutureTask$TrustedFutureInterruptibleTask.runInterruptibly(TrustedListenableFutureTask.java:109)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.util.concurrent.InterruptibleTask.run(InterruptibleTask.java:40)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.common.util.concurrent.TrustedListenableFutureTask.run(TrustedListenableFutureTask.java:77)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at com.google.android.libraries.bind.async.Queue$3$1.run(Queue.java:103)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:18.547  7147  7267 E NSDepend: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:18.547  7147  7267 E NSDepend: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:18.547  7147  7267 E NSDepend: 	... 16 more
,08-31 16:54:18.607   292   292 I ServiceManager: service 'sec_analytics' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'telecom' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'activity' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'user' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'procstats' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'meminfo' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'gfxinfo' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'dbinfo' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'cpuinfo' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'permission' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'processinfo' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'sensorservice' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'battery' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'usagestats' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'webviewupdate' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'scheduling_policy' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'telephony.registry' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'persona' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'notification' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'location' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'country_detector' died
08-31 16:54:18.607  6573  6676 E WifiManager: Channel connection lost
,08-31 16:54:18.607  2738  2749 W Sensors : sensorservice died [0xad893bc0]
08-31 16:54:18.607   292   292 I ServiceManager: service 'sec_location' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'search' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'execute' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'dropbox' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'wallpaper' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'audio' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'DockObserver' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'midi' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'usb' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'serial' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'kiesusb' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'jobscheduler' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'backup' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'appwidget' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'voiceinteraction' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'diskstats' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'mDNIe' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'AAS' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'MSCS' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'spengestureservice' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'quickconnect' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'samplingprofiler' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'commontime_management' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'dreams' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'graphicsstats' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'print' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'restrictions' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'media_session' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'media_router' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'trust' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'fingerprint' died
08-31 16:54:18.607   292   292 I ServiceManager: service 'launcherapps' died
,08-31 16:54:18.617  1705  1705 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x710fbb0e in tid 1705 (m.android.phone)
08-31 16:54:18.617  1705  2360 E WifiManager: Channel connection lost
,08-31 16:54:18.617  1691  1691 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2cdec02 in tid 1691 (com.android.nfc)
08-31 16:54:18.617  1705  1705 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.617   326   326 E installd: eof
08-31 16:54:18.617  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
08-31 16:54:18.617   326   326 E installd: failed to read size
08-31 16:54:18.617   326   326 I installd: closing connection
08-31 16:54:18.617  2738  4202 E WifiManager: Channel connection lost
,08-31 16:54:18.617  7251  7266 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70ff678e in tid 7266 (IntentService[D)
08-31 16:54:18.617  1691  1691 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.617  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.617  7251  7266 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.617  2021  2032 W Sensors : sensorservice died [0xad4a2880]
,08-31 16:54:18.617  2120  2166 W Sensors : sensorservice died [0xb3af3cc0]
,08-31 16:54:18.617  1721  1734 W Sensors : sensorservice died [0xacf60340]
,08-31 16:54:18.617   293   345 I SurfaceFlinger: id=13 Removed EimLayer(Di (5/8)
08-31 16:54:18.617   293   345 I SurfaceFlinger: id=2 Removed GocusedStac (4/7)
08-31 16:54:18.617   293   345 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/6)
08-31 16:54:18.617   293   345 I SurfaceFlinger: id=4 Removed EimLayer(An (0/5)
,08-31 16:54:18.617  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.617  1386  1411 W Sensors : sensorservice died [0xacf4cc80]
,08-31 16:54:18.617   322   960 W AudioFlinger: power manager service died !!!
08-31 16:54:18.617   322   960 W AudioFlinger: power manager service died !!!
,08-31 16:54:18.627   293   345 I SurfaceFlinger: id=14 Removed EimLayer(An (0/4)
08-31 16:54:18.627   293   345 I SurfaceFlinger: id=2 Removed GocusedStac (-2/4)
08-31 16:54:18.627   293   345 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/4)
08-31 16:54:18.627   293   345 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/4)
,08-31 16:54:18.627   293  1300 I SurfaceFlinger: restart the boot-animation @ binderDied
08-31 16:54:18.627   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-31 16:54:18.627   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-31 16:54:18.627  6532  6532 D HeadsetStateMachine: Proxy object disconnected
,08-31 16:54:18.627  1857  1868 W Sensors : sensorservice died [0xb3af3e00],
,08-31 16:54:18.627   293  7281 I SurfaceFlinger: id=23 Removed YUIInstallC (1/3)
08-31 16:54:18.627   293  7281 I SurfaceFlinger: id=23 Removed YUIInstallC (-2/3)
08-31 16:54:18.627  3068  3086 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e620f91 in tid 3086 (AccountChangeLi)
,08-31 16:54:18.637   293   341 I SurfaceFlinger: id=5 Removed TtatusBar (1/2)
,08-31 16:54:18.637   293   341 I SurfaceFlinger: id=5 Removed TtatusBar (-2/2)
08-31 16:54:18.637   293   341 I SurfaceFlinger: id=13 Removed EimLayer(Di (-2/2)
08-31 16:54:18.637   292   292 I ServiceManager: service 'voip' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'media_projection' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'lpnet' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'imms' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'clipboardEx' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'network_management' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'textservices' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'network_score' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'netstats' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'netpolicy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'wifip2p' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'wifi' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'wifihs20' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'wifiscanner' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'rttmanager' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'ethernet' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'connectivity' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'sb_service' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'servicediscovery' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'updatelock' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'application_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'wifi_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'remoteinjection' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'edm_proxy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'mum_container_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'otp_service' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'enterprise_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'statusbar' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'clipboard' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'SEAMService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'media.camera.proxy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'account' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'content' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'DirEncryptService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'LSManager' died
08-31 16:54:18.637  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
08-31 16:54:18.637   292   292 I ServiceManager: service 'ReactiveService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'DeviceRootKeyService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'EngineeringModeService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'SatsService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'sedenial' died
08-31 16:54:18.637   292   292 ,I ServiceManager: service 'vibrator' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'tw_toolbox' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'tima' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'iccc' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'cepproxyks' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'emailksproxy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'consumer_ir' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'alarm' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'persona_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'package' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'context_aware' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'scontext' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'barbeam' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'multiwindow_facade' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'window' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'input' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'bluetooth_manager' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'rcp' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'input_method' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'accessibility' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'cover' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'mount' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'lock_settings' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'deviceidle' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'device_policy' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'harmony_eas_service' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'sdp' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'sdp_log' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'dlp' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'log_manager_service' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'edmnativehelper' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'uimode' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'batterystats' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'appops' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'power' died
08-31 16:54:18.637   292   292 I ServiceManager: service 'display' died
08-31 16:54:18.637  2021  2484 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x71343192 in tid 2484 (GeofencerStateM)
08-31 16:54:18.637  2021  2484 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.637   293   345 I SurfaceFlinger: id=7 Removed JmageWallpa (0/1)
08-31 16:54:18.637   293   345 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/1)
08-31 16:54:18.637   293   345 I SurfaceFlinger: id=14 Removed EimLayer(An (-2/1)
08-31 16:54:18.637   293   345 I SurfaceFlinger: id=17 Removed DolorFade (0/0)
08-31 16:54:18.637   293   345 I SurfaceFlinger: id=17 Removed DolorFade (-2/0)
,08-31 16:54:18.637  3068  3086 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.637  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.647  6992  7023 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 735
,08-31 16:54:18.647   293  1792 D libEGL  : eglTerminate EGLDisplay = 0xb16596fc
,08-31 16:54:18.647   293  1792 D libEGL  : eglTerminate EGLDisplay = 0xb16596fc
08-31 16:54:18.647  6992  7023 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,08-31 16:54:18.647  6992  7023 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x710d9a72 in tid 7023 (AsyncTask #1)
08-31 16:54:18.647  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
08-31 16:54:18.647  6992  7023 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 16:54:18.657   292   292 I ServiceManager: service 'nfc' died
08-31 16:54:18.657   292   292 I ServiceManager: service 'secontroller' died
08-31 16:54:18.657   292   292 I ServiceManager: service 'nfccontroller' died
,08-31 16:54:18.657  7147  7147 I NSApplication: Starting up...
,08-31 16:54:18.657  7147  7147 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x70ff141e in tid 7147 (.apps.magazines)
08-31 16:54:18.657  7147  7147 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 16:54:18.657  1810  1944 E WifiManager: Channel connection lost
08-31 16:54:18.657  1386  1626 E WifiManager: Channel connection lost
,08-31 16:54:18.667  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.677   292   292 I ServiceManager: service 'isub' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'simphonebook' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'iphonesubinfo' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'isms' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'phone' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'carrier_config' died
08-31 16:54:18.677   292   292 I ServiceManager: service 'sip' died
,08-31 16:54:18.677  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.697  5477  5477 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9cad2440 in tid 5477 (droid.apps.plus)
,08-31 16:54:18.697  5477  5477 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.697  4115  4115 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9a78c181 in tid 4115 (gle.android.gms)
08-31 16:54:18.697  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.707  4115  4115 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.707  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.707  6714  6714 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9d24bff8 in tid 6714 (droid.apps.maps)
08-31 16:54:18.707  6714  6714 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 16:54:18.707  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
08-31 16:54:18.707  5505  5505 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9dd4b9fe in tid 5505 (android.vending)
08-31 16:54:18.707  5505  5505 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 16:54:18.707  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.707   350   350 I Zygote  : Process 1691 exited due to signal (7)
08-31 16:54:18.707   350   350 I Zygote  : Process 3068 exited due to signal (7)
,08-31 16:54:18.717   350   350 I Zygote  : Process 7251 exited due to signal (7)
,08-31 16:54:18.717   350   350 I Zygote  : Process 6992 exited due to signal (7)
,08-31 16:54:18.717  7072  7072 D AndroidRuntime: Shutting down VM
,08-31 16:54:18.717  7072  7072 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f12059c in tid 7072 (oid.apps.photos)
,08-31 16:54:18.717  7072  7072 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.717  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.727   350   350 I Zygote  : Process 1705 exited due to signal (7)
,08-31 16:54:18.737   350   350 I Zygote  : Process 2021 exited due to signal (7)
,08-31 16:54:18.747   350   350 I Zygote  : Process 7147 exited due to signal (7)
,08-31 16:54:18.757   350   350 I Zygote  : Process 5477 exited due to signal (7)
,08-31 16:54:18.757   350   350 I Zygote  : Process 5505 exited due to signal (7)
,08-31 16:54:18.777   350   350 I Zygote  : Process 6714 exited due to signal (7)
,08-31 16:54:18.777   350   350 I Zygote  : Process 7072 exited due to signal (7)
08-31 16:54:18.777   350   350 I Zygote  : Process 4115 exited due to signal (7)
,08-31 16:54:18.797  7056  7056 I Mms/MmsApp:  start initViewCache mms
,08-31 16:54:18.797  7056  7056 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ddeab09 in tid 7056 (com.android.mms)
08-31 16:54:18.797  7056  7056 F libc    : Unable to open connection to debuggerd: Connection refused
,08-31 16:54:18.797  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:18.857   291   291 I lowmemorykiller: ActivityManager disconnected
08-31 16:54:18.857   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-31 16:54:18.867   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
08-31 16:54:18.867   350   350 I Zygote  : Process 7056 exited due to signal (7)
,08-31 16:54:18.867   293   544 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-31 16:54:18.927   312  1204 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb6a977a8 in tid 1204 (rild)
,08-31 16:54:18.927   312  1204 F libc    : Unable to open connection to debuggerd: Connection refused
08-31 16:54:18.927  2062  2062 E audit_log: File locking failed. error= Bad file descriptor
,08-31 16:54:19.116   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-31 16:54:19.116   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
,08-31 16:54:19.126   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3938c
,08-31 16:54:19.126   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3938c
,08-31 16:54:19.126   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3938c
,08-31 16:54:19.126   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef3938c
08-31 16:54:19.126   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef393a4
,08-31 16:54:19.146   293   293 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,08-31 16:54:19.146   293   293 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
08-31 16:54:19.146   293   293 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-31 16:54:19.156   293   544 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
