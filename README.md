# Spam-Filter mit Naive Bayes und Python
Dieses Projekt implementiert einen einfachen Spam-Filter unter Verwendung des Multinomial Naive Bayes Modells. Der Code verwendet die scikit-learn-Bibliothek und verarbeitet einen Datensatz, der E-Mails als Spam oder Nicht-Spam klassifiziert.

Funktionsweise des Programms
- Datenvorbereitung:

Die Daten werden aus einer CSV-Datei eingelesen und in zwei Klassen aufgeteilt: Spam (1) und Nicht-Spam (0).
- Vektorisierung:

Texte werden mithilfe von CountVectorizer in Wortvektoren umgewandelt, um das Modell zu trainieren.
- Modelltraining:

Das Multinomial Naive Bayes-Modell wird auf den vorbereiteten Textdaten trainiert.
- Metriken:

Die Vorhersagegenauigkeit wird anhand von Metriken wie Accuracy, Precision, Recall und dem F1-Score bewertet.
- Konfusionsmatrix:

Eine Konfusionsmatrix wird erstellt, um die Klassifikationsgenauigkeit grafisch darzustellen.
- Kreuzvalidierung:

Eine Kreuzvalidierung wird durchgeführt, um die Leistung des Modells auf verschiedenen Trainings- und Test-Splits zu bewerten.
- Neue E-Mail testen:

Eine neue, benutzerdefinierte E-Mail kann eingegeben werden, um zu überprüfen, ob sie als Spam oder Nicht-Spam klassifiziert wird.
