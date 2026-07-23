<!-- markdownlint-disable -->
<h1 align="center">
    awesome-python-standalone
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-4-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/hasansezertasan/awesome-python-standalone/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/hasansezertasan/awesome-python-standalone?color=green&label=updated"></a>
</p>

This curated list contains 4 awesome open-source projects with a total of 0 stars grouped into 5 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/hasansezertasan/awesome-python-standalone/issues/new/choose), submit a [pull request](https://github.com/hasansezertasan/awesome-python-standalone/pulls), or directly edit the [projects.yaml](https://github.com/hasansezertasan/awesome-python-standalone/edit/main/projects.yaml). Contributions are very welcome!

## What is a standalone Python application?

A **standalone Python application** runs on an end user's machine without asking them to install Python or any dependencies first. Instead of "set up a virtual environment, `pip install`, and hope the right interpreter is on the `PATH`," you hand over a single executable, archive, or installer that just works.

The tools below take different routes to get there — bundling the interpreter, downloading it on first run, or compiling to native code — each trading off artifact size, build time, and whether the target needs an internet connection or a pre-installed Python.

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Launchers](#launchers) _0 projects_
- [Freezers](#freezers) _0 projects_
- [Compilers](#compilers) _0 projects_
- [Zipapps](#zipapps) _0 projects_
- [Miscellaneous](#miscellaneous) _0 projects_
- [Others](#others) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(10000 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" style="display:inline;" width="13" height="13">&nbsp; Written in C
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13">&nbsp; Written in Python
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" style="display:inline;" width="13" height="13">&nbsp; Written in Rust
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" style="display:inline;" width="13" height="13">&nbsp; Written in C++
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" style="display:inline;" width="13" height="13">&nbsp; Written in Go

<br>

## Launchers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Small bootstrap binaries that download Python and dependencies on first run (typically via uv). Tiny artifact, but requires internet access the first time it runs._

<br>

## Freezers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Bundle the Python interpreter and dependencies into a self-contained package. Fully offline, larger artifact, no Python required on the target._

<br>

## Compilers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Compile Python to C or machine code for performance and obfuscation. Fully standalone, slowest to build._

<br>

## Zipapps

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Package the application as an executable zip archive. Requires Python to already be installed on the target — best for internal/dev distribution._

<br>

## Miscellaneous

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_If you can think of a more appropriate category for the items below, PRs welcome!_

<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://docs.python.org/3/library/zipapp.html">zipapp — Manage executable Python zip archives</a></b>  

🔗&nbsp;<b><a href="https://www.youtube.com/watch?v=3BfGAYfKZIg">Why it's so hard to redistribute standalone Python apps</a></b>  

🔗&nbsp;<b><a href="https://www.youtube.com/watch?v=xiwdz2LAtGc">How to use the Python embeddable redistribution to make standalone apps</a></b>  

🔗&nbsp;<b><a href="https://pydevtools.com/handbook/explanation/how-do-i-ship-a-python-application-to-end-users/">How do I ship a Python application to end users?</a></b>  


---

## What qualifies as a standalone Python tool?

To be listed here, a project must help package or distribute a Python application so it runs on a target machine **without the user manually installing Python or its dependencies**. Tools generally take one of these routes:

- **Bundle** the interpreter and dependencies into a self-contained artifact (freezers).
- **Bootstrap** Python on first run, typically via a small downloader (launchers).
- **Compile** Python to C or native machine code (compilers).
- **Package** the app as an executable archive that runs against an existing interpreter (zipapps).

If a project only manages virtual environments or installs packages for development — without producing something shippable to an end user — it likely belongs on a traditional best-of list, not this one.

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/hasansezertasan/awesome-python-standalone/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/hasansezertasan/awesome-python-standalone/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/hasansezertasan/awesome-python-standalone/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/hasansezertasan/awesome-python-standalone/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/hasansezertasan/awesome-python-standalone/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
