# btfhub-archive

BTF files for existing published kernels that don't support embedded BTF.

The main repository can be found at [https://github.com/aquasecurity/btfhub](https://github.com/aquasecurity/btfhub).

> This is an automated repository, issues and PRs should go to main btfhub repository.

## Credits for this repository:

1. Itay Shakury (Aqua Security)
   - Idealization of the project
   - Planned for initial usage with Tracee
1. Rafael David Tinoco (Aqua Security)
   - Initial archive creator with Ubuntu, Fedora
   - Initial build logic and examples
   - Helped Mauricio developing BTFgen
1. Mauricio Vásquez (Kinvolk, Microsoft, Inspektor Gadged)
   - Early adopter and contributor
   - Developed BTFgen and invited Rafael to join efforts
1. Lorenzo Fontana (Former Elastic) & Leonardo di Donato (Former Elastic, Falco)
   - Helped reviewing and debugging BTFgen
1. Bryce Kahle (Datadog)
   - Big adopter
   - Big collaboration by providing missing BTF files for multiple distros
   - Golang version of the update script
1. Steven H
   - Contributor for missing BTF files and fixes
1. Sascha Grunert (Red Hat)
   - Contributor (fixes)
   - move amazon linux 1 into `amzn` path (#8)
1. Guy Arbitman (Sekreet)
   - Creator of BTFHUB online
   - Contributor for missing BTF files
   - Early adopter

Check git log for more.
