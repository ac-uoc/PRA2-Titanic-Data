# PRA2-Titanic-Data


- Anàlisi de dades del viatge inaugural del Titanic



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

Ens hem basat en dos URL

https://en.wikipedia.org/wiki/Passengers_of_the_Titanic

https://en.wikipedia.org/wiki/Crew_of_the_Titanic

El fitxer resultant d'ajuntar per nosaltres 11 taules, all_Titanic.xlsx, ha sigut revisat amb Python en CleaningTitanic.ipynb, que adjuntem.
Qualsevol imprecisió resultant pot ser deguda a error nostre, malgrat que hem procurat ser totalment respectuosos amb l'original.


- Análisis de los datos del viaje inaugural del Titanic



El Titanic quería ser una demostración extrema de la técnica y del lujo, que por eso tiene tanto de significado el hundimiento del barco en su primer viaje con pasajeros. Llevaba tanta gente de la alta sociedad, que el viaje era un hecho social. Tanto es así que algunos como Marconi sacaron el billete de este primer viaje aunque finalmente su agenda no los permitió abordar al Titanic.

Como al reciente caso del Costa Concordia, puede ser que confiados por su superioridad técnica, los oficiales no estuvieron atentos a las incidencias. Por ejemplo,

• El Titanic casi colisionó con el transatlántico City of New York a la salida de Southampton.

• Recibieron 6 avisos de icebergs, que evidentemente no se tuvieron en cuenta: en el momento de la colisión, iban a 22,5 nudos, siente el máximo del Titanic 23. Vieron el iceberg y en 30 segundos colisionaron.

Se había cuidado el lujo, pero no tanto de diseño:

• ¿Por qué se usaron remaches para unir las planchas de acero? Los remaches probablemente cedieron. El iceberg separó las planchas de acero, probablemente no las rompió.

• Parece evidente que no estaba previsto que el peso de seis compartimentos inundados fuera suficiente para romper el Titanic en dos. Cuando el peso de la proa fue excesivo, se partió por el medio y se hundió muy rápidamente.

Se puede pensar, por otro lado, si la extrema ausencia de medidas de seguridad, aunque dentro de la reglamentación de 1912, fue por criterios de la White Star Line. ¿Por qué llevaba solo 20 botes, cuando el diseño incluía 64? Estos 20 botes, de los cuales 4 eran inferiores, no podían en ningún caso con 2208 personas que estaban a bordo, y mucho menos, con la cabida máxima del Titanic de 3547 personas.

Los botes, a pesar de ser insuficientes, no se llenaron: el primero de ellos llevaba 28 personas con una cabida de 65. Tardaron 1 hora a llenar el primer bote. A pesar de todo, casi el 80% de los pasajeros de primera clase, con servicio personal a bordo también a 1.ª clase, se salvó, netamente por encima de la media.

El diseñador iba a bordo, y tenía que saber que con seis compartimentos inundados, el Titanic no tenía salvación: el máximo era 4. Actuaron como si, a pesar de todo, no fuera a hundirse. ¿Aprovecharon las dos horas, 40 minutos que tardó a hacerlo?

Muchos de los pasajeros de las cubiertas inferiores se quedaron atrapados con puertas estancas cerradas para contener la inundación, lo cual fue inútil porque seis compartimentos se inundaron e iba a hundirse en cualquier caso, y porque se rompió por el medio, y el hundimiento fue instantáneo.

La idea es analizar en los datos los hechos del Titanic, los 'Titanic facts'.

Nos hemos basado en dos URL

https://en.wikipedia.org/wiki/passengers_of_the_titanic

https://en.wikipedia.org/wiki/crew_of_the_titanic

El fichero resultante de juntar por nosotros 11 tablas de Excel extraídas de la Wikipedia, all_Titanic.xlsx, ha sido revisado en CleaningTitanic.ipynb, que adjuntamos. Cualquier imprecisión resultante puede ser debida a error nuestro, a pesar de que hemos procurado ser totalmente respetuosos con el original.



- Data Analisis based on Wikipedia Titanic Data 



The sinking of the ship on its maiden voyage with passengers is so significant, because the Titanic intended to be an extreme demonstration of technique and luxury. The Titanic carried so many people from high society in the maiden voyage that the trip was a social event. Some, as Marconi, took out a ticket for this first voyage, although in the end their agenda did not allow them to board the Titanic.

As in the recent case of the Costa Concordia, it could be that confident of their technical superiority, the officers were not attentive to incidents. For example,

- Titanic almost collided with the Liner City of New York on departure from Southampton.

- They received six iceberg warnings, which evidently were not taken into account: at the time of the collision, they were cruising at 22.5 knots, while Titanic's maximum speed was 23 knots.

They had taken much care of luxury, but not so much of design:

- Why were rivets used to join the steel plates? The rivets probably gave way. The iceberg separated the steel plates, probably not broke them.

- It seems clear that the weight of six flooded compartments was not considered to be enough to break Titanic in two. When the weight of the bow was excessive, Titanic broke by the middle and sank very quickly.

On the other hand, one may wonder if the extreme lack of safety measures, although within the 1912 regulations, was due to the criteria of the White Star Line. Why the Titanic did carry only 20 boats, when the design included 64? These 20 boats, of which 4 were inferior, could not in any case hold 2208 people on board, not the Titanic's maximum capacity of 3547 people.

The boats, although insufficient, were not full crowded: 28 people carried the first one with a nominal capacity of 65. It took 1 hour to fill the first boat. Nevertheless, almost 80% of the first class passengers, with personal service on board also in 1st class, were saved, well above average.

The designer was on board, and he had to know that with six compartments flooded, the Titanic had no salvation: the maximum was four. They acted as if, in spite of evidence, it was not going to sink. Did they take advantage of the two hours, 40 minutes it took to do so?

Many of the passengers on the lower decks were trapped with watertight gates closed to contain the flooding. This fact was useless because six compartments were flooded and it was going to sink in any case, and because the Titanic broke down the midship, and the sinking was instantaneous.

The goal is to analyze data and going further on the 'Titanic facts'.

We have relied on two URLs

https://en.wikipedia.org/wiki/passengers_of_the_titanic

https://en.wikipedia.org/wiki/crew_of_the_titanic

The file resulting from joining 11 Excel tables extracted from Wikipedia, the all_Titanic.xlsx, has been revised by CleaningTitanic.ipynb, which we attach. Any resulting inaccuracies may be due to error on our part, although we have tried to be extremly respectful to the original data.
