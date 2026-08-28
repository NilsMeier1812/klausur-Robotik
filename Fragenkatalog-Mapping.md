# Fragenkatalog → Foliensatz-Mapping

Diese Übersicht verknüpft jede Frage aus der `fragenkatalog-grundlagen-der-robotik.pdf`
mit der Stelle im passenden Foliensatz (VE01–VE13), an der der Stoff behandelt wird.
Ziel ist ein schneller Nachschlage-Index zum Lernen — Fragen sind auf ca. 10–15 Wörter
gekürzt/paraphrasiert, die vollständigen Antworten stehen im Fragenkatalog selbst.

**Wichtiger Hinweis:** Die im Fragenkatalog verwendeten Überschriften ("VL1", "VL 8",
"VL12" usw.) entsprechen **nicht** zuverlässig den VE-Nummern der aktuellen
Foliensatz-Dateien (z. B. ist der mit "VL1" überschriebene Block inhaltlich VE02
[Sensorik/Steuerung/Aktorik], und der "VL12"-Block ist inhaltlich VE10 [Maschinelles
Lernen] — VE12 existiert als Datei gar nicht). Die Zuordnung in dieser Tabelle wurde
daher **inhaltlich** durch Abgleich von Fragen-Stichworten mit dem tatsächlichen
Folieninhalt der aktuellen (SS2026-)Foliensätze vorgenommen, nicht anhand der
Katalog-Überschriften. Folienangaben beziehen sich auf die PDF-Seitenzahl (i. d. R.
identisch mit der aufgedruckten Folienzahl). Bei einigen Fragen ist die exakte Folie
nicht eindeutig bestimmbar (z. B. Freitext-/Zeichenaufgaben ohne direktes
Folien-Analogon, oder Inhalte aus einem älteren Studienjahr, die in der aktuellen
Foliensatz-Version nicht mehr wortgleich vorkommen); dort ist der Abschnitt/das
Kapitel angegeben und ggf. eine Unsicherheit vermerkt.

---

## VE01 – Einführung und Industrierobotik / neuartige Konzepte und Kinematiken

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 52–54 | Kategorien der Roboterunterteilung, Sicherheitsdefinition, normative Prüfungen | VE01 | Folie 15–16 (MRK-Sicherheit, Normen) |
| 55–58 | Risiko-Definition, Dreischritt der Risikominderung, inhärente Konstruktion, techn. Schutzmaßnahmen | VE01 | Folie 16 (Sicherheitsfunktionen zur Risikominderung) |
| 59–62 | Berührungslose Schutzeinrichtungen, Sicherheitsabstand, biomechan. Grenzwerte, Zielkonflikt | VE01 | Folie 16–18 (Risikobeurteilung, Arbeitssicherheit) |
| 85 | Definition Industrieroboter | VE01 | Folie 7 |
| 86–90 | 4 Roboterarten + Kinematik (Portal/Schwenkarm/Knickarm/Parallel) + Eigenschaften | VE01 | Folie 7–8 |
| 91 | SCARA: Abkürzung + Typ | VE01 | Folie 8 |
| 92 | Charakterisierung von Industrierobotern (4 Kenngrößenarten) | VE01 | Folie 9 |
| 93–94 | Genauigkeit Knickarmroboter, Absolut- vs. Wiederholgenauigkeit | VE01 | Folie 9–10 (ISO 9283) |
| 95 | Maßnahmen zur Steigerung der Genauigkeit | VE01 | Folie 10 |
| 101 | Arten der Roboterprogrammierung (Online/Automatisiert/Offline) | VE01 | Folie 11–12 |
| 105–106 | Sinn hybrider Montagesysteme, Eigenschaften Mensch/Roboter | VE01 | Folie 13 |
| 107–108 | Eigenschaften kollaborativer Roboter, Betriebsarten MRK | VE01 | Folie 14–16 |
| 161 | Wozu semantische Karten | VE01 | Folie 23–24 (Semantische Kartierung, KI-Pipelines) |
| 162 | Handhabung unbekannter Teile (generatives Greifen) | VE01 | Folie 25 (Reinforcement Learning, Greifen unbekannter Teile) |
| 163 | Nachteile von Getrieben zur Drehzahl/Momentwandlung | VE01 | Folie 32 |
| 166–167 | Tensegrity Robot, aktive/passive Seile am Handgelenk | VE01 | Folie 33 (Tensegrity-Robotergelenk) |

*Hinweis:* Frage 96–100 (Robotersteuerungsarten PTP/CP, Koordinatensysteme, Vorwärtstransformation)
sind inhaltlich Kinematik/Bahnsteuerung und daher unter VE03/VE05 einsortiert (s. u.).

---

## VE02 – Sensorik, Steuerung, Aktorik

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 1 | Sensor/Steuerung/Aktor unterscheiden | VE02 | Folie 4–6 (Systematik) |
| 2 | Unterscheidung der Sensoren (taktil/berührungslos) | VE02 | Folie 7–8 |
| 3–4 | Vor-/Nachteile kapazitiver Näherungsschalter | VE02 | Folie 9–10 |
| 5–6 | Messprinzip + Vor-/Nachteile Ultraschallsensoren | VE02 | Folie 11 |
| 7–9 | Messprinzipien optischer Sensoren, Gerätetypen, Lasertriangulation | VE02 | Folie 13, 15–17 |
| 10–17 | Pulslaufzeitmessung (TOF), LiDAR/Radar/Sonar, Pulsed/CW-Modulation | VE02 | Folie 18–20 |
| 18 | 5 Hauptklassen industrielle Bildverarbeitung | VE02 | Folie 21 |
| 19–22 | Structured Light Verfahren | VE02 | Folie 22 |
| 23–25 | ToF-Tiefenkamera | VE02 | Folie 23 |
| 26–28 | Stereoskopie | VE02 | Folie 24 |
| 29 | Messprinzip Dehnungsmessstreifen (DMS) | VE02 | Folie 27 |
| 30–33 | Sensordatenfusion (Daten-/Merkmals-/Symbolfusion) | VE02 | Folie 29–30 |
| 34–40 | Steuern vs. Regeln (Definition, Skizze, Anwendungsfälle, Grundaufgaben) | VE02 | Folie 33–36 |
| 41–42 | Robotersteuerung (Lücken), SPS-Zyklus | VE02 | Folie 37–39 |
| 43–45 | Motorarten (Gleichstrom/Synchron/Asynchron) | VE02 | Folie 41 |
| 46 | Harmonic-Drive-Getriebe (3 Bestandteile) | VE02 | Folie 43 |
| 47 | Vorteile dielektrischer Elastomere | VE02 | Folie 47–48 |
| 48–51 | Endeffektor-Definition, Greiferprinzipien, Prozesswerkzeuge | VE02 | Folie 49–54 |
| 164–165 | Energieeffizienter künstlicher Muskel, Vorteile dielektrischer Elastomere (Wdh. von Q47) | VE02 | Folie 47–48 |

---

## VE03 – Grundlagen der Roboterkinematik

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 63 | Was ist ein Graph in der Robotik | VE03 | Folie 7 |
| 64–66 | Graphformen, kinematische Kette, offene/geschlossene Ketten | VE03 | Folie 7–9 |
| 67 | ROS/URDF-Datei | VE03 | Folie 10 |
| 68 | 3 Koordinatensysteme /map, /odom, /base_link | VE03 | Folie 11–14 |
| 69–70 | Transformationsmatrix-Aufbau, Rotationsmatrix-Berechnung (k/i-Notation) | VE03 | Folie 18–23 |
| 71 | 3 Rotationswinkel Roll/Pitch/Yaw | VE03 | Folie 15 |
| 72 | Rotation durchführen (Klausuraufgabe) | VE03 | Folie 15, 25–26 |
| 73–74 | Mehrdeutigkeiten Gelenkwinkel, Singularitäten | VE03 | Folie 37 |
| 80 | Kleine Winkelgeschwindigkeiten → Lösung (Jacobi-Determinante, Bahnsteuerung) | VE03 | Folie 37 (Singularitäten/Jacobi) |
| 99–100 | 6 Koordinatensysteme der Robotik, Zweck der Vorwärtstransformation | VE03 | Folie 5–14 (Grundlagen Kinematik) *evtl. auch VE01/VE04* |

---

## VE04 – Grundlagen der Roboterdynamik

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 75 | Vorteile Quaternionen (Gimbal Lock, Speicherplatz) | VE04 | Folie 7–8 |
| 76 | Anzahl Euler-Winkel-Konventionen + Gimbal-Lock-Problem | VE04 | Folie 7–8 |
| 77 | Koordinatentransformation berechnen (Klausuraufgabe) | VE04 | Folie 4–8 (Übungsaufgabe, vgl. Ü2) |
| 78 | Einheitsquaternion für 90°-Drehung um Z berechnen | VE04 | Folie 7–8 |
| 79 | DH-Parameter-Tabelle ausfüllen | VE04 | Folie 14–24 |
| 81–83 | Lagrange-Verfahren, Newton-Euler-Algorithmus (Schritte, Vorteile) | VE04 | Folie 34–39 |
| 84 | Vorteile DH-Parameter-Darstellung | VE04 | Folie 14 |

---

## VE05 – Bahnplanung und Regelung

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 96–98 | Robotersteuerungsarten (PTP/CP/Splines), Synchron- vs. normales PTP | VE05 | Folie 97–99 |
| 102–104 | Bahnplanungsmechanismen (Landkarte/Zellzerlegung/Potentialfeld), Unsicherheiten | VE05 | Folie 9, 18, 21 |
| 109–121 | Aufgabe Bahnplanung, Konfigurationsraum/-hindernis, Bahn- vs. Trajektorienplanung | VE05 | Folie 9–11 |
| 122–129 | Klassische Verfahren: Landkarte, Zellzerlegung, Voronoi, Sichtbarkeitsgraph | VE05 | Folie 18–28 |
| 130–133 | Zellzerlegung (exakt/approximativ), Trapezzerlegung, hierarchische Zerlegung, Quadtree/Octree | VE05 | Folie 21, 35–37 |
| 134–135 | Dijkstra-Algorithmus, Heuristik für A* | VE05 | Folie 49–51 |
| 136–137 | Potentialfeldmethode (anziehend/abstoßend) | VE05 | Folie 78–82 |
| 138–148 | Sampling-based-Verfahren, PRM, EST, RRT, SBL | VE05 | Folie 89–94 |
| 149–153 | Steuerungsarten (Punkt-/Bahnsteuerung), PTP Vor-/Nachteile, Bewegungsprofile | VE05 | Folie 97–99 |
| 154 | Führungsgröße/Regelgröße/Stellgröße unterscheiden | VE05 | Folie 104–105 |
| 155–158 | Vor-/Nachteile Steuerung/Regelung, Regelungsarten, externe/interne Regelung | VE05 | Folie 106–107 |
| 168 | Voronoi-Region/-Kante/-Knoten definieren | VE05 | Folie 22–23 |
| 169 | Sichtbarkeitsgraph für ausgedehnte Roboter | VE05 | Folie 27–28 |
| 170 | Potentialfeldmethode: abstoßende Potentiale berechnen | VE05 | Folie 78–82 |

---

## VE06 – Grundlagen des Robot Operating System (ROS)

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 198–200 | Eigenschaften Robotersoftware, ROS-Definition, ROS-Philosophie | VE06 | Folie 8, 11 |
| 201–205 | Packages: Funktionalität, Inhalte, Metainformationen | VE06 | Folie 16–17 |
| 206–207 | ROS-Node starten (teleop/control), Node-Konzept + Vorteile | VE06 | Folie 14–19 |
| 208–209 | DDS-Standard, Discovery-Prozess | VE06 | Folie 24 |
| 210–213 | Topics: Zweck, Nachrichtenübertragung, Publisher/Subscriber | VE06 | Folie 19–24 |
| 214–215 | Services: Zweck, Request/Response-Prinzip | VE06 | Folie 37 |
| 216 | Parameter: Zweck + Aufbau (Key/Value/Descriptor) | VE06 | Folie 19 |
| 217–220 | Python-Code: Node-Klasse, Konstruktor definieren | VE06 | Folie 14–19 |
| 221 | 4 Programmiersprachen für ROS | VE06 | Folie 11 |
| 223 | 3 Kommunikationsarten (Topics/Services/Actions) | VE06 | Folie 19–37 |
| 224 | UE8-Programmcode: Publisher/Subscriber/Service/Parameter erklären | VE06 + VE07 | VE06 Folie 14–37 (Grundlagen), VE07 Folie 8–34 (Service/tf2/Actions-Anteile) |

---

## VE07 – ROS – Erweiterte Konzepte und Tools

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 222 | rqt-Tools (rqt_plot, rqt_image_view) | VE07 | Folie 36–38 |
| 225–228 | Actions: Kommunikationsbasis, Action Server/Client, Goal/Result/Feedback | VE07 | Folie 8–9 |
| 229–234 | Send-Goal-, Cancel-Goal-, Get-Result-Service-Ablauf | VE07 | Folie 10–13 |
| 235–236 | Anwendung/Struktur von Parameter, Topics, Services, Actions | VE07 | Folie 19 |
| 237–240 | Beschreibung Parameter/Topics/Services/Actions | VE07 | Folie 19 |
| 241 | tf2: statische/dynamische Transformation | VE07 | Folie 31–34 |
| 242–243 | Vorteil ros2 launch, 4 ROS-Tools (rqt/RViz/launch/bag) | VE07 | Folie 36–43 |
| 244–246 | Messages: Basis aller Kommunikationsarten, Aufbau (Header/Datenstruktur) | VE07 | Folie 19 (vgl. auch VE06 Folie 30–31) |
| 247 | Zweck von `colcon build` | VE07 | Kapitel „Packages der ROS-Community“ (Folie 20–28) |
| 248 | Zweck `ros2 launch` | VE07 | Folie 42 |
| 249 | ROS2 als Metabetriebssystem (2 Aspekte) | VE07 | Folie 5–6 *(vgl. VE06 Folie 11)* |
| 250 | DDS-Kommunikationsmodell (Publisher/Subscriber, Global Data Space) | VE07 | Folie 6 *(vgl. VE06 Folie 24)* |
| 251 | builtin_interfaces/Time stamp, string frame_id | VE07 | Folie 19 |
| 252 | 2 ROS2-Tools: colcon, rqt | VE07 | Folie 20–38 |
| 253 | Fallbeispiel: Topic/Service/Action-Wahl begründen | VE07 | Folie 8–19 (Kommunikationsarten-Vergleich) |
| 254 | Turtlesim-Subscriber-Code erklären | VE07 | Folie 40–43 (Übung RViz/Turtlesim) |

---

## VE08 – Robot Simulation

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 255–259 | Nutzen/Grenzen von Simulationen, Kosteneinsparung | VE08 | Folie 5–7 |
| 260 | 5 Simulationsarten (Ablauf-, Regelkreis-, MKS, FEM, Co-Simulation) | VE08 | Folie 4, 8 |
| 261–264 | Definition Simulation/System/Modell/Modellierung | VE08 | Folie 8 |
| 265–266 | 5 Schritte der Simulation, Modellbildung | VE08 | Folie 4, 8 |
| 267–269 | Bewegungssimulation starrer Körper, numerische Verfahren (Runge-Kutta vs. Euler) | VE08 | Kapitel Bewegungssimulation (nach Folie 8) |
| 270–272 | Mehrkörpersimulation: Merkmale, Probleme, Verbindungselemente | VE08 | Kapitel Mehrkörpersimulation |
| 273–278 | Kollisionserkennung (kontinuierlich/diskret), Hüllkörperarten | VE08 | Folie 23–25 |
| 279 | Effizientere Implementierung durch Simulationsframeworks | VE08 | Folie 23–29 |
| 280–281 | Motorsimulation: 2 Ansätze, elektromechanisches Modell | VE08 | Folie 28–29 |
| 282 | Software-in-the-Loop / Hardware-in-the-Loop | VE08 | Folie 30 |
| 283–285 | Störeinflüsse in Simulation, Kamerabild-Rauschen, Verifikation/Validierung Zweck | VE08 | Folie 32–35, 39 |
| 286–289 | Verifikation vs. Validierung, Techniken (Animation, Turing-Test etc.) | VE08 | Folie 39 |
| 290–298 | Vorgehen Gazebo, Werkzeuge, Welten/Modelle, Link/Joint/Plugin-XML, ROS-Schnittstelle | VE08 | Kapitel Gazebo / Übung (Folie 36–41) |
| 299 | 2 Typen von Abstandssensoren (1D/2D) in der Simulation | VE08 | Folie 32–33 |

---

## VE09 – Rechnersehen

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 300–302 | Photoelektrischer Effekt (äußerer/innerer) | VE09 | Folie 8 |
| 303 | 1D/2D/3D optische Sensoren mit Beispielen | VE09 | Folie 10 |
| 304–305 | Projektionsmatrix M=CSP·T | VE09 | Folie 15–17 |
| 306–310 | Abbildungsfehler: radiale Verzeichnung, chromatische/sphärische Aberration, Schärfentiefe | VE09 | Folie 18–21 |
| 311–312 | Aktive Triangulation + Herausforderungen | VE09 | Folie 24 |
| 313–315 | Tiefenberechnung: ToF-Prinzip + Herausforderungen | VE09 | Folie 23–24 |
| 316–318 | LiDAR: Vor-/Nachteile, Funktionsweise, 3 Varianten, Herausforderungen | VE09 | Folie 26–27 |
| 319–320 | Operatoren der Bildverarbeitung (Punkt/Lokal/Global) + Beispiele | VE09 | Folie 35–36 |
| 321–322 | Farbräume (Binär/Grau/Farbe), 3D-Farbräume (RGB/HSV/LAB) | VE09 | Kapitel Bildvorverarbeitung (vor Folie 35) |
| 323–325 | Tiefpassfilter (Mittelwert/Gauß/Median), Filterkerne | VE09 | Folie 37–38 |
| 326–329 | Hochpassfilter, Sobelfilter (X/Y) | VE09 | Folie 39–40 |
| 330 | Erosion/Dilatation: Öffnen/Schließen | VE09 | Folie 41–42 |
| 331 | Canny-Algorithmus (Gauß + Sobel-Kombination) | VE09 | Folie 43 |
| 332 | Projektionsmatrix-Faktoren (K, T, sx, sy, x0, y0, R, t) | VE09 | Folie 15–17 |
| 333 | Was ist OpenCV | VE09 | Folie 47 (Übung 11) |
| 334–335 | Kamerakalibrierung: Voraussetzung + Vorgehen (Schachbrettmuster) | VE09 | Folie 47 (Übung 11) |

---

## VE10 – Maschinelles Lernen

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 159 | Mensch. vs. künstl. neuronales Netz gegenüberstellen | VE10 | Folie 5–13 (Grundlagen KNN) *evtl. veraltet/nicht mehr wortgleich enthalten* |
| 160 | Beispiel Nutzung KNN (Wegerkennung) | VE10 | Folie 5–13 *evtl. veraltet, vgl. auch VE01 Folie 20–24 (Objekterkennung/semant. Karten)* |
| 336–337 | Ziel des Maschinellen Lernens, Regression vs. Klassifikation | VE10 | Folie 8 |
| 338 | Lineare Regression vs. linear trennbare Klassifikation | VE10 | Folie 8 |
| 339 | 3 Maschinelle Lernprinzipien (überwacht/unüberwacht/verstärkend) | VE10 | Folie 9 |
| 340 | 3 etablierte ML-Algorithmen (SVM, Random Forest, ANN) | VE10 | Folie 10 |
| 341 | Was sind künstliche Neuronen | VE10 | Folie 13 |
| 342–344 | Gradientenabstiegsverfahren, Vorgehen, Lernrate zu klein/groß | VE10 | Folie 18 |
| 345 | Ziel des Trainings (Loss-Minimierung) | VE10 | Folie 21 |
| 346–347 | Überanpassung + Vermeidungsmethoden (L1/L2/Dropout) | VE10 | Folie 21–22 |
| 348 | 3 Netzschichten für Bildverarbeitung (Faltung/Aggregation/Vollvernetzt) | VE10 | Folie 23 |
| 349 | Encoder-Decoder-Architekturen | VE10 | Folie 28 |
| 350 | Lösungen für großen Datenbedarf (Internet-Datensätze, Data Augmentation) | VE10 | Folie 33 |
| 351 | 3 Herausforderungen beim Training von KNN | VE10 | Folie 34 |
| 352 | Zusammensetzung des Datensatzes (Training/Evaluation/Test) | VE10 | Kapitel Datensätze (Folie 33–34) |
| 353–354 | Ausgabegröße Faltungs-/Aggregationsschicht berechnen (CNN-Rechenbeispiel) | VE10 | Folie 24–26 |

---

## VE11 – Seilrobotik

Keine Frage im Katalog ließ sich eindeutig VE11 zuordnen. Die einzigen Fragen mit
Seilrobotik-nahen Stichworten (Tensegrity-Roboter, aktive/passive Seile, Q166–167)
sind inhaltlich Teil der "neuartige Konzepte"-Sektion von **VE01** (Folie 33), nicht
von VE11 — im VE11-Foliensatz kommt dieses Beispiel nicht vor.

---

## VE13 – Service-, Pflege- und Medizinrobotik

| Frage-Nr. | Frage (kurz) | Foliensatz | Stelle (Folie/Abschnitt) |
|---|---|---|---|
| 171–173 | Serviceroboter, persönlicher/professioneller Serviceroboter definieren | VE13 | Folie 4, 9 |
| 174–178 | Taxonomie MRI nach Onnasch: Klassifikationscluster, Interaktionskontext, Anwendungsbereiche | VE13 | Folie 10–12 |
| 179–181 | Aufgabenstellung (8 Kategorien), Autonomiegrad (4 Ausprägungen) | VE13 | Folie 14 |
| 182–183 | Morphologie: Hauptformen + Betrachtungskategorien | VE13 | Folie 17 |
| 184–189 | Team-Charakteristik, räumliche/zeitliche Nähe, Interaktionsrolle, Kommunikationskanal | VE13 | Folie 18, 21, 23 |
| 190–192 | Akzeptanzrisiko, professionelle Service- vs. soziale Roboter, Technologieakzeptanzmodelle, Uncanny Cliff | VE13 | Folie 26, 30 |
| 193 | Ethische Bedenken bei Therapie-/Pflegerobotern | VE13 | Kapitel Pflege/Ethik (Folie 30–44) |
| 194 | Safety vs. Security in der Robotik | VE13 | Folie 33 |
| 195–197 | Pflege- vs. Industrieumfeld, Voraussetzung Privatumfeld, Formen MRI in Pflege/Therapie | VE13 | Kapitel Pflege/Ethik (Folie 34–44) |

---

## Abdeckungshinweis

Alle 354 Fragen des Katalogs (Q1–Q354) sind oben genau einmal (einzeln oder in einer
Gruppe aufeinanderfolgender Fragen) aufgeführt. Bei einzelnen Fragen ohne exaktes
Folien-Analogon (insb. reine Zeichen-/Rechenaufgaben oder Fragen zu evtl. aus
Vorjahren stammenden Inhalten) wurde die inhaltlich nächstliegende Foliensatz-Sektion
angegeben, ggf. mit "evtl. auch …"-Vermerk.
