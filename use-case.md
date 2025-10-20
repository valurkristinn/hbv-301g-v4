# Fully Dressed Use Case

**ID:** UC-1  
**Heiti:** Bóka þjónustu hjá verkstæði
**Aðal aðili:** Bílaeigandi  
**Aukaaðilar:** Starfsmaður verkstæðis  

## Forsendur
- Notandi er auðkenndur
- Notandi hefur skráðan bíl í kerfinu
- Það eru til verkstæði nálægt notandanum sem bjóða upp á þjónustuna sem hann þarf

## Eftirskilyrði
- Notandi fær staðfestingu um bókunina í kerfinu
- Verkstæðið fær upplýsingar um bókunina í kerfinu

## Aðalflæði
1. Notandi opnar síðu til að bóka þjónustu fyrir bíl.
2. Notandi velur viðeigandi þjónustu.
3. Kerfið birtir lista af mögulegum verkstæðum.
4. Notandi síar listann eftir fjarlægð/einkunn/verði.
5. Notandi velur verkstæði og tíma fyrir bókun.
6. Kerfið birtir samantekt af upplýsingum fyrir bókunina.
7. Notandi staðfestir bókunina.
8. Kerfið býr til bókunina í kerfinu og sendir upplýsingar um hana til verkstæðis og notanda.
9. Kerfið býr til áminningu fyrir notanda sem verður send til hans degi fyrir bókun.


## Valflæði
- A1: 
    1. Notandi velur verkstæði og tíma fyrir bókun.
    2. Kerfið birtir skilaboð að verkstæðið er fullbókað á þessum tíma.
    3. Kerfið býður upp á að velja annan tíma eða finna annað verkstæði sem er laust á völdum tíma.
    4. Notandi velur annan tíma eða annað verkstæði og heldur áfram í venjulegu flæði.


## Undantekningar
- E1: 
    1. Notandi reynir að staðfesta bókun á þjónustu á verkstæði, en kerfið nær ekki sambandi við kerfið hjá verkstæðinu.
    2. Kerfið birtir skilaboð að bókun hjá verkstæðinu er tímabundið ekki hægt.
    3. Kerfið býr ekki til bókunina en geymir upplýsingar um bókunina í aðgangi hjá notenda svo hann getur seinna haldið áfram með bókunina.
    4. Notandi getur valið að velja annað verkstæði eða reynt seinna að bóka aftur.


## Tengsl (Traceability)
- Kröfur: BR-1 (Einkunnargjöf á þjónustum), UR-3 (Notandi getur bókað þjónustu á verkstæði í kerfinu), FR-1, FR-2, FR-3.
