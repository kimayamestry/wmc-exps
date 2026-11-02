# Wireless & Mobile Communication (WMC) Experiments

This repository contains lab experiments, simulation scripts, and study implementations for **Wireless and Mobile Communication (WMC)**.

---

## 📋 Included Experiments

All experiment implementations, setups, and simulation code are compiled in [`wmc exps.txt`](./wmc%20exps.txt).

| Experiment | Title | Description |
| :--- | :--- | :--- |
| **Exp 2** | **Simulation of Basic Communication Channel** | Analog AM transmission, noise sweep analysis, and digital BPSK simulation. |
| **Exp 3** | **Cellular Network Spectrum Reuse** | Visualizing cellular reuse across geographic cells; comparing $N=3$ and $N=7$ cluster patterns. |
| **Exp 4** | **Wi-Fi Network Scanning** | Scanning SSIDs, measuring RSSI values, and channel congestion mapping. |
| **Exp 5** | **Signal Strength (RSSI) vs. Distance** | Wi-Fi router RSSI modeling using log-distance path loss equations. |
| **Exp 7** | **Bluetooth Communication Study** | Device pairing, transmission range testing, and performance analysis. |
| **Exp 8** | **Security in GSM** | Simulation and implementation of GSM security algorithms ($A3$, $A5/1$, $A8$) and authentication. |
| **Exp 9** | **Multipath Propagation & Small-Scale Fading** | Analysis of indoor/outdoor fading environments with Rayleigh and Rician distributions. |
| **Exp 10** | **Handover Behavior Analysis** | Field observation of mobile handover, RSRP metrics, and hysteresis margins. |

---

## 🛠️ Prerequisites & Libraries

The simulations require Python 3.8+ with standard scientific computing packages:

```bash
pip install numpy scipy matplotlib
```

---

## 🚀 Usage

You can reference or extract specific experiment blocks directly from [`wmc exps.txt`](./wmc%20exps.txt) and execute them in your Python environment:

```bash
python <experiment_script>.py
```
