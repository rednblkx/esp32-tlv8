idf_component_register(
        SRCS tlv8.c
        INCLUDE_DIRS "include"
        REQUIRES mbedtls
        PRIV_REQUIRES esp32-utils)
