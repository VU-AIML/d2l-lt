# Žymėjimai
:label:`chap_notation`

Visoje knygoje vartojame
toliau pateiktus žymėjimus.
Atkreipkite dėmesį, kad kai kurie šių simbolių yra bendrieji žymenys,
o kiti žymi konkrečius objektus.
Bendra taisyklė: žodžiai „bet koks“ aprašyme rodo,
kad simbolis yra bendrasis žymuo
ir kad panašiai užrašyti simboliai
gali žymėti kitus to paties tipo objektus.
Pavyzdžiui, „$x$: bet koks skaliaras“ reiškia,
kad mažosiomis raidėmis paprastai
žymimos skaliarinės reikšmės,
o „$\mathbb{Z}$: sveikųjų skaičių aibė“
visada žymi būtent šią aibę.



## Skaitiniai objektai

* $x$: bet koks skaliaras
* $\mathbf{x}$: bet koks vektorius
* $\mathbf{X}$: bet kokia matrica
* $\mathsf{X}$: bet koks tenzorius
* $\mathbf{I}$: vienetinė matrica (tam tikro duoto dydžio), t. y. kvadratinė matrica, kurios visi įstrižainės elementai lygūs $1$, o visi kiti – $0$
* $x_i$, $[\mathbf{x}]_i$: vektoriaus $\mathbf{x}$ $i$-asis elementas
* $x_{ij}$, $x_{i,j}$,$[\mathbf{X}]_{ij}$, $[\mathbf{X}]_{i,j}$: matricos $\mathbf{X}$ elementas $i$-ojoje eilutėje ir $j$-ajame stulpelyje.



## Aibių teorija


* $\mathcal{X}$: bet kokia aibė
* $\mathbb{Z}$: sveikųjų skaičių aibė
* $\mathbb{Z}^+$: natūraliųjų (teigiamųjų sveikųjų) skaičių aibė
* $\mathbb{R}$: realiųjų skaičių aibė
* $\mathbb{R}^n$: $n$-mačių realiųjų skaičių vektorių aibė
* $\mathbb{R}^{a\times b}$: realiųjų skaičių matricų, turinčių $a$ eilučių ir $b$ stulpelių, aibė
* $|\mathcal{X}|$: aibės $\mathcal{X}$ galia (elementų skaičius)
* $\mathcal{A}\cup\mathcal{B}$: aibių $\mathcal{A}$ ir $\mathcal{B}$ sąjunga
* $\mathcal{A}\cap\mathcal{B}$: aibių $\mathcal{A}$ ir $\mathcal{B}$ sankirta
* $\mathcal{A}\setminus\mathcal{B}$: aibių $\mathcal{A}$ ir $\mathcal{B}$ skirtumas, t. y. aibė, kurią sudaro tik tie aibės $\mathcal{A}$ elementai, kurie nepriklauso aibei $\mathcal{B}$



## Funkcijos ir operatoriai


* $f(\cdot)$: bet kokia funkcija
* $\log(\cdot)$: natūrinis logaritmas (pagrindas $e$)
* $\log_2(\cdot)$: logaritmas, kurio pagrindas $2$
* $\exp(\cdot)$: eksponentinė funkcija
* $\mathbf{1}(\cdot)$: indikatorinė funkcija; lygi $1$, jei loginis argumentas teisingas, ir $0$ priešingu atveju
* $\mathbf{1}_{\mathcal{X}}(z)$: priklausymo aibei indikatorinė funkcija; lygi $1$, jei elementas $z$ priklauso aibei $\mathcal{X}$, ir $0$ priešingu atveju
* $\mathbf{(\cdot)}^\top$: vektoriaus arba matricos transponavimas
* $\mathbf{X}^{-1}$: matricos $\mathbf{X}$ atvirkštinė matrica
* $\odot$: Adamaro (elementų po elementą) sandauga
* $[\cdot, \cdot]$: sujungimas
* $\|\cdot\|_p$: $\ell_p$ norma
* $\|\cdot\|$: $\ell_2$ norma
* $\langle \mathbf{x}, \mathbf{y} \rangle$: vektorių $\mathbf{x}$ ir $\mathbf{y}$ skaliarinė sandauga
* $\sum$: elementų rinkinio suma
* $\prod$: elementų rinkinio sandauga
* $\stackrel{\textrm{def}}{=}$: lygybė, apibrėžianti kairėje pusėje esantį simbolį



## Matematinė analizė

* $\frac{dy}{dx}$: $y$ išvestinė $x$ atžvilgiu
* $\frac{\partial y}{\partial x}$: $y$ dalinė išvestinė $x$ atžvilgiu
* $\nabla_{\mathbf{x}} y$: $y$ gradientas $\mathbf{x}$ atžvilgiu
* $\int_a^b f(x) \;dx$: funkcijos $f$ apibrėžtinis integralas nuo $a$ iki $b$ pagal $x$
* $\int f(x) \;dx$: funkcijos $f$ neapibrėžtinis integralas pagal $x$



## Tikimybių teorija ir informacijos teorija

* $X$: bet koks atsitiktinis dydis
* $P$: bet koks tikimybių skirstinys
* $X \sim P$: atsitiktinis dydis $X$ turi skirstinį $P$
* $P(X=x)$: tikimybė, kad atsitiktinis dydis $X$ įgyja reikšmę $x$
* $P(X \mid Y)$: $X$ sąlyginis tikimybių skirstinys, kai duotas $Y$
* $p(\cdot)$: skirstiniui $P$ priklausanti tikimybės tankio funkcija
* ${E}[X]$: atsitiktinio dydžio $X$ vidurkis (matematinė viltis)
* $X \perp Y$: atsitiktiniai dydžiai $X$ ir $Y$ yra nepriklausomi
* $X \perp Y \mid Z$: atsitiktiniai dydžiai $X$ ir $Y$ yra sąlygiškai nepriklausomi, kai duotas $Z$
* $\sigma_X$: atsitiktinio dydžio $X$ standartinis nuokrypis
* $\textrm{Var}(X)$: atsitiktinio dydžio $X$ dispersija, lygi $\sigma^2_X$
* $\textrm{Cov}(X, Y)$: atsitiktinių dydžių $X$ ir $Y$ kovariacija
* $\rho(X, Y)$: $X$ ir $Y$ Pirsono koreliacijos koeficientas, lygus $\frac{\textrm{Cov}(X, Y)}{\sigma_X \sigma_Y}$
* $H(X)$: atsitiktinio dydžio $X$ entropija
* $D_{\textrm{KL}}(P\|Q)$: Kulbako ir Leiblerio divergencija (arba santykinė entropija) iš skirstinio $Q$ į skirstinį $P$



[Diskusijos](https://discuss.d2l.ai/t/25)
