set(requires esp-tls nvs_flash esp_event esp_netif esp_http_client)
idf_component_register(SRCS "blink_example_main.c"
                       INCLUDE_DIRS "."
                       REQUIRES nvs_flash esp_event esp_netif esp_wifi esp_http_client esp-tls)
