# shadowsocksr-libev
cmake -DCMAKE_C_COMPILER=gcc-9 -DCMAKE_CXX_COMPILER=g++-9 -Dwith_crypto_library=mbedtls -Dmbedtls_INCLUDE_DIRS="${STAGING_DIR}/usr/include" \
	-Dmbedtls_LIBRARIES="${STAGING_DIR}/usr/lib/libmbedtls.so;${STAGING_DIR}/usr/lib/libmbedx509.so;${STAGING_DIR}/usr/lib/libmbedcrypto.so" \
