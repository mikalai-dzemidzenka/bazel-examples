load("//:genfile.bzl", "configtx_template")

configtx_template(
  name = "configtx-org",
  output = "configtx-org.yaml",
  template = "configtx-template.yaml",
  substitutions = {
    "{{.Organization}}": "org",
    "{{.Port}}": "7051",
  },
)
