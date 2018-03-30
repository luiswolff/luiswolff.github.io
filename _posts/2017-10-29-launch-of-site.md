---
layout: post
title: Bloggen mit GitHub-Pages
subtitle: Start meines Webblogs über Java-Webtechnologien
language: de
date: 2017-10-29
author: Luis Wolff
---

Mein neuer cooler Blog. Hier kommt der Abstract hin. Der erste Blog-Post behandelt das Bloggen mit GitHub-Pages und Jekyll.

<!-- end excerpt -->

Bloggen als Entwickler
===
Diese ist mein erster Blog-Eintrag auf meiner Web-Seite. Diesen möchte ich gerne dafür nutzen, den Lesern näher zu bringen, warum ich mich dafür entschieden haben, neben meiner beruflichen Tätigkeit auch zu bloggen. Dabei möchte ich auch gerne zeigen, wie ich meinen Blog mit GitHub-Pages umgesetzt haben. Dazu zählen die Gründe, warum ich mich für diese Blog-Technologie entschieden habe und eine subjektive Einschätzung ihrer Vor- und Nachteile.

Ich habe mich dafür entschieden einen Blog zu betreiben, da ich glaube auf diese Weise der Internet-Community wieder etwas zurückgeben zu können. Jeder von uns benutzt das Internet jeden Tag um sich über Aktuelles zu informieren. Softwareentwickler werden in den Zusammenhang wohl am ehesten an den aktuellen Entwicklungen ihres bevorzugten Technologie-Stacks sein. Neben der reinen Information, wie bestimmte Technologien funktionieren, profitieren wie dabei auch von Meinungen und Einschätzungen anderen Internet-Anwender. Darauf aufbauend bilden wir uns eine eigene Meinung und entscheiden, was wir für zukünftige Softwareprojekte einsetzen möchten.

Diesen Blog möchte ich daher gerne nutzen, um den Lesern meine persönliche Einschätzung über Technologien, mit denen ich beruflich und privat zu tun haben, darzubringen. Dies umfasst in der Regel Java-, XML- und Web-Technologien. Darüber hinaus dient der Blog auch als eine Art öffentliches Notizbuch. Ich werde meine Ideen zu den oben genannten Technologien vorstellen und diese von unterschiedlichen Standpunkten aus beleuchten. 

In meinen ersten Blog-Post möchte ich gerne darüberschreiben, wie ich zum aktuellen Zeitpunkt vorhabe meinen Blog zu betreiben. Wie dem Titel schon zu entnehmen ist setze ich als Blog-Technologie auf GitHub-Pages. Bevor ich habe aber erläutere warum ich mich hierfür entschieden habe werde ich noch etwas zu meinen Hintergrundwissen sagen.

Mein Hintergrundwissen
===
Um mein Hintergrundwissen als Blogger darzulegen möchte ich hier auf zwei Punkte eingehen. Erstens; meine Expertise als Computer-Nutzer. Und zweitens; Die Fachgebiete, auf die ich mich als Entwickler fokussiere.

Als Computer-Nutzer folge ich wohl hauptsächlich den Mainstream aller Nutzer. Obwohl gerade bei Entwicklern ehr Unix-Systeme, wie Mac-OS oder Linux-Derivative, sehr beliebt sind, gehöre ich ehr zu der Windows-Fraktion. Zumindest was die Workstation angeht. Ich muss zwar zugeben, dass die anderen Systeme durchaus ihren Reiz haben, gerade wenn Serverseitig ohnehin Unix-Systeme verwendet werden und ich überwiegend mit Open-Source-Technologien arbeite. Dennoch bin ich es doch ehr gewohnt das Betriebssystem von Microsoft zu verwenden, da ich mich hier auskenne und weiß, wie ich die meisten meiner Aufgaben schnell erledigen kann.

Wie eben bereits angedeutet, verwende ich beruflich als Softwareentwickler ehr Open-Source-Technologien. Die Programmiersprache, die ich aktuell mit abstand am besten kann, ist Java. Neben der Programmiersprache selbst beschäftige ich mich auch viel mit Frameworks, die vor allem im Enterprise-Umfeld eingesetzt werden. Die wichtigsten sind dabei Java EE (bald wohl Jakarta EE) und Spring. Darüber hinaus bin ich steht bestrebt mein Wissen über Web-Standards und den Möglichkeiten von Serverbetriebssystem zu erweitern. Neben den reinen Web-Technologien ist es für mich als Full-Stack-Webentwickler auch sehr wichtig, mich mit Persistenz von Daten auseinanderzusetzen. Ich beschäftige mich also vorrangig mit Technologien, die vor allem im Business-Umfeld verwendet werden, da Geschäftsprozesse abgebildet werden sollen.

Wenn man liest, welche Expertise ich mitbringe, könnte man denken, dass für mich ein leichtes sein müsste einen Web-Blog aufzusetzen, zu betreiben und Blog-Beiträge zu verfassen. Ich könnte ja einfach einen Server mit einen HTTP-Dienst und einer Datenbank aufsetzen und hier meine selbst geschrieben Blog-Anwendung deployen. Beispielen gibt es im Internet genügend, auf die ich aufbauen könnte. Allerdings würde dies den Fokus zu stark auf die zugrunde liegende Technologie legen und wenigen Zeit für das Verfassen von Beiträgen lassen. Daher wollte ich eine Blog-Engine verwenden, bei der ich mich nicht um die Infrastruktur kümmern muss.

GitHub-Pages und Jekyll
===