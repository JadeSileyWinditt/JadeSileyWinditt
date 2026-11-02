# Three Usable Prototypes

Each can be cloned and run with one command.

## 1. Sovereign Compute
Delay-tolerant job placement and resume when links are intermittent.

```bash
git clone https://github.com/JadeSileyWinditt/Soverign-Compute.git
cd Soverign-Compute
bash setup_and_run.sh
```

What you get: k-of-n placement, kill handling, resume-after-delay, persistent state, UDP loopback with drops.

## 2. Ultra-low-power 6G Baseband
Power-envelope check for a 2048-tile fabric under a 4 W limit.

```bash
git clone https://github.com/JadeSileyWinditt/Ultra-low-power-6G-baseband-architecture.git
cd Ultra-low-power-6G-baseband-architecture
bash setup_and_run.sh
```

What you get: stays_under_envelope() call, internal co-sim model (not silicon), chaos load-spike test, labeled power log.

## 3. Phx-passport
Local track store that does not treat missing history as an error.

```bash
git clone https://github.com/JadeSileyWinditt/Phx-passport.git
cd Phx-passport
bash setup_and_run.sh
```

What you get: record() / history(), empty list on miss, file-backed persistence, chaos wipe-and-recover test.

---

Full evaluation steps and commercial contact: [EVALUATION.md](EVALUATION.md)

Authorship only on the public repositories. Source license by request.
