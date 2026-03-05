# Praca na zajęciach
- 4 zadania, tylko 3 obowiązkowe
- Korzystamy z oprogramowania **Multisim 14.3 Education**
  - Kod licencyjny: D11L1095576 (jest też na Panel AGH)
- Na zajęciach będziemy wykorzystywać sygnały TTL (5V)

# Elektronika
- Pozostałość po nieistniejącym przedmiocie, będzie chyba tylko przez pierwszy wykład
- Później będzie faktyczna technika cyfrowa (tranzystory and stuff)
## Napięcie, moc, energia
- Oznaczenie źródla napięcia w obwodzie: <br/>
 ![img_1.png](img_1.png)
- Oznaczenie rezystora:<br/>
 ![img_2.png](img_2.png) <br/>
jest to standard amerykański, my będziemy używać właśnie tego i taki mamy wybrać w oprogramowaniu, o którym mowa jest wyżej
- Prawo Ohma: <br/>
 ![img_3.png](img_3.png)<br/>
Wynika z niego między innymi, że rezystencja nie może być równa 0, nie należy też zwierać obwodu, ponieważ grozi to pożarem
- Prawo Kirhoffa
  - Suma napięć w obwodzie = 0. Napięcie o "zwrocie" przeciwnym do napięcia wytwarzanego przez baterię powstaje na rezystorach
  - Suma prądów wychodzących z węzła jest równa prądowi wpływającymu do węzła
![img_4.png](img_4.png)

- Wzory na moc <br/>
![img_5.png](img_5.png) <br/>
![img_6.png](img_6.png)
<br/><br/>
### Alternatywna forma przedstawienia układów (nie jako obwód zamknięty): <br/>
![img_7.png](img_7.png)

### Rodzaje prądu
- Prąd stały
- Prąd zmienny<br/><br/>
  - Prąd zmienny znajdziemy w sygnałach zegarowych, czyli w sygnałach wytwarzanych przez układy cyfrowe <br/><br/>
   ![img_8.png](img_8.png)<br/>
  - W energetyce prąd zmienia się sinusoidalnie <br/><br/>
  ![img_9.png](img_9.png)

### Rezystory
- Oznaczenie jest omówione wyżej
- Znaczenie kolorów na rezystorze: <br/><br/>
![img_10.png](img_10.png)<br/><br/>

- Łączenie rezystorów
  - Szeregowe (po sobie), daje sumę rezystencji
  - Równoległe (po rozgałęzieniu), daje opór wyrażony wzorem: <br/>
  ![img_11.png](img_11.png)
<br/><br/>
  
- Potencjometr (rezystor zmienny)<br/>
![img_12.png](img_12.png)<br/><br/>

- Fotorezystor <br/>
![img_13.png](img_13.png)<br/><br/>

- Termistor (rezystor termiczny)
  - NTC — rezystencja maleje wraz ze wzrostem temperatury
  - PTC — rezystencja rośnie wraz z temperaturą
  - CTR - Rezystencja nagle maleje przy bardzo konkretnej temperaturze (mogą być używane jako element bezpieczeństwa)

![img_14.png](img_14.png)

**APPARENTLY TEGO WSZYSTKIEGO NIE TRZEBA WIEDZIEĆ XD**

- Kondensator
  - Bateria, którą można bardzo szybko naładować i rozładować
  - Używany do stabilizacji napięcia w układach <br/>
  ![img_16.png](img_16.png)<br/><br/>
  - Można spotkać kondensator o zmiennej pojemności <br/>
  ![img_17.png](img_17.png)<br/><br/>

- Diody — układ, który przewodzi prąd w tylko jednym kierunku <br/>
![img_19.png](img_19.png)


- Tranzystory
  - Układ pozwalający na sterowanie obwodami za pomocą innych obwodów
![img_20.png](img_20.png)
## Podstawy techniki cyfrowej

### Standard TTL
- Obowiązują konkretne poziomy napięcia dla różnych zastosowań

![img_21.png](img_21.png)
- Ucc = napięcie zasilania
- gnd = ground
- o = output
- i = input
- H = high
- L = low

Low oznacza logiczne 0, a high oznacza logiczne 1

Trzeba uważać na to, że tolerancje napięcia wsą inne na wejściu na wyjściu

## Zapis logiczny obowiązujący na zajęciach

![img_22.png](img_22.png)
















