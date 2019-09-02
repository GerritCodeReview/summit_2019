# Labels & Prolog-less submit rules - Control when changes become submittable

For many teams it is important to customize the conditions that make a change
submittable (e.g. to enforce non-author code reviews). The way to do this in
Gerrit is via labels and submit rules.

In this talk I explain how labels and submit rules work and what you can do with
them.

For submit rules the focus is on Prolog-less submit rules which are based on a
[new extension point](https://gerrit-review.googlesource.com/admin/repos/plugins/simple-submit-rules).
Using this extension point to implement submit rules is a good alternative to
writing
[Prolog submit rules](https://gerrit-review.googlesource.com/Documentation/prolog-cookbook.html#SubmitRule)
which often cause trouble because most people are not familiar enough with
Prolog. I will show an example implementation of a Prolog-less submit rule and
explain how you can develop your own custom submit rules.

[Presentation slides](https://docs.google.com/presentation/d/1fUjnmngWLFaexZKlN5XmL9EmOX8Nh_P0yJcThnlJ3Lk/edit?usp=sharing)

*[Edwin Kempin, Google](../speakers.md#ekempin)*
