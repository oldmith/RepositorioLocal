exCamera extension for GameMaker Studio
version 1.0.2 by Alexander Vourtsis (http://www.vourtsis.com)


Installation

Add the exCamera.gex extension and also import the obj_ex_camera.object.gmx file in your project.
Import the easing.gml script file only if you plan on using easing functions.


License

This extension is provided AS-IS. You are allowed to use this extension for both freeware & commercial projects without any cost or attribution requirement.
Have fun with it and make more games!


Changelog

* version 1.0.2 (16 August 2014, 00:13 UTC+2)
Added ex_camera_set_bounds()
Added ex_camera_reset_bounds()

* version 1.0.1 (21 March 2014, 11:53 UTC+2)
Fixed ex_camera_set_scroll_offset(), could cause minor glitch if scrolling was already in effect
Fixed ex_camera_set_zoom_scale() not executing instantly, e.g. not working correctly in a Create Event
Fixed ex_camera_set_tilt_angle() not updating angle instantly
Fixed issue where fade overlay could flicker if you used ex_camera_fade_out_ext() along with easing

* version 1.0.0 (25 January 2014, 08:00 UTC+2)
Fixed support for multiple views, press Space key in the example gmz to test!
Fixed a minor bug calculating view size always by view 0, even for views other than 0
Fixed Flash and Fade overlays glitching when using multiple views
Fixed wrong overlay positioning when ex_camera_set_fade/flash_draw_target was used
Added ex_camera_set_region()
Added ex_camera_set_visible()
Added ex_camera_is_visible()
Added ex_camera_get_width()
Added ex_camera_get_height()

* version 0.8.1 (24 January 2014, 04:11 UTC+2)
Added ex_camera_set_shake_easing()
Added support in ex_camera_set_easing() for shake effect
Added support in ex_camera_reset_easing() for shake effect

* version 0.8.0 (23 January 2014, 21:16 UTC+2)
Added ex_camera_set_safe_area()
Added ex_camera_get_safe_area()
Added ex_camera_set_easing()
Added ex_camera_reset_easing()
Added ex_camera_set_scroll_easing()
Added ex_camera_set_flash_easing()
Added ex_camera_set_fade_easing()
Added ex_camera_set_tilt_easing()
Added ex_camera_set_zoom_easing()

* version 0.6.1 (13 October 2013, 15:09 UTC+2)
Added missing ex_camera_set_fade_color()
Added missing ex_camera_set_flash_color()

* version 0.6.0 (11 October 2013, 12:36 UTC+2)
New system to not require a tracking object (can move around obj_ex_camera manually)
Fixed case where if you did not set a tracking object at the beginning, most camera functions were glitchy
Changed ex_camera_scroll_by() and ex_camera_scroll_to() to use the viewport coordinates instead and offset easier
Fixed ex_camera_set_tracking_object()
Added ex_camera_is_fading()
Added ex_camera_is_scrolling()
Added ex_camera_is_flashing()
Added ex_camera_is_shaking()
Added ex_camera_is_zooming()
Added ex_camera_set_scroll_offset()
Added ex_camera_get_x_offset()
Added ex_camera_get_y_offset()

* version 0.5.0 (09 October 2013, 22:15 UTC+2)
First release of the extension
