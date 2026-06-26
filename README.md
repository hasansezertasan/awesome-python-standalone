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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-32-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/hasansezertasan/awesome-python-standalone/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/hasansezertasan/awesome-python-standalone?color=green&label=updated"></a>
</p>

This curated list contains 32 awesome open-source projects with a total of 63K stars grouped into 5 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/hasansezertasan/awesome-python-standalone/issues/new/choose), submit a [pull request](https://github.com/hasansezertasan/awesome-python-standalone/pulls), or directly edit the [projects.yaml](https://github.com/hasansezertasan/awesome-python-standalone/edit/main/projects.yaml). Contributions are very welcome!

## What is a standalone Python application?

A **standalone Python application** runs on an end user's machine without asking them to install Python or any dependencies first. Instead of "set up a virtual environment, `pip install`, and hope the right interpreter is on the `PATH`," you hand over a single executable, archive, or installer that just works.

The tools below take different routes to get there — bundling the interpreter, downloading it on first run, or compiling to native code — each trading off artifact size, build time, and whether the target needs an internet connection or a pre-installed Python.

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Launchers](#launchers) _3 projects_
- [Freezers](#freezers) _17 projects_
- [Compilers](#compilers) _2 projects_
- [Zipapps](#zipapps) _2 projects_
- [Miscellaneous](#miscellaneous) _4 projects_
- [Others](#others) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
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

<details><summary><b><a href="https://github.com/ofek/pyapp">pyapp</a></b> (🥇19 ·  ⭐ 2K) - Runtime installer for Python applications. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ofek/pyapp) (👨‍💻 14 · 🔀 58 · 📥 120K · 📦 63 · 📋 70 - 38% open · ⏱️ 26.06.2026):

	```
	git clone https://github.com/ofek/pyapp
	```
</details>
<details><summary><b><a href="https://github.com/razorblade23/PyCrucible">PyCrucible</a></b> (🥉14 ·  ⭐ 200) - A robust, cross-platform builder and launcher for Python.. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/razorblade23/PyCrucible) (👨‍💻 4 · 🔀 5 · 📥 680 · 📦 3 · 📋 37 - 24% open · ⏱️ 13.04.2026):

	```
	git clone https://github.com/razorblade23/PyCrucible
	```
</details>
<details><summary><b><a href="https://github.com/AmadeusITGroup/uvbox">uvbox</a></b> (🥉12 ·  ⭐ 53) - Fast, simple and cross-platform Python application packaging. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/AmadeusITGroup/uvbox) (👨‍💻 3 · 🔀 2 · 📥 390 · 📋 6 - 33% open · ⏱️ 20.04.2026):

	```
	git clone https://github.com/AmadeusITGroup/uvbox
	```
</details>
<br>

## Freezers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Bundle the Python interpreter and dependencies into a self-contained package. Fully offline, larger artifact, no Python required on the target._

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥇39 ·  ⭐ 13K) - Freeze (package) Python programs into stand-alone.. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 500 · 🔀 1.9K · 📥 750K · 📦 89K · 📋 5.6K - 4% open · ⏱️ 21.06.2026):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥇30 ·  ⭐ 3.3K) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 210 · 🔀 520 · 📥 1.2K · 📦 870 · 📋 1K - 15% open · ⏱️ 26.06.2026):

	```
	git clone https://github.com/beeware/briefcase
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥈26 ·  ⭐ 420 · ➕) - py2app is a Python setuptools command which will allow.. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 31 · 🔀 44 · 📦 5.6K · 📋 520 - 39% open · ⏱️ 26.05.2026):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📥 63K / month):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥈25 ·  ⭐ 990) - Create standalone Windows programs from Python code. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" style="display:inline;" width="13" height="13"></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 25 · 🔀 110 · 📥 27K · 📦 2.2K · 📋 190 - 8% open · ⏱️ 21.06.2026):

	```
	git clone https://github.com/py2exe/py2exe
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥈25 ·  ⭐ 500 · ➕) - tool for creating installers from conda packages. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 80 · 🔀 170 · 📥 290 · 📦 27 · 📋 450 - 8% open · ⏱️ 22.06.2026):

	```
	git clone https://github.com/conda/constructor
	```
- [PyPi](https://pypi.org/project/constructor) (📥 230 / month):
	```
	pip install constructor
	```
</details>
<details><summary><b><a href="https://github.com/JonathonReinhart/staticx">staticx</a></b> (🥉23 ·  ⭐ 420 · ➕) - Create static executable from dynamic executable. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" style="display:inline;" width="13" height="13"></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JonathonReinhart/staticx) (👨‍💻 6 · 🔀 44 · 📥 260 · 📦 170 · 📋 170 - 31% open · ⏱️ 06.05.2026):

	```
	git clone https://github.com/JonathonReinhart/staticx
	```
- [PyPi](https://pypi.org/project/staticx) (📥 50K / month):
	```
	pip install staticx
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥉22 ·  ⭐ 1.6K) - Creates standalone executables from Python scripts with.. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 120 · 🔀 240 · 📋 1.1K - 3% open · ⏱️ 21.06.2026):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
</details>
<details><summary><b><a href="https://github.com/pytauri/pytauri">PyTauri</a></b> (🥉22 ·  ⭐ 1.4K · 💤) - Tauri binding for Python through Pyo3. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" style="display:inline;" width="13" height="13"></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytauri/pytauri) (👨‍💻 5 · 🔀 27 · 📥 710 · 📦 15 · 📋 50 - 26% open · ⏱️ 10.09.2025):

	```
	git clone https://github.com/pytauri/pytauri
	```
- [PyPi](https://pypi.org/project/pytauri) (📥 9.3K / month):
	```
	pip install pytauri
	```
</details>
<details><summary><b><a href="https://github.com/metaist/cosmofy">cosmofy</a></b> (🥉11 ·  ⭐ 110 · ➕) - Cosmopolitan Python Bundler. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/metaist/cosmofy) (🔀 1 · 📥 170 · 📦 2 · 📋 120 - 2% open · ⏱️ 13.01.2026):

	```
	git clone https://github.com/metaist/cosmofy
	```
- [PyPi](https://pypi.org/project/cosmofy) (📥 93 / month):
	```
	pip install cosmofy
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/mherrmann/fbs">fbs</a></b> (🥈25 ·  ⭐ 3.9K · 💀) - Create Python GUIs with Qt in minutes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥈24 ·  ⭐ 6.1K · 💀) - A modern Python application packaging and distribution.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥉20 ·  ⭐ 990 · 💀) - Build Windows installers for Python applications. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/skywind3000/PyStand">PyStand</a></b> (🥉16 ·  ⭐ 1.2K · 💀) - Python Standalone Deploy Environment !!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tusharsadhwani/packaged">packaged</a></b> (🥉10 ·  ⭐ 200 · 💀) - The easiest way to ship python applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/jlevy/py-app-standalone">py-app-standalone</a></b> (🥉10 ·  ⭐ 53 · 💀) - Standalone, relocatable Python app installs with uv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mbachry/exxo">exxo</a></b> (🥉9 ·  ⭐ 460 · 💀) - Build portable Python binaries. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/joaompinto/py2static">py2static</a></b> (🥉5 ·  ⭐ 3 · 💀) - Build Linux static binaries from Python scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Compilers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Compile Python to C or machine code for performance and obfuscation. Fully standalone, slowest to build._

<details><summary><b><a href="https://github.com/Nuitka/Nuitka">nuitka</a></b> (🥇31 ·  ⭐ 15K) - Nuitka is a Python compiler written in Python. Its fully.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" style="display:inline;" width="13" height="13"></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 210 · 🔀 770 · 📦 3.9K · 📋 2.8K - 5% open · ⏱️ 22.06.2026):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/wasmerio/py2wasm">py2wasm</a></b> (🥉16 ·  ⭐ 230 · 💀) - Nuitka is a Python compiler written in Python. Its fully.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Zipapps

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Package the application as an executable zip archive. Requires Python to already be installed on the target — best for internal/dev distribution._

<details><summary><b><a href="https://github.com/pex-tool/pex">pex</a></b> (🥇30 ·  ⭐ 4.2K) - A tool for generating .pex (Python EXecutable) files, lock files and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pex-tool/pex) (👨‍💻 130 · 🔀 310 · 📥 1.2M · 📋 1.2K - 4% open · ⏱️ 21.06.2026):

	```
	git clone https://github.com/pex-tool/pex
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉18 ·  ⭐ 1.9K) - shiv is a command line utility for building fully self contained.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 45 · 🔀 110 · 📥 2.9K · 📋 130 - 37% open · ⏱️ 22.05.2026):

	```
	git clone https://github.com/linkedin/shiv
	```
</details>
<br>

## Miscellaneous

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_If you can think of a more appropriate category for the items below, PRs welcome!_

<details><summary><b><a href="https://github.com/conda/conda-pack">conda-pack</a></b> (🥇31 ·  ⭐ 570 · ➕) - Package conda environments for redistribution. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/conda/conda-pack) (👨‍💻 42 · 🔀 98 · 📦 3.9K · 📋 180 - 7% open · ⏱️ 23.06.2026):

	```
	git clone https://github.com/conda/conda-pack
	```
- [PyPi](https://pypi.org/project/conda-pack) (📥 150K / month):
	```
	pip install conda-pack
	```
</details>
<details><summary><b><a href="https://github.com/winpython/winpython">WinPython</a></b> (🥈26 ·  ⭐ 2.3K · ➕) - A free Python-distribution for Windows platform, including.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/winpython/winpython) (👨‍💻 25 · 🔀 350 · 📥 130K · 📋 690 - 11% open · ⏱️ 21.06.2026):

	```
	git clone https://github.com/winpython/winpython
	```
</details>
<details><summary><b><a href="https://github.com/bjia56/portable-python">portable-python</a></b> (🥉14 ·  ⭐ 83 · ➕) - Portable Python binaries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bjia56/portable-python) (👨‍💻 4 · 🔀 6 · 📥 19K · 📦 11 · ⏱️ 10.03.2026):

	```
	git clone https://github.com/bjia56/portable-python
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/facebookincubator/xar">XAR</a></b> (🥉17 ·  ⭐ 1.6K · 💀) - executable archive format. <code>❗Unlicensed</code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" style="display:inline;" width="13" height="13"></code>
</details>
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
