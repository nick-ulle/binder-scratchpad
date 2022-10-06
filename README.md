# Binder Scratchpad

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nick-ulle/binder-scratchpad/HEAD)

This repo is set up so that it can be used with [Binder][] for [JupyterLab real-time collaboration][jl-rtc].

[Binder]: https://mybinder.org/
[jl-rtc]: https://jupyterlab.readthedocs.io/en/stable/user/rtc.html

Want to set up your own repo like this?

1. Set up a repo for [Binder][]. I learned how from [the Zero-to-Binder chapter in The Turing Way][ztb].
2. Configure the repo to enable JupyterLab RTC. I learned how from [this gist][jtpio-gist].

Then launch a Binder instance for the repo. After opening a notebook, you can find the URL to share with collaborators in the `Share` menu.

[ztb]: https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html
[jtpio-gist]: https://gist.github.com/jtpio/6ce26381703355e0ef1da4af742b7f72

It's also possible to set up JupyterLab RTC without Binder, but it's a bit more difficult and has potential security risks. See [this article][p2p-rtc] for details.

[ptp-rtc]: https://elc.github.io/posts/jupyter-collaborative/
