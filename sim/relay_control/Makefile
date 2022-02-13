all: test_isolated.net

test_isolated.net: test_isolated.sch
	gnetlist -g spice-sdb -o $@ $<

