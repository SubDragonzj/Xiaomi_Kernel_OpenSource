GCC_VERSION      := $(shell $(CONFIG_SHELL) $(srctree)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
ccflags-y += -Idrivers/media/video/msm
ccflags-y += -Idrivers/media/platform/msm/camera_v2_rosy/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2_rosy
ccflags-y += -Idrivers/media/platform/msm/camera_v2_rosy/pproc/cpp
ccflags-y += -Idrivers/media/platform/msm/camera_v2_rosy/msm_buf_mgr/

obj-$(CONFIG_MSM_FD) += msm_fd_dev.o msm_fd_hw.o
