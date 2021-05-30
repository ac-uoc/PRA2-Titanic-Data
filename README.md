# PRA2-Titanic-Data
Data Analisis based on Wikipedia Titanic Data - 
Anàlisi de dades del viatge inaugural del Titanic

Ens hem basat en dos URL

https://en.wikipedia.org/wiki/Passengers_of_the_Titanic

https://en.wikipedia.org/wiki/Crew_of_the_Titanic

El fitxer resultant d'ajuntar per nosaltres 11 taules, all_Titanic.xlsx, ha sigut revisat amb Python en CleaningTitanic.ipynb, que adjuntem.
Qualsevol imprecisió resultant pot ser deguda a error nostre, malgrat que hem procurat ser totalment respectuosos amb l'original.

El Titanic volia ser una demostració extrema de la tècnica i del luxe, que per això té tant de significat l'enfonsament del vaixell en el seu primer viatge amb passatgers. Portava tanta gent de l'alta societat, que el viatge era un fet social. Tant és així que alguns com Marconi van treure el bitllet d'aquest primer viatge encara que finalment la seva agenda no els va permetre abordar al Titanic.

Com al recent cas del Costa Concordia, pot ser que confiats per la seua superioritat tècnica, els oficials no van estar atents a les incidències.
Per exemple,

  •	El Titanic quasi va col·lidir amb el transatlàntic City of New York a l'eixida de Southampton.
  
  •	Van rebre 6 avisos d’icebergs, que evidentment no es tingueren en compte: en el moment de la col·lisió, anaven a 22,5 nusos, sent el màxim del Titanic 23. Van veure l’iceberg i en 30 segons van col·lidir.
  
Hi havia molt de luxe, però no tant de disseny:

  •	Per què es van unir les planxes d'acer amb reblons? Els reblons probablement van cedir. L’iceberg no va trencar probablement les planxes, les va separar.
  
  •	És clar que no estava previst que el pes de sis compartiments inundats era suficient per a trencar-se en dos. Quan el pes de la proa va ser excessiu es va partir pel mig i enfonsar molt ràpidament.
  
Per altra banda, es pot pensar si l'extrema absència de mesures de seguretat va ser per criteris de la White Star Line (encara que dins de la reglamentació de 1912) : perquè portava a soles 20 bots, quan el disseny incloïa 64? 20 bots, dels quals 4 eren inferiors, no podien en cap cas amb 2208 persones que estaven a bord, i molt menys, amb la cabuda màxima del Titanic de 3547 persones.

Els bots, malgrat ser insuficients, no es van omplir: el primer d'ells portava 28 persones amb una cabuda de 65. Tardaren 1 hora a omplir el primer bot. Malgrat tot, del nostre anàlisi, quasi el 80% dels passatgers de primera classe, amb servei personal a bord també a 1a classe, es va salvar.

El dissenyador anava a bord, i havia de saber que amb sis compartiments inundats, el Titanic no tenia salvació: el màxim era 4. Actuarem com si, malgrat tot, no anara a afonar-se. Aprofitaran les dues hores, 40 minuts que va tardar a fer-ho?

Molts dels passatgers de les cobertes inferiors es quedaren atrapats amb portes estanques tancades per a contenir la inundació, la qual cosa va ser inútil perquè sis compartiments es van inundar i anava a afonar-se en qualsevol cas, i perquè es va trencar pel mig, i l'enfonsament va ser ràpid.

La idea és analitzar en les dades els fets del Titanic, els 'Titanic facts'.
