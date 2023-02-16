SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/wrappers/dut_test.v
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
<<<<<<< HEAD
TOPLEVEL = dut_test
MODULE = dut_test
=======
VERILOG_SOURCES += $(PWD)/wrappers/dut_test.v
dut: 
	$(MAKE) sim MODULE=dut_test TOPLEVEL=dut_test
>>>>>>> 9306a0d (modified makefile)
include $(shell cocotb-config --makefiles)/Makefile.sim
