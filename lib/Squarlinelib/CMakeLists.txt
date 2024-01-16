SET(SOURCES screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_screenshot_png.c
    images/ui_img_815904853.c
    images/ui_img_577774466.c)

add_library(ui ${SOURCES})
