lib_wlr_types = static_library(
	'wlr_types',
	files(
		'data_device/wlr_data_device.c',
		'data_device/wlr_data_offer.c',
		'data_device/wlr_data_source.c',
		'data_device/wlr_drag.c',
		'seat/wlr_seat_keyboard.c',
		'seat/wlr_seat_pointer.c',
		'seat/wlr_seat_touch.c',
		'seat/wlr_seat.c',
		'xdg_shell/wlr_xdg_popup.c',
		'xdg_shell/wlr_xdg_positioner.c',
		'xdg_shell/wlr_xdg_shell.c',
		'xdg_shell/wlr_xdg_surface.c',
		'xdg_shell/wlr_xdg_toplevel.c',
		'xdg_shell_v6/wlr_xdg_popup_v6.c',
		'xdg_shell_v6/wlr_xdg_positioner_v6.c',
		'xdg_shell_v6/wlr_xdg_shell_v6.c',
		'xdg_shell_v6/wlr_xdg_surface_v6.c',
		'xdg_shell_v6/wlr_xdg_toplevel_v6.c',
		'wlr_box.c',
		'wlr_compositor.c',
		'wlr_cursor.c',
		'wlr_gamma_control.c',
		'wlr_idle_inhibit_v1.c',
		'wlr_idle.c',
		'wlr_input_device.c',
		'wlr_input_inhibitor.c',
		'wlr_keyboard.c',
		'wlr_layer_shell.c',
		'wlr_linux_dmabuf.c',
		'wlr_list.c',
		'wlr_matrix.c',
		'wlr_output_damage.c',
		'wlr_output_layout.c',
		'wlr_output.c',
		'wlr_pointer.c',
		'wlr_primary_selection.c',
		'wlr_region.c',
		'wlr_screenshooter.c',
		'wlr_server_decoration.c',
		'wlr_surface.c',
		'wlr_tablet_pad.c',
		'wlr_tablet_tool.c',
		'wlr_touch.c',
		'wlr_wl_shell.c',
		'wlr_xcursor_manager.c',
		'wlr_xdg_output.c',
	),
	include_directories: wlr_inc,
	dependencies: [pixman, xkbcommon, wayland_server, wlr_protos],
)
