FFKI Ansible Documentation
==========================

This is the documentation for the automated ansible setup of Freifunk Kiel.

Documentation is split up into multiple parts:
 - Site setup: site.md
 - Gateway setup: gateway.md
 - Developer documentation: roles/*.md

# Limitations

The following limitations apply to the ansible roles in this repository:
 - Multi domain setups are not supported yet
 - Only setup of gateways is currently supported

# configuration:

 - `ffki_host_vars`

      in this submodule the secret keys are defined. The repository is not public, so
      this whole ansible config wil only wrk, if you define your own hosts there
 
 - `roles`

      see [/docs/roles/README.md](/docs/roles/README.md)

# usage

See [gateway.md](gateway.md) and [site.md](site.md)
