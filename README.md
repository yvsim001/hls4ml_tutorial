# hls4ml_tutorial

Das Gebiet des Machine Learnings hat in den letzten Jahren eine rasante Entwicklung erlebt.
Gleichzeitig wächst der Bedarf, trainierte Modelle nicht nur in Software auszuführen, sondern direkt
auf dedizierter Hardware – insbesondere FPGAs – zu betreiben, um Latenzen im
Mikrosekundenbereich zu erreichen. Herkömmliche Werkzeuge bieten hierfür jedoch kaum
automatisierte Unterstützung, sodass Ingenieure bislang den zeitaufwendigen Weg über manuelle
Hardware-Beschreibungssprachen (HDL) oder manuelle HLS-Implementierungen gehen mussten.
Das hls4ml-Framework (High Level Synthesis for Machine Learning) wurde entwickelt, um genau diese
Lücke zu schließen. Es ermöglicht die automatisierte Übersetzung von in Python trainierten MLModellen (Keras, PyTorch, ONNX) in synthetisierbaren HLS-Code, der anschließend mit Vivado/Vitis
HLS auf einem FPGA synthetisiert werden kann. Die Entstehung des Frameworks ist eng mit der
Hochenergiephysik-Gemeinschaft am CERN Large Hadron Collider (LHC) [3] verbunden, wo EchtzeitTrigger Systeme mit geringen Latenzen benötigt werden, um relevante Kollisionsereignisse aus dem
enormen Datenstrom herauszufiltern.
Ziel dieser Projektarbeit ist es, das hls4ml-Framework zu erkunden, das offizielle Tutorial auf dem
PYNQ-Z1-Board durchzuführen und die Ergebnisse zu dokumentieren. Der Bericht gliedert sich in einen
Theorieteil, der die relevanten FPGA-Konzepte und Framework-Parameter erläutert, einen Praxisteil
mit detaillierter Beschreibung jeder Tutorial-Einheit sowie eine Diskussion der aufgetretenen Hürden
und einen Ausblick auf mögliche Weiterentwicklungen.
