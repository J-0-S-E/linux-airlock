# Sources

Collected October 2026. Several are secondary reports that do not fully agree on dates and
package counts. Check Arch Linux's own news posts before relying on specifics.

## AUR malware, 2025-2026

- [LWN: malware in the AUR](https://lwn.net/Articles/1077619/): `-bin` browser packages with a RAT (July 2025), `plex-media-player` and `gnome-randr-rust` (2026)
- [Corgea: the openconnect-sso wave, August 2026](https://corgea.com/research/arch-aur-openconnect-sso-malware-wave-august-2026): taken-over packages, at least 89 names, adoption and pushes disabled
- [IT-Connect: Chaos RAT in three AUR packages](https://www.it-connect.fr/arch-linux-trois-paquets-aur-malveillants-destines-a-installer-le-malware-chaos-rat/)
- [OSTechnix: using the AUR safely](https://ostechnix.com/use-the-aur-safely-arch-linux/): the Atomic Arch campaign and `atomic-lockfile`, what was stolen
- [FOSS Linux: the AUR malware crisis](https://www.fosslinux.com/159893/arch-linux-aur-malware-security-crisis.htm)
- [Hexnode threat watch](https://www.hexnode.com/threat-watch/?p=616): SSH worming via `known_hosts`
- [Börse Express: AUR write access locked](https://www.boerse-express.com/news/articles/arch-linux-aur-schreibzugriffe-nach-paketuebernahmen-gesperrt-934748) (German)

## Fake repositories and packages

- [Cloud Security Alliance: FakeGit and AgentBaiting (July 2026)](https://labs.cloudsecurityalliance.org/wp-content/uploads/2026/07/CSA_research_note_fakegit-agentbaiting-mcp-supply-chain_20260721-csa-styled.pdf): READMEs written to steer AI coding agents
- [Cyber Security News: payload disguised as `/tmp/.sshd`](https://cybersecuritynews.com/hackers-hide-linux-payload-under-ssh-like-filename/amp/)
- [OSV MAL-2026-6377](https://osv.dev/vulnerability/MAL-2026-6377): base64-obfuscated URL, binary fetched without a checksum
- [SecurityWeek: manipulated GitHub search](https://www.securityweek.com/threat-actors-manipulate-github-search-to-deliver-malware/): fake stars and automated commits
- [Rushter: the rise of malicious repositories on GitHub](https://rushter.com/blog/github-malware/)

## General

- TuxCare, *Top Ten Cybersecurity Misconfigurations* (playbook, PDF from tuxcare.com/downloadables): allowlisting over blocklisting, sandboxing untrusted code in VMs
- TuxCare, *How to Recover from a Ransomware Infection* (guide, PDF from tuxcare.com/downloadables): disconnect first, never pay, never trust a compromised install, keep backups isolated
- [TuxCare: Linux security](https://tuxcare.com/blog/linux-security/)
