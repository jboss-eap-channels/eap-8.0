# EAP-8.0 Manifest
This repository hosts the manifest for EAP 8.0. To use it copy
`installer-channels.yaml` to the `$JBOSS_HOME/.installation/` directory. Do
note this will override any customization done.

Alternative replace the `manifest` section of `eap-8.0` with the url to this
repository so it looks like:

    manifest:
      url: "https://raw.githubusercontent.com/jboss-eap-channels/eap-8.0/latest/manifest.yaml"
