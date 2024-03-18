# Aufgabe 5

1. Kubernetes Deployments bieten automatische Skalierung, Selbstheilung und die Möglichkeit, Updates ohne Downtime durchzuführen. Sie ermöglichen ein einfaches Management von Konfigurationen und eine bessere Fehlerbehebung durch Versionskontrolle und Rollbacks.
   
2. Ein Kubernetes Service dient als Schicht, die einen Zugangspunkt zu einer Gruppe von Pods bietet, welche eine bestimmte Anwendung oder einen bestimmten Dienst ausführen. Er ermöglicht Netzwerkzugriff auf eine Gruppe von Pods, selbst wenn diese ersetzt oder skaliert werden, indem er eine konstante IP-Adresse und einen Port bereitstellt.
   
3. Kubernetes kann über einen Ingress Controller (z.B. nginx) über einen NodePort-Service oder über einen LoadBalancer(-Service) erreicht werden.

# Zusatzaufgabe

Ein Kubernetes Job ist eine Konfiguration, die einen oder mehrere Pods startet, um eine bestimmte Aufgabe auszuführen und dann zu terminieren. Im Gegensatz zu einem herkömmlichen Pod, ist ein Job für Aufgaben gedacht, die bis zu ihrem Abschluss laufen und dann stoppen.
