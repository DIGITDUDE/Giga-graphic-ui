SET(SOURCES components/ui_comp_sidebar.c
    components/ui_comp.c
    screens/ui_Screen1.c
    screens/ui_Screen2.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_screenshot_png.c
    images/ui_img_815904853.c
    images/ui_img_577774466.c
    images/ui_img_1080249043.c
    images/ui_img_1704086984.c
    images/ui_img_1714697232.c
    images/ui_img_877206327.c
    images/ui_img_lightbulb_png.c
    images/ui_img_add_png.c)

add_library(ui ${SOURCES})
