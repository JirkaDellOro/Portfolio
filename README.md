# Inhaltsverzeichnis
- [Motivation](#motivation)
- [Coding](#coding)
- [Modelling](#modelling)
- [Video](#video)
- [Musik](#musik)
- [Grafik](#grafik)
- [Dokumente](#dokumente)

<hr/>  

# Motivation
Seit mein Vater, ein Professor für Computerspiele, mich bereits in sehr frühem Alter von 3 Jahren vorsichtig an dieses Medium herangeführt hat, interessierte ich mich nicht nur für das Spielen, sondern auch ähnlich stark für die Entwicklung von Games. Ich zeichnete zusätzliche Level für Super Mario oder entwarf neue Spiele, das könnte man als meine ersten Schritte im Gamedesign bezeichnen. Später verbrachte ich viel Zeit mit der Kombination der elementaren Redstone-Elemente von Minecraft um logische Schaltungen, Rechensysteme, Binärzähler und Segmentanzeigen zu konstruieren. Auch bereitete mir die Modifikation des Spiels durch selbst gestaltete Resourcepacks viel Freude.  

Im Alter von 9 Jahren begann mein Interesse am 3D–Modelling, was sich durch Architektur-Projekte in Google SketchUp und diverses Modeling in Sculpt3D wiederspiegelte. Mit 10 Jahren folgten kleinere Text-Games, die ich mit Batch – meiner ersten Programmiersprache - und dem Windows Editor umsetzte. Mit einem Leuchtturm von Fischer-Technik machte ich zu dieser Zeit auch erste Erfahrungen mit Ablaufsteuerungen. Am Nintendo-DS erstellte ich Zeichentrickanimationen über das Touchpad und kleine Stop-Motion-Trickfilme. Mit 11 Jahren begann ich mit der grafischen Bildbearbeitung mit Paint, mit 13 Jahren intensivierte ich dieses Hobby mit GIMP.  

Etwa zur selben Zeit befreite mich TypeScript aus der Unflexibilität von Batch, was mir die dynamische Generierung zweidimensionaler Bilder auf einem Canvas ermöglichte. Im Rahmen des mehrmals besuchten Kinder-Uni Feriencamps in Furtwangen machte ich erste Erfahrungen mit Processing und programmierte Pong. Jedes Erlernen eines neuen programmiertechnischen Werkzeuges verstärkte die Erkenntnis der Möglichkeit, dadurch meine Ideen in einem digitalem Medium festzuhalten, und sie von mir oder anderen, interaktiv oder passiv, später wieder abrufbar zu machen, was wiederum meine Motivation immer weiter steigen ließ.  

Auch begann ich, elektronische Musik mit FL-Studio zu produzieren, oft mit dem Hintergedanken, diese für Computerspiele zu verwenden.  

Ich erkannte durch die Programmierung die Relevanz der Mathematik in verschiedenen Bereichen und begann mit experimenteller Programmierung für verschiedene Fächer am technischen Gymnasium, wo auch meine erste formale Ausbildung in Informatik begann. Mit 15 Jahren entwickelte ich eine regelrechte Begeisterung für die Möglichkeiten der Vektorrechnung und fraktaler Geometrie. Zusammen mit einem Lehrer und einem Mitschüler, mit dem ich einen Übersetzer für eine ausgedachte Geheimsprache programmierte, gründete ich eine Informatik-AG. In dieser wagten wir uns an die voll umfassende Programmierung neuronaler Netzwerke zum Experimentieren mit künstlicher Intelligenz, besonders bezogen auf Echtzeit - Bildverarbeitung eines Live-Kamerabildes.  

Im Rahmen der freiwilligen Aufgaben des Programmieren-Moduls meines aktuellen Studiums entwickelte ich mit Java einen ewigen Kalender, Game-Of-Life und Tic-Tac-Toe. Letzteres baute ich zusätzlich mit einem zufällig spielenden Computergegner aus, der zum Trainieren einer künstlichen Intelligenz genutzt werden soll.  

Beim GlobalGameJam 2020 im Spiellabor der Hochschule wirkte ich in einem Team bei der Entwicklung eines VR-Spiels mit, wobei meine Hauptaufgaben bei Gamedesign und Sound lagen. Dieses Event weckte bei mir erneut die Interesse an der 3D-Programmierung und dem 3D-Modeling, weshalb ich mich momentan in Unity und Blender weiter vertiefe.  

Seit Oktober 2019 studiere ich nun Medieninformatik an der Hochschule Furtwangen. Das dritte Semester ist als Praxissemester vorgesehen und so bin ich auf der Suche nach einer entsprechenden Stelle ab Oktober 2020. Auf dieser Seite sammle ich einige meiner eigenmotivierten Arbeiten um einen Beleg für meinen Enthusiasmus und Lernfähigkeit zu liefern und Interesse für ein Angebot zu wecken.

<hr/>  

# Coding
## Fraktal
<a href="Code/Fraktal/start.html"><img src="Fraktal.PNG" alt="Fraktal" width="100%"/></a>  
Die Idee für diese Applikation kam mir auf, als ich die Möglichkeiten der grafischen Visualisierung durch Rekursion begriff. Das klare Endergebnis konnte ich mir, je nach Anzahl von Iterationen, noch nicht vorstellen, weshalb ich es sofort ausprobierte, mit dem Ziel, mich von meinem eigenen Programm zum Staunen zu bewegen. <br>
Instanzierte Bälle mit "create-children" Objektmethoden schafften dies bereits. Es folgten einige Experimente mit der maximal umsetzbaren Auflösung verschiedener Browser, um ein fertig gerendertes Bild von 1000 mal 10000 Pixeln zu erhalten, welches sich stark vergrößern lässt, um die repetitiven Strukturen nahtlos entdecken zu können. <br>
Daraufhin, ebenfalls ohne eine konkrete Vorstellung des Ergebnisses, begann ich den Farbwinkel abhängig von der Iterationsstufe und der Ordnung der circular Positionierten Kreise sowohl relativ, als auch absolut zu berechnen. Auch hier war ich von der Ästhetik der visualisierten Mathematik überrascht und begeistert. <br>
Auf der Seite können Sie einige Parameter der Berechnung verändern.

## FraktalAnimation
<a href="Code/FraktalAnimation/start.html"><img src="Animation.PNG" width="100%"></a>  
Zugrunde liegt das zuvor beschriebene Projekt "Fraktal". Diesmal mit dem Ziel, einige Parameter der Berechnung, die sich als Dezimalbrüche darstellen lassen, wie beispielsweise der Farbwinkel, zeitlich zu modulieren, um eine zusätzliche Dimension zu schaffen, die ebenso zu etlichen neuen Beobachtungen und weiteren Experimenten führen sollte. <br>
Bemerkenswert ist unter anderem der Zusammenhang, wie sich die Veränderung des Divisors eines Vollkreises, der die Positionierung der "children" eines jeden Balls bestimmt, auf die Bewegung und das Muster der Anordnung bis hin zu den kleinsten Bällen auswirkt, ebenso wie die entstehende Farbkonstillation

## Cardioids
<a href="Code/Cardioids/start.html"><img src="cardioids.PNG" width="100%"/></a>  

Dieses Projekt ist durch eine Präsentationsarbeit im Fach Mathematik der 13. Klasse entstanden. Meine Mitschüler und ich durften uns entweder aus vorgegebenen, oder eigens ausgesuchten fortgeschrittenen Themen der Mathematik widmen. Für letzteres wählte ich aus meiner schon bestehenden Kenntnis einiger mathematischer/physikalischer Phänomene die der Kardioide aus. <br>
Um die Beschreibung der dahinter liegenden Mathematik zu vermeiden, verweise ich an dieser Stelle auf das Endresultat innerhalb des Mathematik-Projekts, welches aus diesem vertonten [Video](#video) bestand.  <br>
Um den Mitschülern diese Thematik näher zu bringen und dafür zu faszinieren, programmierte ich diese Anwendung
Bei höheren Werten des in der Applikation auch von Ihnen einstellbaren Parameters "Faktor", sowie dem ab dann interressanten Parameter "Lines", ist für mich bis heute der eindeutige Zusammenhang der eingestellten Werte mit den entstehenden Mustern zugegebenermaßen nicht eindeutig erklärbar.

## RubberBand
<a href="Code/RubberBand/start.html"><img src="Rubber.PNG" width="100%"/></a>  
Grundlage für diese Physik-Simulation war die in Echtzeit stattfindende Anwendung physikalischem Verhaltens auf Körper, die von dem Mauszeiger beeinflusst werden. Durch simple Vektoradition erschuf ich damit schon ein System dreier gekoppelter Massen, deren Verhalten annähernd Gummibändern ähneln.<br>
Hierraus wird sich in naher Zukunft noch eine Simulation eines ganzen Rasters dieser Massen entwickeln, um Stoff zu simulieren (Cloth-Simulation).

<hr/>  

# Modelling                   
## Turret for Tower-Defense-Game
<iframe width="100%" height="300em" src="https://www.youtube.com/embed/VAOCARtbn54"
frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>  
Dies ist mein erstes 3D-Mesh-Modellierungsprojekt, daher wird in diesem Video teilweise unerfahrener Workflow wiedergegeben. Die Idee dazu kam mir, als ich einem Kollegen beim Programmieren eines 3D-Tower-Defense Spiels zuschaute.  
Abgesehen von dem Kugellager und den Läufen, bediente ich mich keinen Tutorials, um die Modelliertechniken herauszufinden, da ich ein möglichst individualisiertes Gatling-Geschütz erschaffen wollte. Ich verwendete hier alle elementaren Tools, die der Edit-Mode von Blender für Hard-Surface-Modeling zu bieten hat.  
Das Endresultat ist in dem Tower-Defense-Game meines Kollegen integriert

## Truhe
<img src="Truhe.png" alt="Truhe" width="100%">  
Dieses Projekt geht aus einer Computergrafik-Aufgabe hervor, deren Anforderung das Modellieren (Mesh ohne Material) einer symmetrischen Truhe, mitsamt eines Deckels und eines Rahmens war.  
Ich ging darüber hinaus, in dem ich aus der primitiven Geometrie Details wie Edelsteine durch Loop-Cuts, Extrudes und Insets erzeugte. Die Marmortexturen erzeugte ich prozedural über Noise-Nodes, die Holztextur ebenso über Noise, Musgrave und Voronoi Nodes, sowie Vektorkurven und Color-Burn-Nodes. 

## Deren Schloss
<img src="Schloss.png" alt="Schloss" width="100%">  
Die Anforderung für das Schloss war, aus einem größeren Würfel einen kleineren durch Insets oder dem boolean-Modifier auszustanzen.  
Um einen höheren Detailgrad zu erreichen, modellierte ich mit Bézierkurven eine etwas aufwendigere Ausstanzform für ein Schloss. Hier generierte ich die prozedurale Textur ebenfalls über die Steuerung der Normalenlänge auf der Oberfläche mittels eines mit Noise-Texturen angesteuerten Bump-Nodes(Displacements)

## Wackelpudding-Simulation  
<video width="100%" controls loop>
            <source src="Jelly.mp4" alt="Jelly" type="video/mp4"/>
            Ihr Browser unterstützt den Video-Tag nicht
</video>  
Hier habe ich weniger gemodelt, sondern eher aus freihen Stücken die Möglichkeiten der  Softbody&Collision Physik Simulation ausprobiert, und eine kleine Animation gerendert, um ein Wackelpudding-ähnliches Verhalten zu simulieren
  
## Das verrückte U-Boot  
<video width="100%" controls loop>
            <source src="submarine.mp4" alt="submarine" type="video/mp4">
            Ihr Browser unterstützt den Video-Tag nicht
</video>  
Die Anforderungen der Computergrafik-Aufgabe, die mich zu dieser Animation inspirierte, bestand darin, rein durch Skalierung, Rotation und Verschiebung von Objekten, sowie das Anwenden einfacher Materialien ein U-Boot zusammenzustellen. Der Anforderung, nur mit der Komposition primitiver Körper zu arbeiten, widersetzte ich mich nicht sondern nahm sie als Herausforderung an.  
Die Positionierung der Spirale aus Blasen erreichte ich durch Rotation langer Blasenreihen unter Proportionalem Bearbeiten. Ähnlich erreichte ich auch die Greifarme des U-Boots. Die Textur der Blasen erreichte ich durch die Mischung einer Noise-Textur und Transparenz. Die Volumetrische Beleuchtung erreichte ich durch die Addition eines Lichtstreuenden, und eines Licht-Absorbierenden Shaders mit unterschiedlicher Dichte. Die Bewegungsabläufe erreichte ich durch Keyframes und interpolierten Kurven. Dies war mein erstes Modellierungsprojekt mit einer zeitlich beschränkten Vorgabe.

## Schild   
<img src="Schild.png" alt="Schild" width="100%">
Die Grundidee für diesen Schild ist der Vorarbeitung eines Computergrafik-Vorlesungsskriptes, welches nun allerdings ersetzt wurde, zu verdanken. Hier hätte die Anforderung aus dem Modellieren eines Schildes, und dem Ausschneiden von Bereichen mit dem Boolean-Modifier bestanden.  
Ich ging durch die Modellierung komplexerer Details, sowie frei gestaltete Verzierungen durch Bézierkurven darüber hinaus. Auch hier verwendete ich Kombinationen aus Noise-Texturen, um detaillierte Shader zu erreichen.  

## Korallenriff  
<video width="100%" controls loop>
            <source src="CoralReef.mp4" alt="CoralReef">
            Ihr Browser unterstützt das Videoformat nicht
</video>
Dieses Projekt geht aus der aktuellsten Computergrafik-Aufgabe hervor. Das Modeling erfolgte über die Extrudierung eines "Control-Cage", auf dem der Catmull-Clark Algorithmus angewendet wurde Allerdings wurden auch hier keine Materialien gefordert, sondern der Umgang mit dem Displacement-Modifier verinnerlicht werden.  
Diesen ersetzte ich durch einen entsprechenden Displacement-Node, durch den ich nicht nur Oberflächenberechnungen der Versetzten Stellen verändern kann, um beispielsweise unterschiedliche Farben oder Rauigkeitswerte zu erreichen, sondern auch generell mehr Kombinations- und Steuerungsmöglichkeiten durch weitere Nodes, wie beispielsweise Noise-Nodes hatte.

## Donut
<img src="Donut.png" alt="Donut" width="100%">  
Dies ist mein Ergebnis des zweiten Levels der Blender-Tutorialreihe des <a href="https://www.youtube.com/watch?v=TPrnSACiTJ4">Blender Guru</a>s. Das durch proportionales Editieren und Scultping erreichte Mesh des Teigs wurde durch Noise-Texturen und Overlay-Variation mit Bump versehen und geshaded, sowie Texture-Painting angewandt, um leicht verbrannte Stellen zu malen.  
In der Tutorial Reihe wird eine Zuckerglasur verwendet, ich jedoch erwünschte mir eine Schokoladenglasur, die ich durch ein Node-Setup, in dem ein Glossy- und Diffuse Shader gemischt werden, erreichte. Auch hier ist etwas Displacement durch eine Noise-Textur meinerseits verwendet worden.

## Brennender Affenkopf  
<video width="100%" controls loop>
            <source src="Monkey.mp4" alt="Monkey">
            Ihr Browser unterstützt das Videoformat nicht
</video>  
Dies ist mein erstes Blender Projekt überhaupt. In diesem Erfahrungszustand hatte ich noch nie Topologie verändert, und somit für eine Mantaflow Feuer&Rauch-Simulation den vorgefertigten Affenkopf "Suzanne" verwendet, und eine Animation gerendert. Die Position der einzelnen Flammen wird durch eine Wolken-Textur über das Objekt bewegt, um einen höheren Grad an Zufall zu erreichen.  
Ein brennender Affenkopf kommt in dem Donut-Tutorial des <a href="https://www.youtube.com/watch?v=TPrnSACiTJ4">Blender Guru</a>s ganz zu Beginn vor,
                    allerdings gab es zu der Entstehungszeit Mantaflow noch nicht. Er demonstrierte das Feuer, umMotivation für Blender zu schaffen. Dieser Teil der ersten Folge war mit Mantaflow allerdings nicht nachahmbar, was mich nicht zum Aufgeben, sondern eigenständigem Nachforschen und Ausprobieren ermutigte, bis ich einen brennenden Affenkopf erhielt.

<hr/>  

# Video
## Cardioids - Tutorial
<iframe width="100%" height="300em" src="https://www.youtube.com/embed/A68-juE2ves"
frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"                allowfullscreen>
</iframe>

<hr/>  

# Musik
## Fuwashima (Soundtrack zum GlobalGameJam2020)
<audio controls>
            <source src="Musik/Fuwashima.mp3" type="audio/mp3">
            Ihr Browser unterstützt den Audio-Tag nicht
</audio><br>

## PiSong
<audio controls>
            <source src="Musik/PiSong.mp3" type="audio/mp3">
            Ihr Browser unterstützt den Audio-Tag nicht
</audio>

## VocalRemixTrap
<audio controls>
            <source src="Musik/VocalRemixTrap.mp3" type="audio/mp3">
            Ihr Browser unterstützt den Audio-Tag nicht
</audio>

<hr/>  

# Grafik
## Donald Trump, Kugelschreiberzeichnung
<img src="Zeichnungen/Trump.jpg" alt="Trump" width="100%">

## Schlafend im Bus, Kugelschreiberzeichnung
<img src="Zeichnungen/Sleep.jpg" alt="Sleep" width="100%"/>

## Tribal, Tuschezeichnung
<img src="Zeichnungen/Tribal.jpg" alt="Tribal" width="100%">

<hr/>  

# Dokumente
- [Daten und Lebenslauf](Lebenslauf.md)
- [Abiturzeugnis](CCF18022020_0001.jpg)
- [Semesternotenspiegel](Notenspiegel.pdf)
- [Empfehlungsschreiben](EmpfehlungCalvinDellOro.pdf)
- [Auszeichnung des Gymnasiums für kulturelles Engagement](CCF18022020_0003.jpg")
- [Hackathon-Urkunde](CCF18022020_0002.jpg)
- [Regelung zum praktischen Studiensemester](CCF18022020_0000.jpg)

