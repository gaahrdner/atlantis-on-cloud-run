# atlantis-on-cloud-run
~A set of @hashicorp Terraform configurations for running Atlantis on @googlecloud Cloud Run~

This is not possible according to [the runtime contract](https://cloud.google.com/run/docs/reference/container-contract#filesystem) and [this comment](https://github.com/runatlantis/atlantis/issues/879#issuecomment-564782386). :(
