ADD_EXECUTABLE(compare_test compare_test.c)
TARGET_LINK_LIBRARIES(compare_test version)
ADD_TEST(compare_test compare_test)

ADD_EXECUTABLE(signature_test signature_test.c)
TARGET_LINK_LIBRARIES(signature_test version)
ADD_TEST(signature_test signature_test)

ADD_EXECUTABLE(compare_fuzzer compare_fuzzer.c)
TARGET_LINK_LIBRARIES(compare_fuzzer version)
