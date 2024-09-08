# The Raspberry Pi SBC in the Taichung residence of Buo-ren Lin

For providing services including but not limited to remote access to my Taichung residence.

<https://gitlab.com/brlin/brlin-taichung-home-rpi>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/brlin-taichung-home-rpi/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/brlin-taichung-home-rpi/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/brlin-taichung-home-rpi/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/brlin-taichung-home-rpi/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/brlin-taichung-home-rpi "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/brlin-taichung-home-rpi)

## References

The following materials are referenced during the development of this project:

* [DEFAULT_STDOUT_CALLBACK — Ansible Configuration Settings — Ansible Community Documentation](https://docs.ansible.com/ansible/latest/reference_appendices/config.html#default-stdout-callback)  
  Explains how to set the YAML stdout callback plugin.
* [githubixx/ansible-role-wireguard: Ansible role for installing WireGuard VPN. Supports Ubuntu, Debian, Archlinx, Fedora and CentOS.](https://github.com/githubixx/ansible-role-wireguard)  
  Explains how to use the githubxx.ansible-role-wireguard Ansible role.
* [How to find out if my Ubuntu/Debian Linux needs a reboot - nixCraft](https://www.cyberciti.biz/faq/how-to-find-out-if-my-ubuntudebian-linux-server-needs-a-reboot/)  
  Explains which file to check if the APT package management system considered the system requires a reboot to apply the updates.
* [Execute Ansible reboot with handler only when required - Stack Overflow](https://stackoverflow.com/questions/75272769/execute-ansible-reboot-with-handler-only-when-required)  
  Explains how to reboot the system only when the package management system considered necessary using Ansible's handler mechanism.

## Licensing

Unless otherwise noted(individual file's header/[REUSE.toml](REUSE.toml)), this product is licensed under [the 3.0 version of the GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), or any of its recent versions you would prefer.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.
