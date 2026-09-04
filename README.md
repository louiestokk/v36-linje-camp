# Ändringsutmaning · räkna raderna


# Trestegsmetod (Flex vs Grid)
1. Peka på tavlan: selektorn där du satte display: grid (.tabla) — varför behövs rader och kolumner?
## svar:
rad 28 HTML filen  <div class="tabla"> grid container
Med Grid kan lagga till fler avgangar .avgang och stylingen skoter sig sjalv med grid. Samt att vi kan styra hur manga columner och rader vi vill ha.

2. Peka på pärlbandet: selektorn med display: flex (.kort-rad) — varför räcker en riktning?
## svar
pa rad 19 i ul i nav for att vi vill ha navigations lankarna pa en och samma red

3. Peka på resultatet: beskriv vad som händer om du byter verktyg (Flex på tabla = en rad som kläms; Grid på kort = onödigt tungt för ett band).
## svar
Om vi skulle anvanda flex box med direction row och ha flera avgangar skulle vi fa en overflow x och man skulle kunnan avanda overflowx scroll for att styra antalal rader vilket blir en enda rad. Men med flexwrap skapar den fler columner dock kan vi inte styra antal rader och columner och medfor en del extra css kod.  

# Jag kan förklara varje rad jag har pushat.