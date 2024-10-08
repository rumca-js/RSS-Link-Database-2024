# Source:The Linux Foundation, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCfX55Sx5hEFjoC3cNs6mCUQ, language:en

## Compartmentalizing Vulnerable Kernel Components Without Stopping the Machine - Qinrun Dai
 - [https://www.youtube.com/watch?v=vNN5hI1q-kg](https://www.youtube.com/watch?v=vNN5hI1q-kg)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:37+00:00

Compartmentalizing Vulnerable Kernel Components Without Stopping the Machine - Qinrun Dai, University of Colorado - Boulder

Device drivers are relatively low-quality yet take 70% of the kernel codebase. Thus, attackers can exploit vulnerabilities in them. While compartmentalizing vulnerable drivers can enhance security, existing methods are limited, preventing them from being widely deployed: rebooting the system is necessary which inevitably interrupts services. Syzkaller’s data indicates that avg. 7.62 unique kernel panics are reported per day. It means the machine would need multiple reboots in one day to enforce compartmentalization, which is unacceptable. In this talk, we will explore the potential of on-the-fly enforcement, the main challenge of which lies in handling transition hazards - pre-existing objects are untracked and can be misused. We will demo this attack by exploiting CVE-2022-0995, followed by O2C which aims to mitigate transition hazards. O2C has two key technica

## Systemd & TPMs - Lennart Poettering, Microsoft
 - [https://www.youtube.com/watch?v=vT2uw25o0uM](https://www.youtube.com/watch?v=vT2uw25o0uM)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:37+00:00

Systemd & TPMs - Lennart Poettering, Microsoft

In this talk I'd like to give an update on what's new in systemd's various TPM related subsystems, such as disk encryption, PCR policy management, measurement APIs, event log and more.

## Enabling Hardware Security Modules for Confidential Computing - Reinhard Buendgen, IBM
 - [https://www.youtube.com/watch?v=uJcLJq_W3Qk](https://www.youtube.com/watch?v=uJcLJq_W3Qk)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:36+00:00

Enabling Hardware Security Modules for Confidential Computing - Reinhard Buendgen, IBM

Confidential Computing secures an important attack vector for sensitive workload: a provider cannot inspect or manipulate a confidential computing workload via its main memory or CPU registers. Yet confidential computing workloads are susceptible to other attacks (e.g., network attacks) like any other system. Therefore, certain workloads may require the use of a hardware security module (HSM) to protect their cryptographic keys. The usage of an HSM in a cloud gives raise to new attack vectors that need to be dealt with to establish a trustworthy relation between a virtual machine (aka guest) running in a trusted execution environment, the HSM and the cryptographic keys. The protection required goes beyond the establishment of a secure channel between the TEE and an attached device. This presentation reviews the security promises of confidential computing and HSMs, describes how to overcome the chal

## The Critical Path to Implant Backdoors and Potential Mitigation Techniques: Learnings from XZ...
 - [https://www.youtube.com/watch?v=hP7S8o9KqU8](https://www.youtube.com/watch?v=hP7S8o9KqU8)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:36+00:00

The Critical Path to Implant Backdoors and Potential Mitigation Techniques: Learnings from XZ - René Mayrhofer & Mario Lins, Johannes Kepler University Linz

An emerging supply-chain attack due to a backdoor in XZ Utils has been identified. The backdoor allows an attacker to run commands remotely on vulnerable servers utilizing SSH without prior authentication. We have analyzed the critical attack path to discuss current mitigation strategies for such kinds of supply-chain attacks.

## Hiding Attestation with Linux Keyring in Confidential Virtual Machines - Mikko Ylinen, Intel
 - [https://www.youtube.com/watch?v=EUnNL10n944](https://www.youtube.com/watch?v=EUnNL10n944)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:35+00:00

Hiding Attestation with Linux Keyring in Confidential Virtual Machines - Mikko Ylinen, Intel

Confidential computing (CC) is about processing application data in a trusted execution environment (TEE) that is provided by the hardware platform. Moreover, CC includes one crucial feature: remote attestation is used to get a proof of the TEE and the runtime environment authenticity and integrity before any secrets get provisioned. To ease confidential computing adoption, a smooth transition is critical. While confidential virtual machines allow users to easily move their existing workloads to run in TEEs making them attestation aware may still be disruptive. Ideally, no changes should be needed even when attestation gets involved. Linux Keyring offers an interesting choice to solve the challenge. By design, it can handle and store secrets without forcing workloads having to know about the security details involved. In this talk, we are going to cover the basics of CC and Linux Keyring. The

## Restricting Unprivileged User Namespaces in Ubuntu - John Johansen & Maxime Bélair, Canonical
 - [https://www.youtube.com/watch?v=GcVjng8WVeg](https://www.youtube.com/watch?v=GcVjng8WVeg)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:35+00:00

Restricting Unprivileged User Namespaces in Ubuntu - John Johansen & Maxime Bélair, Canonical

A retrospective on the work to restrict unprivileged user namespaces by default in Ubuntu 24.04. This presentation will cover the challenges, problems, and the solutions that Ubuntu choose. It will also take a look at work to address the problems that remain.

## Safer Seccomp: Dead Syscalls Elimination - Yuan Tan & Siqi Fan, Lanzhou University; Xiao Liu
 - [https://www.youtube.com/watch?v=84n0xvIj31Y](https://www.youtube.com/watch?v=84n0xvIj31Y)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:35+00:00

Safer Seccomp: Dead Syscalls Elimination - Yuan Tan & Siqi Fan, Lanzhou University; Xiao Liu, Yunnan University

Restricting system calls can significantly reduce the attack surface. However, solutions like seccomp can be bypassed(CVE-2009-0835, CVE-2019-2054, CVE-2023-2431, etc.). If unused syscalls can be eliminated at config level and compile time, the attack surface can be fundamentally controlled.
However, the widespread presence of .pushsection in kernel code prevents linker to perform code garbage collection. The associated KEEP() directive also causes ownership reversal issues, resulting in related sections that should be removed to remain, leaving more unused code for potential exploitation by hackers.
By systematically reworking the .pushsection directive, we propose dead syscalls elimination. After specifying the syscalls that need to be retained, it can remove other syscalls' code without affecting the normal operation of the kernel. Attackers cannot exploit something that

## Update on Landlock: IOCTL Support - Günther Noack, Google
 - [https://www.youtube.com/watch?v=K2onopkMhuM](https://www.youtube.com/watch?v=K2onopkMhuM)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:35+00:00

Update on Landlock: IOCTL Support - Günther Noack, Google

The Landlock security module lets Linux processes restrict what they can do and puts developers in charge of defining appropriate sandboxing policies for their programs. We will give a brief overview over Landlock’s current features, recent developments, and talk about what is next. We will discuss in more detail Landlock’s new support for restricting the use of IOCTL and the design considerations and trade-offs that went into it.

## Enabling New Security Frontiers: Deep-Dive Into Implementing Confidential Computing on RISC-V - R...
 - [https://www.youtube.com/watch?v=fHU1Ep5umq4](https://www.youtube.com/watch?v=fHU1Ep5umq4)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

Enabling New Security Frontiers: Deep-Dive Into Implementing Confidential Computing on RISC-V - Ravi Sahita, Rivos Inc.

This session aims to cover ISA and non-ISA for Confidential VM Environment (CoVE) on RISC-V platforms. The session will describe the use of ratified RISC-V privileged ISA extensions and new priv. ISA extensions called "Supervisor Domains" that are proposed and reaching task group consensus. This session will also describe the specifications for proposed non-ISA/ABI extensions and SoC requirements that enable Confidential Computing on RISC-V-based platforms - and the related open-source activities in open-source that are required to enable the confidential computing stack on RISC-V platforms. The common/abstract aspects that are cross-architectural will be discussed to enable interoperability across different RISC-V and non-RISC-V platforms. A future roadmap of capabilities will be discussed to encourage participation from the community.

## LVBS and Advanced Kernel Integrity - Thara Gopinath, Microsoft
 - [https://www.youtube.com/watch?v=O7NPWw9Yq9w](https://www.youtube.com/watch?v=O7NPWw9Yq9w)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

LVBS and Advanced Kernel Integrity - Thara Gopinath, Microsoft

Linux Virtualization based Security (LVBS) is a security feature that can a) harden the kernel and b) ensure that critical kernel resources remain untampered, even if the kernel gets compromised. VBS uses hardware virtualization and the hypervisor (Hyper-V) to create an isolated virtual environment that runs as a higher trust level, called Virtual Trust Level 1 (VTL1). In earlier talks on LVBS we explored the fundamentals of having a secure kernel running in VTL1 and how we support basic kernel integrity through LVBS. In this talk we explore how LVBS can be extended to offer advanced kernel integrity features. We examine the status quo in Linux kernel today and the various kernel features that manipulate page tables to inject/modify kernel code. We then discuss how these features can be hardened via LVBS to ensure that authenticity and integrity of the modified/loaded code can be ensured, even if the kernel is compromised

## SLUB Internals for Exploit Developers - Andrey Konovalov, xairy.io
 - [https://www.youtube.com/watch?v=2hYzxsWeNcE](https://www.youtube.com/watch?v=2hYzxsWeNcE)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

SLUB Internals for Exploit Developers - Andrey Konovalov, xairy.io

Every Linux kernel exploit that targets a slab memory corruption bug has to shape slab memory in a certain way to control which memory gets corrupted. For example, make the kernel put a specific slab object next to a buffer that can be overflown. Or replace a freed object with another one to overwrite it later via a use-after-free reference. Implementing different slab-shaping strategies requires a deep understanding of the SLUB allocator. This talk will cover the core SLUB allocator internals and explain how and why common slab memory shaping strategies work in Linux kernel exploits.

## Verifying and Signing EBPF Programs with Inspektor Gadget - Francis Laniel, Microsoft
 - [https://www.youtube.com/watch?v=cRY5oWO4kT0](https://www.youtube.com/watch?v=cRY5oWO4kT0)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

Verifying and Signing EBPF Programs with Inspektor Gadget - Francis Laniel, Microsoft. NOTE: For Virtual Attendees - This Session Will Be Audio Only

eBPF is now widely used, particularly in monitoring and observability. Sadly, it can modify the system behavior, by using helpers like bpf_override_return() or bpf_send_signal(). It was also the root cause of some CVEs, like CVE-2021-3489 or CVE-2021-3490. Inspektor Gadget is an eBPF tool and systems inspection framework for k8s, containers and linux hosts. eBPF programs run by Inspektor Gadget are packaged as OCI images. This was first done to ease users' lives so they can share and use other's. We also leveraged this to improve eBPF programs' security by signing and verifying them. This presentation will showcase how we make use of cosign to: 1. Sign our OCI images in our CI. 2. Verify them at runtime and deny the execution if the image was not signed with the given public key. Everyone can use Inspektor Gadget to sign and verify their

## Welcome & Opening Remarks - Elena Reshetova, Intel
 - [https://www.youtube.com/watch?v=S1r94G8yJMs](https://www.youtube.com/watch?v=S1r94G8yJMs)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

Welcome & Opening Remarks - Elena Reshetova, Intel

## Welcome Back & Remarks - Elena Reshetova, Intel
 - [https://www.youtube.com/watch?v=LgoZFe_0Oqw](https://www.youtube.com/watch?v=LgoZFe_0Oqw)
 - RSS feed: $source
 - date published: 2024-10-07T18:59:34+00:00

Welcome Back & Remarks - Elena Reshetova, Intel

## Keynote: EMBAG - The New Swiss Open Source Law and Its Implementation - Prof. Matthias Stürmer (PhD)
 - [https://www.youtube.com/watch?v=-yItywU-7WM](https://www.youtube.com/watch?v=-yItywU-7WM)
 - RSS feed: $source
 - date published: 2024-10-07T18:57:45+00:00

Keynote: EMBAG - The New Swiss Open Source Law and Its Implementation - Prof. Matthias Stürmer (PhD), Head of the BFH Institute for Public Sector Transformation

Starting from January 2024, the "Federal Act on the Use of Electronic Means for the Fulfillment of Government Tasks" (EMBAG) mandates the Swiss federal government to release its own software under an open source license. This new "Public Money, Public Code" law applies to all software developed by government programmers and external suppliers unless restricted by third-party rights or security concerns. Recent public tenders demonstrate the impact of this open source policy on national IT procurement. Additionally, new official guidelines on open source software release and community building suggest that the EMBAG law may lead to a paradigm shift in government software development and collaboration. Therefore, this presentation provides an overview of the new regulation and highlights evidence of its impact as well as early 

## Quick tips for first time Attendees at #kubecon #cloudnativecon
 - [https://www.youtube.com/watch?v=jydnjsfwBMY](https://www.youtube.com/watch?v=jydnjsfwBMY)
 - RSS feed: $source
 - date published: 2024-10-07T13:00:52+00:00

Are you excited to attend the KubeCon + CloudNativeCon North America 2024? Use these checklists to make this event unforgettable! See you in Salt Lake City from November 12–15! 

Learn more: https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/
#kubecon #cloudnativecon

