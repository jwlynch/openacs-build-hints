# used for build suggestion files

all: aolserver.config.step gd.configure.step tcl.configure.step tDOM.configure.step gdtclft.configure.step tcllib.configure.step tk.configure.step ImageMagick-configure-step TclMagick-configure-step xotcl.configure.step nspostgres-the.make.command


%: %.macro openacs-tools.m4
	m4 openacs-tools.m4 $< > $@

