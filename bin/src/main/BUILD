load("@io_bazel_rules_groovy//groovy:groovy.bzl", "groovy_binary")

groovy_binary (
    name = "BazelApp",
    srcs = glob(["groovy/**/*.groovy"]),
    main_class = "example.Main",
deps = [
    '@maven//:org_springframework_boot_spring_boot',
    '@maven//:org_springframework_boot_spring_boot_autoconfigure',
    '@maven//:org_springframework_boot_spring_boot_starter'
  ],
)
