# Yen-Heng Yu

**Software Engineer | C++17 / Python | Algorithms, Simulation, and Decision Systems**

Taiwan (UTC+8) · Open to remote and Taiwan-based software engineering roles  
[LinkedIn](https://www.linkedin.com/in/yan-heng-yu/) · [Email](mailto:yanhengyu0719@gmail.com) · [IEEE publication](https://doi.org/10.1109/JSEN.2026.3671767)

I like building systems where a decision can be traced back to its state, data source, and test result. My recent work combines C++ decision logic, Python experiment tooling, large-scale simulation, and optimization research.

I hold an M.S. in Computer Science and Engineering from National Yang Ming Chiao Tung University and a B.S. in Mechanical Engineering from National Taiwan University.

## Selected Work

### [GTOmirage — Texas Hold'em Decision-System Case Study](https://github.com/KlockYu/gtomirage-case-study)

An independent research project that uses Texas Hold'em as a difficult, imperfect-information decision domain.

- Built the private C++17 system end to end: state representation, preflop and postflop policy modules, exact-combination opponent ranges, policy routing, and safety checks.
- Built Python tools that transform external solver output into versioned profiles and produce CSV, JSON, HTML, and Markdown review reports.
- Developed an offline simulator, frozen-baseline A/B workflow, targeted hand replays, and semantic regression tests rather than judging a policy from one favorable run.
- Generated a source-aware profile with **35,508 rows and no missing rows** while keeping **960 low-precision cases** visibly flagged for review.

The linked repository contains an engineering case study and a small, independently rewritten C++17 example using synthetic identifiers and weights. It does not contain production strategy code, private data, real-time assistance, automated interaction, or third-party platform integration.

### [Bi-Objective Optimization for Wireless Rechargeable Sensor Networks](https://github.com/KlockYu/wrsn-optimization-case-study)

Peer-reviewed research published in *IEEE Sensors Journal* (2026).

- Second author; implemented the proposed and comparison algorithms in Python, ran the simulation experiments, analyzed routing, cycle time, survival, and energy results, and drafted major technical sections.
- Under the paper's experimental setting, ADEC achieved a **95.5% network survival ratio** and an **18% improvement** over directional-charging baselines, while SPFC used **86.6% less long-term energy** than fundamental heuristics.
- [Read the published article via DOI](https://doi.org/10.1109/JSEN.2026.3671767).

## Technical Toolkit

| Area | Technologies and practices |
| --- | --- |
| Languages | C++17 (primary), Python |
| Core engineering | Data structures and algorithms, object-oriented design, simulation, combinatorial optimization |
| Reliability | Regression tests, replay-based validation, A/B comparison, structured logging, feature gates, rollback paths |
| Data and tools | Git, OpenCV, JSON, CSV, HTML reporting, command-line and batch workflows |

## What I Am Looking For

I am interested in software engineering roles involving C++, Python, algorithms, simulation, optimization, or decision infrastructure. I am based in Taiwan and open to remote collaboration across time zones.

If my background fits your team, contact me through [LinkedIn](https://www.linkedin.com/in/yan-heng-yu/) or [email](mailto:yanhengyu0719@gmail.com).
