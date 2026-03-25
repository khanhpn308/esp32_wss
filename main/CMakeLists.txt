idf_component_register(SRCS "app_main.c"
                    PRIV_REQUIRES mqtt esp_wifi nvs_flash
                    EMBED_FILES "mqtt_eclipseprojects_io.pem"
                    INCLUDE_DIRS ".")
