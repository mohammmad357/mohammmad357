<div align="center">

# Experiments you can inspect. Results you can reproduce.

**Python · C11 · Algorithms · Storage recovery · Simulation**

I build small open-source engineering projects with readable implementations,
independent checks and documented boundaries.

[Pathfinding](https://github.com/mohammmad357/maze-signal) · [Storage](https://github.com/mohammmad357/crashvault) · [Simulation](https://github.com/mohammmad357/faultline) · [Inverter control](https://github.com/mohammmad357/PowerControlLab)

</div>

## Start here

| Project | The question | Evidence to explore |
|---|---|---|
| [**Maze Signal**](https://github.com/mohammmad357/maze-signal) | When is a longer route cheaper, and when does A* explore less? | Python/C parity, 500 seeded maps checked against Bellman-Ford, reproducible search footprints |
| [**CrashVault**](https://github.com/mohammmad357/crashvault) | What survives after an acknowledged write and a process restart? | Matching binary logs, truncation/corruption checks, explicit sync and recovery contracts |
| [**Faultline**](https://github.com/mohammmad357/faultline) | Can two languages reproduce the same stochastic event history? | 300 paired trajectories, independent replay, analytical checks and raw experiments |
| [**PowerControlLab**](https://github.com/mohammmad357/PowerControlLab) | How do inverter controllers behave under defined disturbances? | Simulation models, controller derivations, benchmark protocol and an experiment dashboard |

**Try Maze Signal first:** follow its [quick start](https://github.com/mohammmad357/maze-signal#quick-start), then inspect the [measured results](https://github.com/mohammmad357/maze-signal/blob/main/results/RESULTS.md).

## How I approach a project

- Define a small problem and its input contract.
- Check behavior against an independent reference or mathematical invariant.
- Publish commands, raw measurements and the conditions behind the numbers.
- Explain limitations alongside results; these projects do not establish production readiness.

The implementations were developed with AI coding assistance. Claims are tied to executable tests and documented experiments.

## Current direction

Make Maze Signal easier to try through a browser demonstration, improve first-use documentation,
and learn from reproducible bug reports and outside contributions. A browser demo is planned; it is not available yet.

If you try a project, open an issue in that repository with the command, environment,
expected behavior and actual result. Small, well-explained contributions are welcome.

<details>
<summary>فارسی — دربارهٔ این مجموعه</summary>

این مجموعه برای یادگیری و نمایش مهندسی قابل‌بررسی است: الگوریتم، بازیابی داده و شبیه‌سازی در Python و C.
برای شروع، Maze Signal را اجرا کن و بعد نتیجه‌ها و آزمون‌ها را ببین.
تمرکز فعلی روی استفادهٔ آسان‌تر، بازخورد واقعی و نگهداری پروژه‌هاست.
CrashVault یک موتور آموزشی کوچک است؛ Faultline پیش‌بینی بیماری نیست؛ نتایج PowerControlLab فعلاً شبیه‌سازی‌اند.

</details>
