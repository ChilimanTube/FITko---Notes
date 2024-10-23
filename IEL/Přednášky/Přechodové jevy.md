[[Přechodové jevy na RC, RL , RLC a vedení#^fb9a6c |Přechodový jev]]

## Vedení
- Typické parametry vedení:
	- **Charakteristická impedance** $Z [\Omega]$
		- $Z = \sqrt{ \frac{L_{m}}{C_{m}} }$
	- **Délka** (určuje útlum a zpoždění signálu)
	- $L_{m}, C_{m}, R_{m}, G_{m}$ na jednotku délky
- **Symetrické** (dvojlinka) / **Asymetrické** (koaxiální)
- Vodiče pro přenos signálu
- Vliv impedance zdroje signálu a zátěže
	- Zdroj signálu
		- $R_{G} = Z$ (impedančně způsobeno = bez odrazů)
		- $R_{G} \neq Z$ (odrazy na začátku vedení)
	- Zakončení
		- $R_{z} = \infty$ (naprázdno, odraz)
		- $R_{z} = Z$ (impedančně přizpůsobeno = bez odrazů)
		- $R_{z} = 0$ (nakrátko, odraz na konci)
	- Aplikace: zpoždění, generování impulsu, hledání místa přerušení, ...

### Nejjednodušší model vedení
> [!example]
> ![[Pasted image 20241009142309.png]]

- Parametr: délka vedení $l$
- Zpoždění je dané délkou vedení a rychlostí světla $c$
- Ideální přenos signálu:
$$u_{2}(t) = u_{1} \left( t - \frac{I}{c} \right)$$
### Model reálného vedení
- Přesnost aproximace závisí na počtu segmentů
- Řešení závisí na parametrech vedení, impedanci zdroje $R_{G}$ a impedanci zátěže $R_{L}$ 
- Aproximace vedení RLC segmenty ($G_{m}$ zanedbáme):
	![[Pasted image 20241009142707.png]]
- Vedení: N segmentů za sebou (pro $N=4$)
	![[Pasted image 20241009142730.png]]

