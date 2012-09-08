jQuery plugin for delayed hover mouse_out event.
It works similar to jQuert hover but has additional parameter - mouse_out_timeout.
It executes mouse_out callback with mouse_out_timeout delay, so mouse_out callback wont be executed when mouse cursor quickly returned to hoverable area.

###Usage

    $('some selector').hover_delayed(function() {
      // This is mouse_over callback code
    }, function() {
      // This is mouse_out callback code
    }, mouse_out_timeout_in_milliseconds);
