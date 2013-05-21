**Hint** is written in [SASS](http://sass-lang.com/).

It is suggested that you contribute to [Hint.css](https://github.com/chinchang/hint.css). Check [Hint.css contribution guidelines](https://github.com/chinchang/hint.css/blob/master/CONTRIBUTING.md) for more info.
If your contribution is about the namespaced or "@extend-only" implementation, then contribute to this project.

#Setup
1. [Fork the repo](https://help.github.com/articles/fork-a-repo) and clone it on your system.
2. Create a new branch out off `master` for your fix/feature. `git checkout new-feature master`

#Things to remember
- Do not fix multiple issues in a single commit. Keep them one thing per commit so that they can be picked easily incase only few commits require to be merged.

- For every new modifier (example `hint--success`, `hint--top`) added, make a separate file unless it fits into a current modifier file.

- Before submitting a patch, rebase your branch on upstream `master` to make life easier for the merger.

- **DO NOT** add the library builds (`hint.css` & `hint.min.css`) in your commits.

#Stay in touch

To catch all updates and discussion, join the mailing list: **hintcss@googlegroups.com**.

To subscribe: **hintcss+subscribe@googlegroups.com** or visit [here](https://groups.google.com/forum/?fromgroups=#!forum/hintcss).
