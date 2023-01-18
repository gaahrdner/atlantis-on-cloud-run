# atlantis-on-cloud-run
~A set of @hashicorp Terraform configurations for running Atlantis on @googlecloud Cloud Run~

~This is not possible according to [the runtime contract](https://cloud.google.com/run/docs/reference/container-contract#filesystem) and [this comment](https://github.com/runatlantis/atlantis/issues/879#issuecomment-564782386). :(~

This may now be closer to reality based on some newer changes to Cloud Run, specifically [the support of Cloud Storage through a FUSE driver](https://cloud.google.com/run/docs/tutorials/network-filesystems-fuse).

More info [here](https://github.com/runatlantis/atlantis/issues/2869) and [here](https://stackoverflow.com/questions/74913423/error-chmod-on-config-lock-failed-operation-not-permitted).
