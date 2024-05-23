add_library(data_structures
        bitset/bitset.c
        unordered_array_set/unordered_array_set.h
        unordered_array_set/unordered_array_set.c
        ordered_array_set/ordered_array_set.c
        ordered_array_set/ordered_array_set.h
        vector/vector.c
        vector/vector.h
        matrix/matrix.c
        matrix/matrix.h
        matrix/test_matrix.c
)

target_link_libraries(data_structures algorithms)