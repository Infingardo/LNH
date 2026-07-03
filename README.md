# LNH — Algoritmo diagnostico linfomi

App interattiva a pagina singola (HTML/JS, nessuna dipendenza) per il ragionamento diagnostico nei linfomi, allineata a **WHO-HAEM5** e **ICC 2022**. Copre linfomi non-Hodgkin a cellule **B**, linfomi **T/NK** e linfoma di **Hodgkin classico**.

**App online:** https://infingardo.github.io/LNHB/

## Contenuti
- **Gate di linea** iniziale (CD3/CD20) che smista verso il percorso B, T/NK o Hodgkin.
- **Wizard guidato**: percorso step-by-step (topografia → morfologia → IHC) che restringe il differenziale.
- **Panel IHC**: scorer fenotipico con vincoli topografici.
- **Vista Flowchart** stampabile + signature table immunofenotipica.
- **Referto** plain-text generato dalle risposte reali, nomenclatura WHO-HAEM5 (5ª ed., 2024).

## Entità coperte
- **B non-Hodgkin**: FL, FLBCL, PTFL, LBCL-IRF4, MCL (classico, blastoide, pleomorfo), NLPBL, MZL, CLL/SLL, DLBCL (GCB / non-GCB), HGBL (DH, MYC/BCL6, NOS), Burkitt, PMBL, THRLBCL, HCL, LPL.
- **T/NK**: AITL (TFH), PTCL-NOS, ALCL ALK+, ALCL ALK−, ENKTL (NK/T extranodale), Micosi fungoide.
- **Hodgkin**: linfoma di Hodgkin classico (CHL).

## Uso
Tutto in `index.html`. Apri il file nel browser o usa l'URL GitHub Pages.

## Avvertenza
Strumento di supporto decisionale. **Non** sostituisce il giudizio diagnostico integrato (morfologia + clinica + accertamenti).
