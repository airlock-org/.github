<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/airlock-org/.github/main/profile/assets/airlock-wordmark-thin-red-dark.svg">
    <img alt="AirlockOS" src="https://raw.githubusercontent.com/airlock-org/.github/main/profile/assets/airlock-wordmark-thin-red-light.svg" height="64">
  </picture>
</p>

AirlockOS is a desktop operating system combining [Qubes](https://www.qubes-os.org/)
isolation with [NixOS](https://nixos.org/) configuration and updates.

Xen runs the VMs, Qubes manages their isolation and communication, and Nix defines
the system configuration. Whole-machine updates and rollback keep the VMs on a
shared system generation while preserving their private data.

AirlockOS is under active development. Qubes OS security equivalence has not been
established.

- [Source code](https://github.com/airlock-org/airlock)
- [Security and limitations](https://github.com/airlock-org/airlock/blob/main/SECURITY.md)
