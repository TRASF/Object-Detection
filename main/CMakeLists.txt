
#
# Main component of TF Micro project 'person_detection'.
#

idf_component_register(
    SRCS
       
        "image_provider.cc"
        "main.cc"
       
        "model_settings.cc"
       
        "app_camera_esp.c"
        "esp_cli.c"

    PRIV_REQUIRES console spi_flash
    INCLUDE_DIRS "")
