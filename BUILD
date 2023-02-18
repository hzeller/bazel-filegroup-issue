
cc_binary(
   name = "foo",
   srcs = ["foo.cc"],
)

cc_test(
   name = "foo_test",
   srcs = ["foo_test.cc"],
)

filegroup(
   name = "all_targets_filegroup",
   srcs = [
     ":foo",
     ":foo_test",
   ],
   testonly = True,
)
