---
layout: post
title: Bloggen mit GitHub-Pages
subtitle: Start meines Web-Blogs über Java-Webtechnologien
tags: blogging jekyll github-pages
categories: miscellaneous
language: de
date: '2017-10-29'
author: Luis Wolff
---

Dies ist mein erster Blog-Eintrag auf meiner Web-Seite. Diesen möchte ich gerne dafür nutzen, den Lesern näher zu bringen, warum ich mich dafür entschieden habe, neben meiner beruflichen Tätigkeit auch zu bloggen und wie ich diesen umgesetzt habe. Ich werde die Blog-Technologie GitHub-Pages und Jekyll vorstellen und auf die Gründe eingehen, warum ich mich für diese entschieden habe.

<!-- end excerpt -->

Bloggen als Entwickler
===

Viele Menschen benutzen das Internet jeden Tag um sich über Aktuelles zu informieren. Softwareentwickler werden in dem Zusammenhang wohl am ehesten an den aktuellen Entwicklungen ihres bevorzugten Technologie-Stacks interessiert sein. Neben der reinen Information, wie bestimmte Technologien funktionieren, profitieren wir dabei auch von Meinungen und Einschätzungen anderer Internet-Anwender. Darauf aufbauend bilden wir uns eine eigene Meinung und entscheiden, was wir für zukünftige Softwareprojekte einsetzen möchten. Ich habe mich dafür entschieden einen Blog zu betreiben, da ich glaube auf diese Weise der Internet-Community wieder etwas zurückgeben zu können.

Diesen Blog möchte ich daher gerne nutzen, um den Lesern meine persönliche Einschätzung über Technologien, mit denen ich beruflich und privat zu tun haben, darzubringen. Dies umfasst hauptsächlich Java-, Datenbank- und Web-Themen. Darüber hinaus dient der Blog auch als eine Art öffentliches Notizbuch. Ich werde Ideen zu den oben genannten Punkten vorstellen und diese von unterschiedlichen Standpunkten aus beleuchten.

In meinem ersten Blog-Post möchte ich gerne über das Bloggen selbst schreiben. Ich zeige, wie ich aktuell vorhabe meinen Blog zu betreiben. Dabei werde ich auf die Blog-Technologie [GitHub-Pages](https://pages.github.com) eingehen, welche ich als Plattform zum Bereitstellen meiner Artikel verwende. Zuvor möchte ich aber kurz auf mein Hintergrundwissen als Entwickler eingehen, damit der Leser sich ein besseres Bild davon machen kann, warum ich mich für diesen Weg entschieden habe.

Mein Hintergrundwissen
===

Um mein Hintergrundwissen als Blogger darzulegen möchte ich hier auf zwei Punkte eingehen. Erstens; meine Expertise als Computer-Nutzer. Und zweitens; Die Fachgebiete, auf die ich mich als Entwickler fokussiere.

Als Computer-Nutzer folge ich wohl hauptsächlich dem Mainstream. Obwohl gerade bei Entwicklern und IT-Experten Unix-Systeme, wie Mac-OS oder Linux-Derivative, sehr beliebt sind, gehöre ich bei der Workstation eher zu der Windows-Fraktion. Zwar haben die anderen Systeme durchaus ihren Reiz, gerade wenn serverseitig ohnehin meistens Linux-Systeme verwendet werden und ich überwiegend mit Open-Source-Technologien arbeite. Dennoch bin ich es gewohnt, das Betriebssystem von Microsoft zu verwenden. Mit diesem kenne ich mich aus und weiß, wie ich die meisten Aufgaben schnell erledigen kann.

Wie eben bereits angedeutet, verwende ich beruflich als Softwareentwickler eher Open-Source-Technologien. Die Programmiersprache, die ich aktuell mit Abstand am besten kann, ist Java. Daneben beschäftige ich mich auch viel mit Frameworks, die vor allem im Enterprise-Umfeld eingesetzt werden. Die wichtigsten sind nach meiner Einschätzung [Java EE](https://github.com/javaee) (bzw. jetzt [Jakarta EE](https://jakarta.ee/)) und das [Spring Framework](https://spring.io). 

Als Enterprise-Entwickler bin ich stets bestrebt mein Wissen über Web-Standards und den Möglichkeiten von Serverbetriebssystem zu erweitern. Darüber hinaus ist es auch sehr wichtig, dass ich mich mit dem Persistieren von Daten auseinanderzusetzen, was in der Regel über Datenbanken gelöst wird. Es ist also zu erkennen, dass ich mich vorrangig mit Technologien beschäftige, die im Business-Umfeld verwendet werden um Geschäftsprozesse abzubilden.

Einige Leser könnten nun denken, dass es mit dieser Expertise für mich ein Leichtes sein müsste einen Web-Blog aufzusetzen und zu betreiben. Es könnte ja einfach ein Server mit einen HTTP-Dienst sowie einer Datenbank aufgesetzt und hier eine selbst geschriebene Blog-Anwendung deployed werden. Beispiele gibt es im Internet genügend, auf die aufgebaut werden könnte. Allerdings würde dies den Fokus zu stark auf die zugrunde liegende Technologie legen und weniger Zeit für das Verfassen von Beiträgen lassen. Daher wollte ich eine Blog-Engine verwenden, bei der ich mich nicht um die Infrastruktur kümmern muss.

GitHub-Pages und Jekyll
===

Während meines Studium zum Wirtschaftsinformatiker (Vertiefung Softwareentwicklung) habe ich mich mit der Plattform [GitHub](https://github.com) beschäftigt. Hierbei handelt es sich um eine serverbasierte Software zur Verwaltung von Git-Repositorien. Git wiederum ist eine Technologie mit dem Softwarequellcode dezentral versioniert werden kann. Diese Plattform bietet aber auch noch andere Features, die oft für die Verwaltung von Softwareentwicklungsprojekten genutzt werden können. Unteranderem bin ich so auch auf [GitHub-Pages](https://pages.github.com) gestoßen. 

Für den Aufbau meines Blogs fand ich GitHub-Pages sehr interessant, da es überwiegend auf Technologien aufbaut, mit denen ich als Entwickler sowieso arbeite. Änderungen können einfach über das Bereitstellen neuer Commits auf GitHub bereitgesellt werden. Es können Vorlagen verwendet werden, deren Anpassung mit HTML/CSS-Kenntnissen einfach möglich ist. Außerdem können einfache Texteditoren verwendet werden, um die Webseite aufzubauen. Dadurch muss ich mir keine Gedanken über die Bereitstellung einer Infrastruktur machen.

Das Bloggen mit GitHub-Pages funktioniert dabei wie folgt; Zunächst muss ein Repositorium auf GitHub für die persönliche Seite bereitgestellt werden. Dieses folgt dabei folgender Namenskonvention; `<Nutzername>.github.io`. Dadurch stellt GitHub automatisch eine entsprechende Internet-Domain bereit. Sie stellt den Content bereit, welcher im Master-Zweig des persönlichen Repositoriums gespeichert wird. Änderungen am Blog werden also veröffentlicht, indem Änderungen dorthin geschoben werden.

Ein Blog auf GitHub-Pages liefert nur statische Ressourcen aus. Eine serverseitige Logik gibt es also nicht, was es sehr einfach macht diese Technologie zu verstehen. Zwar schränkt dies die Möglichkeiten der Gestaltung deutlich ein. Auf der anderen Seite kann der Server sehr schnell auf Anfragen antworten, da er keine Seiten rendern muss.

Um nicht wiederkehrende Teile von HTML- und CSS-Dateien wiederholt schreiben zu müssen kann [Jekyll](https://jekyllrb.com/) verwendet werden. Hierbei handelt es sich um eine Rendering-Engine, mit der aus unterschiedlichen Textformaten statische Webseiten erzeugt werden können. Darüber hinaus bringt es viele Funktionen mit, die vor allem für die Bereitstellung von Blog-Posts nützlich sind. Die Handhabung ist nach meiner Einschätzung sehr eingängig, weshalb ich mich entschieden habe, meinen Blog mit GitHub-Pages und Jekyll umzusetzen.

Als Blogger möchte ich in der Regel einen Post betrachten, bevor er veröffentlicht wird. Um dies bewerkstelligen zu können, kann die Jekyll-Engine auch lokal auf einen PC ausgeführt werden. Allerdings ist hierfür ein Unix-System notwendig. Zum Glück ist die Software auch auf dem Ubuntu-Subsystem von Windows 10 lauffähig. Dadurch kann sie auch von mir als Windowsnutzer verwendet werden. Über die Bash kann nun ein HTTP-Server gestartet, so dass der gesamte Blog über einen Webbrowser betrachtet werden kann.

Schreiben von Blogposts
===

Nach dem nun die Blog-Webseite fertig designt ist, beginnt die eigentliche Arbeit des Bloggers; Das Verfassen von Blog-Posts. Daher betrachte ich in diesem Abschnitt, wie Inhalte für den eigenen Blog mit GitHub-Pages und Jekyll erstellt und gepflegt werden. Dazu gehe ich zunächst darauf ein, wie Blog-Post erstellt werden und welche Tools verwendet werden können.

Ein Blog-Artikel, welcher über GitHub-Pages bereitgestellt werden soll, muss grundsätzlich als [Markdown](http://markdown.de/)-Datei vorliegen. Er muss im Projektorder `_posts` abgelegt werden und folgt der Namenskonvention `<Jahr>-<Monatsnummer>-<Monatstag>-<Title>.md`.

Bei Markdown handelt es sind um ein textbasiertes Dateiformat, mit dem formatierter Text beschrieben werden kann. Das Besondere dabei ist, dass die Formatierung auch durch die reine Betrachtung der ASCII-Textdatei leicht erkennbar ist. Es wird oft für die Dokumentation von Software verwendet und unterstützt daher die gängige Formatierung, wie Code-Blöcke, Bilddarstellung, Aufzählungen und vieles mehr. Viele IDEs oder Versionsverwaltungstools (wie GitHub) sind in der Lage Markdown in HTML umzuwandeln und als Webseitenfragment darzustellen. Daher können in der Regel gängige Entwicklerwerkzeuge für das Erstellen beziehungsweise Bearbeiten dieses Dateiformat und damit auch Jekyll-Blogposts verwendet werden.

Um Metadaten, wie Autor, Kategorie oder Schlagwörter, bereitstellen zu können, kann das sogenannte Front Matter benutzt werden. Jekyll verwendet hier ein Format, dass auf YAML aufbaut. Front Matter wird einem Blog-Artikel vorangestellt und bei der Generierung der HTML-Seite ausgewertet. Eine Markdown-Datei mit Front Matter könnte wie folgt aufgebaut sein:

	---
	layout: myBlogLayout
	title: My Blog
	date: '2017-10-29'
	author: Luis Wolff
	---
	
	<!-- Markdown-text -->

Das Bearbeiten und Darstellen von Blogeinträgen ist eine Sache. Allerdings lebt ein Blog von seinen Texten, weshalb ein Blogger auf diesen seinen Fokus legen sollte. Eine IDE fokussiert dagegen auf Code, also auf formalisierte Sprache. Freitext wird dagegen kaum unterstützt. Oft ist zwar eine Prüfung vorhanden, ob die im Text enthaltenen Wörter in einem hinterlegten bzw. vom Nutzer definierten Wörterbuch vorkommen. Dass eine komplette Rechtschreib- oder Grammatikprüfung in einer IDE hinterlegt ist, ist mir nicht bekannt.

Leider konnte ich weder im Zusammenhang mit GitHub-Pages noch Jekyll Tools finden, die bei der Textgestaltung unterstützen. Es wäre wünschenswert, wenn es eine Anwendung gäbe, die beim Schreiben von Blog-Artikeln hilft Rechtschreib- und Grammatikregeln einzuhalten. Ich, als Windowsnutzer, habe mir einige Möglichkeiten bei der Verwendung von Microsoft Word angeschaut. Folgende habe ich untersucht:

 * **Konvertierung Worddokumenten**: Prinzipiell besteht die Möglichkeit, dass Worddokumente ins Markdown-Format konvertiert werden. Es gibt einige freie Tools oder Open-Source-Anwendungen, die das unterstützen. Allerdings ist das daraus resultierende Markdown nicht unbedingt gut leserlich, was der eigentliche Vorteil dieses Dateiformats sein sollte. Auch wird das Front Matter von Jekyll nicht unterstützt, weshalb dieses weiterhin manuell gepflegt werden muss. Dieser Ansatz führt also dazu, dass Blog-Artikel in zwei unterschiedlichen Dateien gepflegt werden müssen.
 * **Öffnen als ASCII-Textdatei**: Mit Microsoft Word ist es auch möglich Markdown-Dateien als ASCII-Textdatei zu öffnen. Formatierungszeichen können dabei nicht korrekt ausgelegt werden, sondern werden unverändert angezeigt. Eine falsche Interpretation durch die Rechtschreib- und Grammatikprüfung ist auch möglich. Der Vorteil ist aber, dass für die Blog-Artikel nur jeweils eine Datei gepflegt werden muss.

Ich habe mich letztendlich dafür entschieden, meine Blog-Artikel als ASCII-Datei in Word zu bearbeiten. Auf diese Weise muss ich keine Konvertierung von Dateiformaten vornehmen. Formatierungselemente von Markdown sind auch so eingängig, dass ich eigentlich keine Vorschau benötige. Auch kann auf diese Weise die Rechtschreib- und Grammatikprüfung von Word mit einigen Einschränkungen genutzt werden.

Zusammenfassung
===

Ich persönlich glaube, dass das Bloggen mit GitHub-Pages und Jekyll für Programmierer, die sich hauptsächlich auf ihrer eigentlichen Arbeit, das Programmieren von Software, konzentrieren wollen, recht interessant sein kann. Für mich ist das Bloggen ehr eine Nebentätigkeit und dient auch als eine Art Notizblock für spontane Ideen. Hierbei kann die Plattform GitHub-Pages mir viele aufwändige Infrastrukturaufgaben, wie das Bereitstellen und Warten eines Webservers, abnehmen. Durch das Verwenden von Jekyll muss ich mich auch nicht in ein komplexes Content-Management-System einarbeiten. Stattdessen kann ich auf Erfahrungen und Tools zurückgreifen, die ich als Softwareentwickler sowieso kenne. Wünschen würde ich mir aktuell noch eine bessere Unterstützung beim Schreiben von Blog-Artikeln. Alles in Allem denke ich aber, dass GitHub-Pages für mich die richtige Technologie ist, um neben meiner beruflichen Tätigkeit Ideen mit anderen Teilen zu können.
