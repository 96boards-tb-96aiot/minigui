## Makefile.am for MiniGUI using the framebuffer console video driver

AM_CPPFLAGS = -I$(abs_top_srcdir)/src/include -I$(abs_top_srcdir)/include \
			            -I$(abs_top_srcdir)/src/newgal/

noinst_LTLIBRARIES = libvideo_drmcon.la
libvideo_drmcon_la_SOURCES = $(DRMCON_SRCS)

DRMCON_SRCS = \
    fbvideo.c fbvideo.h \
    fb3dfx.c fb3dfx.h 3dfx_mmio.h 3dfx_regs.h \
    fbmatrox.c fbmatrox.h matrox_mmio.h matrox_regs.h \
    fbneomagic.c fbneomagic.h neomagic_mmio.h \
	pcivideo.c pcivideo.h pciinfo.h compiler.h \
	pci_smi.c pci_smi.h \
	drm_display.c drm_display.h libdrm_macros.h
