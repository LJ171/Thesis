# Initial Discussion with Christian 19.01.22

## Possible Topics
1. Hyperparameter Optimization (möglich langweilig, schlecht dokumentiert), wie viel besser als standard, relationsspezifisch setzen 
	Forschungsfrage: Wenn man das Validationset voll ausnutzt, wie gut wird ANYBURL?
	Weiter gehende Frage: regel für optimale Hyperparameter
	Sein voller Code -> analysieren 
	Thema 3 macht hier Bauchschmerzen.

2. (more complex) KGE wenn man die zweimal laufen lässt, sind zahlen sehr ähnlich. Einzelne rankings varieren tatsächlich stark. Varianz recht hoch.
	rule-based teilen diese schwäche nicht. 
	Forschungsthema: Was können regelbasierte Systeme gut und was können embeddingsbasierte Systeme gut -> Mittelwertranking aus mehreren Runs. 
	Identifizier die 100 Fälle indenen KGEs besser sind und die 100 Fälle indenen Rule-based besser sind.
	Gibt es vielleicht Fälle wo KGE das gar nicht hinbekommt, aus zufall bereinigt. Ist das Model spezifisch, oder haben das andere auch? 
	Testset erstellen, welches einfach logisch ist, aber KGEs schwer fällt. -> Synthetischer Datensatz

3. Schwachpunkt vom Rule-based wie werden Regeln ausgewertet, wenn mehrere Regeln feuern, wird maximum genommen. Alternative annahme, Regeln sind unabhängig -> vielleicht Kombinationen von Regeln besser als eine.
	Wie aggregiert man? (effizent bleiben) Es geht nicht um das lernen, sondern anwenden. 
	nur die max aggregierung in python wäre schon ne Leistung. 
	Saphran und ANYBURL
	https://arxiv.org/pdf/2109.08002
	
	Techniken: Noisy Or; Mittelwert; Aggregierung relationsspezifisch -> vielleicht dann Hyperparameter Optimization
	
### Alternative Advisors
Patrick Betz: Baupläne einscannen, Typen Klassifizierung
Bernhard Schäfer: handgeschriebene BPM strukturierte Übertragung

## Next Steps
Proposal wäre der nächste Schritt 
	wie ne Vereinbarung (Vertrag auf beiden Seiten)
	
	20. Februar Ziel fürs Proposal
	Selbstmanagement!
	
	
## Additional Material
Paper Regelerklärung 
https://arxiv.org/pdf/2004.04412.pdf

Source Code: vielleicht auch mal laufen lassen 
https://web.informatik.uni-mannheim.de/AnyBURL/