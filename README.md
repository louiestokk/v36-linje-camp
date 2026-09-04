# Ändringsutmaning · räkna raderna


# Trestegsmetod (Flex vs Grid)
1. Peka på tavlan: selektorn där du satte display: grid (.tabla) — varför behövs rader och kolumner?
## svar:
rad 28 HTML filen  <div class="tabla"> grid container
Med Grid kan lagga till fler avgangar .avgang och stylingen skoter sig sjalv med grid. Samt att vi kan styra hur manga columner och rader vi vill ha. Detta behover vi for vi skall gora en  avgångstavla med tider och spår.

3 stegs metoden
# skall vi ha en dimension i taget eller 2 dimensioner  som vi har i grid dar vi styr rader och columner. 
## Flexbox anvander vi for innehallet / kort etc sa man kan kombinera grid och flexbox 
### Grid Placering av element pa exakt plats , flexbox nar man vill justera element i förhållande till varandra 


2. Peka på pärlbandet: selektorn med display: flex (.kort-rad) — varför räcker en riktning?
## svar
pa rad 19 i ul i nav for att vi vill ha navigations lankarna pa en och samma rad.

3. Peka på resultatet: beskriv vad som händer om du byter verktyg (Flex på tabla = en rad som kläms; Grid på kort = onödigt tungt för ett band).
## svar
Om vi skulle anvanda flex box med direction row och ha flera avgangar skulle vi fa en overflow x och man skulle kunnan avanda overflowx scroll for att styra antalal rader vilket blir en enda rad. Men med flexwrap skapar den fler columner dock kan vi inte styra antal rader och columner och medfor en del extra css kod.  

# Jag kan förklara varje rad jag har pushat.

# Varför du valde två eller tre kolumner för Linje 47.
grid item har sa lite innehall sa jag valde 4 columner. 