# Prolog-less submit rules, easy and for everyone

For many teams it is important to customize the conditions that make a change
submittable (e.g. to enforce non-author code reviews). The traditional way to do
this is via
[Prolog submit rules](https://gerrit-review.googlesource.com/Documentation/prolog-cookbook.html#SubmitRule),
but many project owners struggle with Prolog and find Prolog submit rules hard
to use. Writing, testing and maintaining complex Prolog rules can be difficult
and time-consuming. In this talk I want to introduce you to an alternative and
show you how submit rules can be easily configured from the WebUI by using the
[simple-submit-rules plugin](https://gerrit-review.googlesource.com/admin/repos/plugins/simple-submit-rules).
The plugin is based on a
[new extension point](https://gerrit-review.googlesource.com/admin/repos/plugins/simple-submit-rules)
that allows to implement submit rules in Java. I will explain how you can use
this extension point to add your own submit rules and how submit rules from
different plugins can be combined.

*[Edwin Kempin, Google](../speakers.md#ekempin)*
