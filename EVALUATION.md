# Evaluation Guide

Three prototypes have a single setup-and-run script.

## Sovereign Compute
Delay-tolerant placement and resume.

```bash
git clone https://github.com/JadeSileyWinditt/Soverign-Compute.git
cd Soverign-Compute
bash setup_and_run.sh
```

## Ultra-low-power 6G baseband
Power-envelope check (internal co-sim model).

```bash
git clone https://github.com/JadeSileyWinditt/Ultra-low-power-6G-baseband-architecture.git
cd Ultra-low-power-6G-baseband-architecture
bash setup_and_run.sh
```

## Phx-passport
Local track store that does not error on missing history.

```bash
git clone https://github.com/JadeSileyWinditt/Phx-passport.git
cd Phx-passport
bash setup_and_run.sh
```

Each script installs what is needed, runs the main demo, then runs the chaos suite.

Commercial evaluation or source license: jadesileywinditt@gmail.com
