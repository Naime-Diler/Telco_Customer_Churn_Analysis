# **Telco Customer Churn Analysis** 

## **Geschäftsproblem** 
Ein Maschinenlernmodell wird benötigt, um Kunden vorherzusagen, die das Unternehmen verlassen werden. Vor der Entwicklung des Modells müssen die erforderlichen Schritte für die Datenanalyse 
und das Feature-Engineering durchgeführt werden.
<br>
## **Datensatzgeschichte**
Die Daten zum Kundenverlust des Telekommunikationsunternehmens im dritten Quartal enthalten Informationen über 7043 Kunden in Kalifornien, die von einem fiktiven Telekommunikationsunternehmen 
Telefon- und Internetdienste erhalten haben. Die Daten zeigen, welche Kunden das Unternehmen verlassen haben, welche geblieben sind und welche sich für den Service angemeldet haben.
<br>
## **Variablen**
<ul>
<li><strong>CustomerId:</strong> Kunden-ID</li>
<li><strong>Gender:</strong> Geschlecht</li>
<li><strong>SeniorCitizen:</strong> Seniorität des Kunden (1 für ja, 0 für nein)</li>
<li><strong>Partner:</strong> Hat der Kunde einen Partner? (Ja, Nein) - Ist er verheiratet?</li>
<li><strong>Dependents:</strong> Gibt es Personen, für die der Kunde verantwortlich ist? (Ja, Nein) (Kinder, Mutter, Vater, Großmutter)</li>
<li><strong>tenure:</strong> Die Anzahl der Monate, die der Kunde im Unternehmen verbracht hat</li>
<li><strong>PhoneService:</strong> Verfügt der Kunde über Telefonanschluss? (Ja, Nein)</li>
<li><strong>MultipleLines:</strong> Hat der Kunde mehrere Telefonleitungen? (Ja, Nein, Kein Telefonanschluss)</li>
<li><strong>InternetService:</strong> Internetdienstanbieter des Kunden (DSL, Glasfaser oder kein Internetdienst)</li>
<li><strong>OnlineSecurity:</strong> Kunden-Online-Sicherheit (Ja, Nein, Kein Internetdienst)</li>
<li><strong>OnlineBackup:</strong> Status der Online-Backups des Kunden (Ja, Nein, Kein Internetdienst)</li>
<li><strong>DeviceProtection:</strong> Kunden-Geräteschutz (Ja, Nein, Kein Internetdienst)</li>
<li><strong>TechSupport:</strong> Technischer Support des Kunden (Ja, Nein, Kein Internetdienst)</li>
<li><strong>StreamingTV:</strong> Kundennutzung von Internetdiensten zur Übertragung von Fernsehprogrammen von einem Drittanbieter</li>
<li><strong>StreamingMovies:</strong> Kundennutzung von Internetdiensten zur Streaming von Filmen von einem Drittanbieter</li>
<li><strong>Contract:</strong> Vertragslaufzeit des Kunden (Monatlich, Jährlich, Zweijährlich)</li>
<li><strong>PaperlessBilling:</strong> Status der papierlosen Rechnung des Kunden (Ja, Nein)</li>
<li><strong>PaymentMethod:</strong> Zahlungsmethode des Kunden (Elektronischer Scheck, Postanweisung, automatische Banküberweisung, automatische Kreditkartenzahlung)</li>
<li><strong>MonthlyCharges:</strong> Monatliche Gebühren des Kunden</li>
<li><strong>TotalCharges:</strong> Gesamtbetrag, der dem Kunden in Rechnung gestellt wird</li>
<li><strong>Churn:</strong> Kundenabwanderung (Ja oder Nein) - Kunden, die im letzten Monat oder Quartal abgewandert sind</li>
</ul>
<br>
<ul>
<li>Jede Zeile repräsentiert einen einzigartigen Kunden.</li>
<li>Die Variablen umfassen Informationen zu Kundenservice, Konten und demografischen Daten.</li>
<li>Dienste, für die Kunden angemeldet sind - Telefon, Mehrfachleitungen, Internet, Online-Sicherheit, Online-Backup, Geräteschutz, technischer Support sowie Streaming von TV und Filmen.</li> 
<li>Kundenkontoinformationen - Dauer der Kundenbeziehung, Vertragsdetails, Zahlungsmethode, papierlose Abrechnung, monatliche und Gesamtkosten.</li> 
<li>Demografische Informationen über Kunden - Geschlecht, Altersgruppe, Partnerschaftsstatus und Verantwortung für andere Personen.</li>
</ul>

## **Ziel**
Entwicklung eines Maschinenlernmodells zur Vorhersage von Kundenabwanderung basierend auf den bereitgestellten Kundendaten.
<br>
## **Vorgehensweise**
<ul>
<li><strong>Datenüberprüfung:</strong> Überprüfung der Datenintegrität und Struktur.</li>
<li><strong>Explorative Datenanalyse:</strong> Analyse der Verteilung und Beziehung zwischen Variablen.</li>
<li><strong>Feature Engineering:</strong> Identifizierung und Behandlung von Ausreißern und fehlenden Werten. Extraktion neuer Merkmale aus vorhandenen Variablen.</li>
<li><strong>Encoding:</strong> Umwandlung kategorialer Variablen in numerische Formate.</li>
<li><strong>Modellierung und Bewertung:</strong> Erstellung eines Basismodells, Implementierung von Feature-Engineering-Techniken und Bewertung der Modellleistung.</li>
</ul>

## **Ergebnisse**
<ul>
<li>Implementierung von Feature-Engineering-Techniken führte zu einer Verbesserung der Modellgenauigkeit (Accuracy), des Recall-Werts und des F1-Scores.</li>
<li>Die Genauigkeit stieg auf 0.79, der Recall auf 0.65 und der F1-Score auf 0.57.</li>
<li>Das Modell ist nun besser in der Lage, Kundenabwanderung vorherzusagen, mit einer AUC-ROC-Kennzahl von 0.74.</li>
</ul>
