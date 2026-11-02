# Prototypes

Six research prototypes. Three have one-command entry points for evaluation.

## Usable now (one command)

### 1. Sovereign Compute
Delay-tolerant job placement and resume when links are intermittent.

```bash
git clone https://github.com/JadeSileyWinditt/Soverign-Compute.git
cd Soverign-Compute
bash setup_and_run.sh
```

k-of-n placement, kill handling, resume-after-delay, persistent state, UDP loopback with drops.

### 2. Ultra-low-power 6G Baseband
Power-envelope check for a 2048-tile fabric under a 4 W limit.

```bash
git clone https://github.com/JadeSileyWinditt/Ultra-low-power-6G-baseband-architecture.git
cd Ultra-low-power-6G-baseband-architecture
bash setup_and_run.sh
```

stays_under_envelope() call, internal co-sim model (not silicon), chaos load-spike test, labeled power log.

### 3. Phx-passport
Local track store that does not treat missing history as an error.

```bash
git clone https://github.com/JadeSileyWinditt/Phx-passport.git
cd Phx-passport
bash setup_and_run.sh
```

record() / history(), empty list on miss, file-backed persistence, chaos wipe-and-recover test.

## Research prototypes

### 4. Rubik Aero
Structure-preserving discrete advection + near-wall model for Cd / Cl / L/D.
NACA 0012 benchmark included. Interactive 3D view available.

### 5. Residue Theorem 2D Particle Simulator
Complex-analysis residue theorem mapped to an interactive physics engine.

### 6. Holographic Horizon Shield v2
Boundary and horizon model (research).

---

Full evaluation steps and commercial contact: [EVALUATION.md](EVALUATION.md)

Authorship only on the public repositories. Source license by request.
