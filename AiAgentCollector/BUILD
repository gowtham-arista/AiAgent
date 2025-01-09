cc_binary(
    name = "AiAgentCollector",
    srcs = [ "AiAgentCollector.cpp" ],
    deps = [
          "@prometheus-cpp//core:core",
          "@prometheus-cpp//pull:pull",
    ],
    linkstatic = True,
    linkopts = [ "-static" ],
)
