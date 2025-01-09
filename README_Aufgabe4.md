# Github Action Cache Node.js Modules

Was macht die Action: Die Action `actions/cache` speichert die Node.js-Abhängigkeiten (z.B.`node_modules`) im Cache und stellt sie bei weiteren Builds wieder her. So werden Installationszeiten kürzer und die Builds gehen schneller.

Praktischer Nutzen: Die Action optimiert die CI/CD-Pipeline, indem sie unnötige Wiederholungen bei der Installation von Abhängigkeiten vermeidet. Dies spart Zeit und Ressourcen, vorallem bei grossen Projekten mit vielen Abhängigkeiten.
