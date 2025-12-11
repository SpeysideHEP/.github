[![arxiv](https://img.shields.io/static/v1?style=plastic&label=arXiv&message=2307.06996&color=brightgreen)](https://arxiv.org/abs/2307.06996)
[![DOI](https://img.shields.io/static/v1?style=plastic&label=DOI&message=10.21468/SciPostPhys.16.1.032&color=blue)](https://scipost.org/10.21468/SciPostPhys.16.1.032)
[![DOI](https://zenodo.org/badge/549515208.svg)](https://zenodo.org/badge/latestdoi/549515208)
[![doc](https://img.shields.io/static/v1?style=plastic&label&message=Documentation&logo=gitbook&logoColor=white&color=gray)](https://spey.readthedocs.io)

<img src="https://raw.githubusercontent.com/SpeysideHEP/spey/main/docs/img/spey-logo.png" alt="Spey logo" style="float: right; margin-right: 20px" align="right" width=250px/>

[![github](https://img.shields.io/static/v1?style=plastic&label&message=GitHub&logo=github&logoColor=black&color=white)](https://github.com/SpeysideHEP/spey)
[![PyPI - Version](https://img.shields.io/pypi/v/spey?style=plastic&link=https%3A%2F%2Fpypi.org%2Fproject%2Fspey%2F)](https://pypi.org/project/spey/)
![tests workflow](https://github.com/SpeysideHEP/spey/actions/workflows/tests.yml/badge.svg?branch=main&style=plastic)
[![Documentation Status](https://readthedocs.org/projects/spey/badge/?style=plastic&version=main)](https://spey.readthedocs.io/)
[![GitHub License](https://img.shields.io/github/license/SpeysideHEP/spey?style=plastic)](https://github.com/SpeysideHEP/spey/blob/main/LICENSE)

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/spey?style=plastic)
[![PyPI Downloads](https://static.pepy.tech/personalized-badge/spey?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/spey)
[![codecov](https://codecov.io/gh/SpeysideHEP/spey/graph/badge.svg?token=78Q76XFPTF)](https://codecov.io/gh/SpeysideHEP/spey)

# Spey: smooth inference for reinterpretation studies

Spey is a plug-in-based statistics framework designed to unify all likelihood models under a single, backend-agnostic interface. Its aim is to offer a common workspace where users can freely combine, analyse, and interpret statistical models built on entirely different backends. By standardising how likelihoods are accessed and evaluated, Spey facilitates seamless statistical inference across frameworks that would otherwise remain isolated.

At the core of Spey’s design lies a dedication to the FAIR principles, ensuring that statistical models and tools are Findable, Accessible, Interoperable, and Reusable. Spey only requires one key component from any model: the ability to compute the log-probability. Given this, it can carry out the full range of statistical tasks, including but not limited to fitting, calculating exclusion limits, computing, and running samplers, without being dependent on any specific backend.

This interoperability is made possible through Spey’s modular plug-in architecture. Developers can contribute their own statistical model prescriptions without modifying the Spey codebase. By publishing an independent Spey plug-in, following the guidelines detailed in the documentation, your model becomes automatically discoverable and usable by any Spey installation. The framework also provides built-in citation tools via metadata, ensuring contributors receive proper credit for their plug-ins.

With its flexible architecture, FAIR-driven approach, and emphasis on long-term sustainability, Spey provides a contemporary ecosystem for statistical inference that connects communities and tools across high-energy physics and beyond.

Finally, the name “Spey” originally comes from the Spey River, a river in the mid-Highlands of Scotland. The area “Speyside” is famous for its smooth whisky.
