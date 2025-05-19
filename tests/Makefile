SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/wrappers/xor_test.v
xor:
	rm -rf sim_build
	$(MAKE) sim TOPLEVEL=dut MODULE=dut_test

include $(shell cocotb-config --makefiles)/Makefile.sim
