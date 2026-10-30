# Evaluation Guide

Three prototypes have one-command entry points and chaos tests.

## Sovereign Compute
Delay-tolerant placement and resume.

```bash
git clone https://github.com/JadeSileyWinditt/Soverign-Compute.git
cd Soverign-Compute
python runner.py
bash chaos_tests/run_all_chaos.sh
```

## Ultra-low-power 6G baseband
Power-envelope check (internal co-sim model).

```bash
git clone https://github.com/JadeSileyWinditt/Ultra-low-power-6G-baseband-architecture.git
cd Ultra-low-power-6G-baseband-architecture
python envelope.py
bash chaos_tests/run_all_chaos.sh
```

## Phx-passport
Local track store that does not error on missing history.

```bash
git clone https://github.com/JadeSileyWinditt/Phx-passport.git
cd Phx-passport
python track_store.py
bash chaos_tests/run_all_chaos.sh
```

Commercial evaluation or source license: jadesileywinditt@gmail.com
