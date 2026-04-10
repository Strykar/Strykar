# Avinash H. Duduskar

I'm an independent researcher focused on Linux kernel datapath performance
and identity-aware networking, inspired by OpenBSD's pf/anchor and authpf.

My current work asks whether per-packet identity reconstruction is a
necessary cost in orchestrated environments, or an architectural
assumption worth revisiting and builds the measurement infrastructure
to answer that precisely.

My methods instrument the kernel's memory subsystem directly via PMU events,
per-program attribution, cross-architecture validation rather than relying
on application-level benchmarks that obscure where the cost actually lives.

I come to this through a long background in Linux and BSD systems and network
engineering - Slackware 3.1 through to production Kubernetes and eBPF.
