t-1059820287 for details.n the manual BUILD contents below.
    all_node_modules_target_name = "node_modules_a
        "//:.yarnrc",
    ],
    # Disabled because, when False, yarnepository. This is needed to link the shared
    # set of deps for example e2es.
    exports_directories_only = False,
    manual_build_file_contents = """\
filegroup(
    name = "node_modules_files",
