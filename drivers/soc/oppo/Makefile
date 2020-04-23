obj-$(CONFIG_OPPO_COMMON_SOFT)	+=  oppo_project/
obj-$(CONFIG_OPPO_DEVICE_IFNO)	+=  oppo_devinfo/
obj-$(CONFIG_OPPO_DEBUG_ASSERT)	+=  oppo_trace/
obj-$(CONFIG_RECORD_MDMRST)     +=  oppo_mdmrst/
#//jie.cheng@swdh.sh, 2016/04/15, Add hypnus helper
obj-$(CONFIG_OPPO_HYPNUS)     +=  oppo_hypnus/
#ifdef VENDOR_EDIT
#//wenbin.liu@PSW.Kernel.MM, 2018/05/23, Add for Healthinfo monitor
obj-y     +=  oppo_healthinfo/
#endif /* VENDOR_EDIT */
#obj-y     +=  oppo_BScheck/
obj-y     +=  oppo_als_cali_value/

#//Zhaoan.Xu@PSW.MM.AudioDriver.Other, 2019/01/16, Add for criticallog
obj-y +=  oppo_criticallog/

#ifdef VENDOR_EDIT
#wen.luo@PSW.Kernel.MM, 2018/05/23, Add for Healthinfo monitor
obj-$(CONFIG_OPPO_SHUTDOWN_DETECT)	+=  oppo_shutdown_detect/
#endif /* VENDOR_EDIT */

#ifdefine VENDOR_EDIT
#GaoTing.Gan@PSW.MultiMedia.MediaServer, 2019/03/07, Add for kevent feedback
obj-y +=  oppo_kevent_feedback/
#endif /* VENDOR_EDIT */

#add by zhengzhiwei@RM.BSP.Sensors for oppo_alsps
obj-y +=  sensor/
