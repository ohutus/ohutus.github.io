---
layout: post
title: "Huvitavad faktid"
---

<h1 id="fakt">Pikendusjuhtmed ei ole mõeldud püsivaks kasutamiseks, Paljud kasutavad neid aastaid järjest, kuid need on mõeldud ajutiseks lahenduseks. Ülekoormatud või üksteise otsa ühendatud pikendusjuhtmed on sage tulekahju põhjus</h1>

<button id="teinefakt" style="padding: 10px; color: black; background-color: lightgreen; font-size: 25px; border-radius: 10px; border-style: none;">Veel</button>

<script>const faktid = ["Enamik raskeid õnnetusi juhtub tuttaval teel", "Turvavöö vähendab surma riski eest kokkupõrkes ligi 45–50%", "Turvapadi avaneb umbes 20–40 millisekundiga.", "Ilma turvavööta võib turvapadi hoopis vigastusi suurendada.", "Pimedas helkurita jalakäiat on lähituledega märgatav umbes 30 meetri pealt. Helkuriga võib nähtavus ulatuda 150 meetrini või rohkem", "Telefon roolis pikendab reaktsiooniaega rohkem kui kerge joove", "Kiiruse väike tõus = suur riskitõus. Kui kiirus kasvab 50 km/h pealt 60 km/h-ni, suureneb jalakäija surma risk mitmekordselt, kui kokkupõrge toimub.",
  "Pikendusjuhtmed ei ole mõeldud püsivaks kasutamiseks, Paljud kasutavad neid aastaid järjest, kuid need on mõeldud ajutiseks lahenduseks. Ülekoormatud või üksteise otsa ühendatud pikendusjuhtmed on sage tulekahju põhjus.",
"Väikesed patareid on suuremad ohud kui terariistad, Nn nööppatareid (nt kellades ja mänguasjades) võivad allaneelamisel põhjustada eluohtlikke sisemisi põletusi juba mõne tunni jooksul.",
"Tulekahjus ei tapa enamasti tuli, vaid suits, Enamik tulekahjuohvreid sureb suitsu sissehingamise tõttu, mitte põletuste tõttu. Suits võib muuta inimese teadvusetuks vähem kui 2 minutiga.",
"Desinfitseerimisvahendid on tuleohtlikud, Alkoholi sisaldavad kätegeelid võivad süttida, kui need pole täielikult kuivanud ja läheduses on lahtine leek (nt gaasipliit või küünal).",
"Õlipõlengut ei tohi kunagi veega kustutada, Vesi põhjustab rasvapõlengu plahvatusliku leviku. Õige viis on katta leek kaanega või kasutada tulekustutit.",
  ];
  document.querySelector("#teinefakt").addEventListener("click", () => {document.querySelector("#fakt").innerHTML = faktid[Math.floor(Math.random() * faktid.length)]})
</script>
