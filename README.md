# hls4ml Tutorial – PYNQ-Z1 Board

> **Projektarbeit** | Fachhochschule Dortmund  
> Betreuer: Michael Karagounis  
> Autor: Yvan Simo

---

## Überblick

Dieses Repository dokumentiert die praktische Durchführung des offiziellen **hls4ml**-Tutorials auf dem **PYNQ-Z1 FPGA-Board**. Es umfasst einen theoretischen Hintergrund zum Framework, eine schrittweise Anleitung jeder Tutorial-Einheit sowie eine Diskussion aufgetretener Hürden und möglicher Weiterentwicklungen.

**hls4ml** (*High Level Synthesis for Machine Learning*) ist ein Open-Source-Framework, das die automatisierte Übersetzung von in Python trainierten ML-Modellen (Keras, PyTorch, ONNX) in synthetisierbaren HLS-Code ermöglicht – bereit zur Synthese mit Vivado/Vitis HLS auf einem FPGA.

---

## Motivation

Das Gebiet des Machine Learnings hat in den letzten Jahren eine rasante Entwicklung erlebt. Gleichzeitig wächst der Bedarf, trainierte Modelle direkt auf dedizierter Hardware zu betreiben, um **Latenzen im Mikrosekundenbereich** zu erreichen – ein Bereich, in dem klassische Software-Inferenz an ihre Grenzen stößt.

Bisherige Ansätze erforderten zeitaufwendige manuelle Implementierungen in Hardware-Beschreibungssprachen (HDL) oder manuelles HLS-Coding. hls4ml schließt diese Lücke durch **vollständige Automatisierung** des Übersetzungsprozesses.

Das Framework wurde ursprünglich für Echtzeit-Triggersysteme am **CERN Large Hadron Collider (LHC)** entwickelt, wo extrem geringe Latenzen nötig sind, um relevante Kollisionsereignisse aus einem enormen Datenstrom herauszufiltern.

---

## Ziel der Projektarbeit

- Das hls4ml-Framework erkunden und verstehen
- Das offizielle Tutorial vollständig auf dem PYNQ-Z1-Board durchführen
- Ergebnisse, Hürden und Erkenntnisse strukturiert dokumentieren

---

## Inhalt des Berichts

| Abschnitt | Beschreibung |
|---|---|
| **Theorieteil** | FPGA-Konzepte, HLS-Grundlagen, Framework-Parameter |
| **Praxisteil** | Detaillierte Beschreibung jeder Tutorial-Einheit |
| **Diskussion** | Aufgetretene Probleme und Lösungsansätze |
| **Ausblick** | Mögliche Weiterentwicklungen und Anwendungsfelder |

---

## Hardware & Software

| Komponente | Version / Modell |
|---|---|
| FPGA-Board | PYNQ-Z1 |
| Synthesetool | Vivado / Vitis HLS |
| Framework | hls4ml |
| ML-Backends | Keras, PyTorch, ONNX |
| Betriebssystem | Ubuntu 24.04 |
| Sprache | Python 3.x |

---

## Verwandte Ressourcen

- [hls4ml Dokumentation](https://hls4ml.readthedocs.io)
- [hls4ml GitHub Repository](https://github.com/fastmachinelearning/hls4ml)
- [PYNQ-Z1 Board Dokumentation](https://pynq.readthedocs.io)
- [CERN LHC Trigger Systems](https://home.cern/science/computing/trigger-and-data-acquisition)

---

## Lizenz

Dieses Repository dient ausschließlich akademischen Zwecken im Rahmen einer Projektarbeit an der Fachhochschule Dortmund.
