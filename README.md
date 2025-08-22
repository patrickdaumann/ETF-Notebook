# ETF-Notebook

## Nutzung & Annahmen

**Wie bedienen?**  
1. *Investment (€)*: Monatliche Sparrate in ETFs.  
2. *Dynamik (%)*: Jährliche Erhöhung der Sparrate (z. B. Gehaltsanpassung).  
3. *Inflation (%)* & *Rendite p.a. (%)*: Langfristige Annahmen - Durschnittswerte.  
4. *Inflation im Plot berücksichtigen*: Zeigt das Vermögen optional in **heutiger Kaufkraft**.  

**Wesentliche Modellannahmen (bewusst vereinfacht):**  
- Monatliche Verzinsung aus Jahresrendite; Sparrate steigt **jährlich**.  
- Entnahmen sind **inflationsangepasst** (heutige Kaufkraft bleibt konstant).  
- Steuern: Proportionaler Gewinnanteil bei Verkäufen, pauschal {steuersatz_effektiv*100:.1f} % auf realisierte Gewinne.  
- Reihenfolge Entnahme: **Erst Rendite, dann Entnahme + Steuer** (neutral bis leicht optimistisch).

**Warum diese Standardwerte?**  
- *Rente mit*: entspricht der in Deutschland üblichen Regelaltersgrenze.  
- *Inflation*: nahe dem EZB-Ziel (~2 %).  
- *Rendite p.a.*: gängige Langfrist-Annahme für globale Aktien (nominal).  
- *Lebenserwartung*: liegt **über** dem heutigen Schnitt (Planungspuffer gegen Langlebigkeitsrisiko).  
- *Netto/Monat*: konservative Richtgröße für eine Einzelperson (Netto variiert stark mit Steuerklasse/Region).  

**Hinweis:** Realistische Netto-Einkommen leiten sich aus Brutto (z. B. ~4.5–4.7 T€ mtl. Durchschnitt Vollzeit) minus Abzügen ab; 2500€ ist daher als *konservativer* Startwert gedacht.


## Disclaimer
Dieses Tool ist ein **vereinfachtes, didaktisches Modell** zur Veranschaulichung des langfristigen Investierens in ETFs.  
Es ersetzt **keine Finanz- oder Steuerberatung**. Ergebnisse sind **Szenarien, keine Prognosen**.

### Annahmen & Vereinfachungen
- **Rendite:** konstante, durchschnittliche Jahresrendite (Standardwert 6,5 % p.a.).  
  → Gängige Langfrist-Annahme für global diversifizierte Aktien-ETFs (nominal, vor Kosten).  
- **Inflation:** konstante Inflationsrate (Standardwert 2 % p.a.).  
  → Entspricht langfristigem EZB-Ziel.  
- **Nettoeinkommen:** Standardwert 2 500 € monatlich.  
  → In etwa der Durchschnitt jüngerer Berufstätiger mit überdurchschnittlicher Qualifikation.  
- **Sparrate:** monatliche Investments, mit optionaler jährlicher Dynamik (z. B. Gehaltssteigerungen).  
- **Steuern:** pauschale Besteuerung realisierter Gewinne mit 18 %.  
  → Vereinfachung: Keine Teilfreistellung, kein Sparer-Pauschbetrag, keine Kirchensteuer.  
- **Kosten:** Fondsgebühren (TER), Transaktionskosten und steuerliche Freibeträge werden nicht berücksichtigt.  
- **Cashflow-Logik:** „erst Rendite, dann Entnahme“ (leicht optimistisch).  
- **Entnahmephase:** Entnahmen steigen jährlich mit der Inflation, um die Kaufkraft zu erhalten.  
- **Vererbung:** als „Vererbung“ wird der Depotwert zum Erreichen der eingestellten Lebenserwartung dargestellt.

### Einschränkungen
- **Volatilität & Risiko** werden nicht berücksichtigt. Tatsächliche Marktverläufe schwanken stark; Renditen treten nicht konstant ein.  
- **Andere Einkünfte** (gesetzliche Rente, Betriebsrenten, Immobilien etc.) sind nicht einbezogen.  
- **Steuerrecht** ist komplexer als hier abgebildet und kann sich ändern.  

### Zweck
Das Tool soll:
- den **Zinseszinseffekt** sichtbar machen,  
- die Wirkung von **regelmäßigem Investieren über Jahrzehnte** illustrieren,  
- und durch **interaktive Anpassung** von Parametern motivieren, sich mit Altersvorsorge auseinanderzusetzen.

Es soll **aufklären und sensibilisieren**, nicht exakte Finanzplanung ersetzen.