load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "BuickMain",
    srcs = [
        "BuickMain.java",
        "Greeting.java",
    ],
    main_class = "com.lottery.BuickMain",
    deps = [
        "//third_party:com_google_guava_guava",
        "//third_party:org_hamcrest_hamcrest_library",
        "//third_party:org_springframework_boot_spring_boot",
        "//third_party:org_springframework_boot_spring_boot_autoconfigure",
        "//third_party:org_springframework_boot_spring_boot_starter_web",
        "//third_party:org_springframework_boot_spring_boot_test",
        "//third_party:org_springframework_boot_spring_boot_test_autoconfigure",
        "//third_party:org_springframework_spring_beans",
        "//third_party:org_springframework_spring_context",
        "//third_party:org_springframework_spring_test",
        "//third_party:org_springframework_spring_web",
    ],
)
