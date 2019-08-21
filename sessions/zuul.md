# Zuul: A project gating system for Gerrit and others

Zuul is a project gating system, which is like a CI or CD system, but
is focused on ensuring that changes are tested correctly before they
are merged.

Zuul was originally written for Gerrit and integrates very well with
it.  It also supports other systems (including GitHub) and allows
interaction between multiple systems.  Using Zuul's cross-repo
dependency feature, developers can seamlessly test a change to a
project in Gerrit that depends on an unmerged change to a project in
GitHub.

This presentation will provide an overview of Zuul, discuss how it
integrates with Gerrit, and how it can be used to promote
collaboration in enterprise environments.

*[Monty Taylor, Red Hat](../speakers.md#mordred)*
