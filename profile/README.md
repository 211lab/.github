# 211 Lab

A self-hosted compute, storage, and Kubernetes platform — built, documented,
and run in the open.

211 Lab is a personal homelab: a Proxmox VE cluster hosting a highly-available
K3s Kubernetes platform with GitOps delivery, self-hosted services, and
infrastructure-as-code. This organization collects the repositories behind it.

## Projects

- **[atlas](https://github.com/211lab/atlas)** — the lab cluster: Ansible
  configuration management, the K3s control plane, GitOps (Gitea + Argo CD),
  storage, DNS, and operational runbooks.
- **[docs](https://github.com/211lab/docs)** — lab-wide documentation, including
  the network topology.
- **[guide](https://github.com/211lab/guide)** — a general guide to building a
  small homelab Kubernetes cluster on a single Proxmox VE host.
- **[language-model-research](https://github.com/211lab/language-model-research)**
  — benchmarking current language models.
- **[local-llm-troubleshooting](https://github.com/211lab/local-llm-troubleshooting)**
  — notes on running LLMs locally.

## Naming

Hosts and projects are named after pioneers and machines from computing
history.

| Name                            | What / Who                                                                                                                          | Why it matters                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Atlas**                       | A British supercomputer from the 1960s, developed by the University of Manchester, Ferranti, and Plessey. ([Wikipedia][1])          | It was one of the first machines to use virtual memory and strong support for multitasking/multiprogramming. It was extremely influential in early OS design. ([Wikipedia][1])                                                                                                                                                                             |
| **Titan (supercomputer, ORNL)** | A more recent U.S. supercomputer built by Cray Inc., operating from 2012 to 2019 at Oak Ridge National Laboratory. ([Wikipedia][2]) | Titan was notable for being among the first large supercomputers to use a hybrid architecture combining CPUs and GPUs. It pushed forward scientific simulation capability. ([OLCF][6])                                                                                                                                                                     |
| **Alan Turing**                 | English mathematician, logician and cryptanalyst (1912-1954). ([Wikipedia][3])                                                      | Often considered the father of theoretical computer science; he made foundational contributions (the Turing Machine model, the concept of algorithm/computation, breaking Enigma) which underlie modern computing. ([Wikipedia][3])                                                                                                                        |
| **Grace Hopper**                | American computer scientist and U.S. Navy Rear Admiral (1906-1992). ([Wikipedia][4])                                                | A pioneer in developing compilers and high-level programming. She also was instrumental in developing COBOL, promoted usability of programming, popularized the metaphor “debugging.” ([Wikipedia][4])                                                                                                                                                     |
| **Ada Lovelace**                | English mathematician and writer, 1815-1852. ([Wikipedia][5])                                                                        | Worked with Charles Babbage on his proposed Analytical Engine. She is often regarded as the first “computer programmer” because she wrote what is recognized as the first algorithm intended to be processed by a machine. She also had insight into how machines could go beyond number-calculations to more general symbolic processes. ([Wikipedia][5]) |
| **Charles Babbage**             | English mathematician, philosopher, inventor and mechanical engineer (1791-1871). ([Wikipedia][7])                                  | Designed the Difference Engine and proposed the Analytical Engine, which are considered precursors to modern computers. His ideas influenced Ada Lovelace and laid essential groundwork for the concept of programmable machines. ([Wikipedia][7])                                                                                                         |

[1]: https://en.wikipedia.org/wiki/Atlas_%28computer%29 "Atlas (computer)"
[2]: https://en.wikipedia.org/wiki/Titan_%28supercomputer%29 "Titan (supercomputer)"
[3]: https://en.wikipedia.org/wiki/Alan_Turing "Alan Turing"
[4]: https://en.wikipedia.org/wiki/Grace_Hopper "Grace Hopper"
[5]: https://en.wikipedia.org/wiki/Ada_Lovelace "Ada Lovelace"
[6]: https://www.olcf.ornl.gov/olcf-resources/compute-systems/titan/ "Titan - Oak Ridge Leadership Computing Facility"
[7]: https://en.wikipedia.org/wiki/Charles_Babbage "Charles Babbage"
