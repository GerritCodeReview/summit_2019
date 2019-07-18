# First-class Gerrit CI integration with Checks

In its 10 years of history, Gerrit has never offered a dedicated integration of
CI or analyzer systems. To work around that, people have used several
workarounds like integrating with Gerrit's label system instead. This approach
has several issues including a suboptimal user experience.

To improve that, we have designed a new way to integrate CI systems with Gerrit,
which is especially targeted at being flexible, robust/resilient, and scalable.

We are aware that many different CI systems and use cases exist. This was
especially taken into account for the base design. It's extensible enough so
that we can add many more features.

Within this talk, I will outline the base ideas of the new design and what it
means for integrating CI systems. Part of it is already implemented, which I
will show in a demo. I will also cover some future features we're envisioning
and how we think that the approach would need to be extended to work for
analyzers as well.

*[Alice Kober-Sotzek, Google](../speakers.md#aliceks) (Summit in Europe)*

*TBD (Summit in USA)*
