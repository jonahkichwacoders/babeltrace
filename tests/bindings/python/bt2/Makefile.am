check_SCRIPTS = testall.sh
EXTRA_DIST = 					\
	$(check_SCRIPTS)			\
	test_clock_class.py			\
	test_clock_class_priority_map.py	\
	test_component.py			\
	test_component_class.py			\
	test_connection.py			\
	test_ctf_writer_clock.py		\
	test_event.py				\
	test_event_class.py			\
	test_field_types.py			\
	test_fields.py				\
	test_graph.py				\
	test_notification.py			\
	test_notification_iterator.py		\
	test_packet.py				\
	test_plugin.py				\
	test_port.py				\
	test_stream.py				\
	test_stream_class.py			\
	test_trace.py				\
	test_values.py				\
	.coveragerc

LOG_DRIVER_FLAGS='--merge'
LOG_DRIVER = env AM_TAP_AWK='$(AWK)' $(SHELL) $(top_srcdir)/config/tap-driver.sh

if ENABLE_PYTHON_BINDINGS
TESTS = testall.sh
endif
