> [!attention]
> 10. Týden v semestru půlsemestrální zkouška?

## Nabíjení kondenzátorů
$$ i = \frac{u_R}{R} $$
$$ u_{R} + u_{C} = U$$
$$u_{C}' = \frac{i}{C}, u_{C}(0)=u_{cR}$$
$$u_{C}'=\frac{u_{R}}{R*C} $$
> [!missing]
> The next line is known to contain missing material

$$ u_{c}'= $$
Nehomogenní:
$$u_{c}'+ \frac{u_{c}}{R-C} = \frac{U}{R.C}; u_{c}(0)=u_{cp}$$
-> Charakteristická rovnice $$u_{c}'= \lambda, u_{c} = 1 $$
$$ \lambda + \frac{1}{RC} = 0 \to \lambda = - \frac{1}{RC} $$
>[!missing]
-> Očekáváné řešení
$$u_{c}(t)=K(t).e^{\lambda*t}=$$

-> Dosadíme
$$K'(t)e^{-\frac{t}{RC}}-\frac{K(t)}{RC}*e^{-\frac{t}{RC}}+\frac{K(t)*e^{-\frac{t}{RC}}}{RC} = \frac{U}{RC}$$
$$K'_{t}e^{-\frac{t}{RC}} = \frac{U}{RC} /*e^{\frac{t}{RC}}$$
$$K'(t) = \frac{U}{RC}*e^{\frac{t}{RC}} / derivace$$
$$ K(t) = \frac{\frac{U}{RC}}{\frac{1}{RC}}*e^{\frac{t}{RC}}+k = U*e^{\frac{t}{RC}}+k$$
$$u_{c}(t)=(U*e^{\frac{t}{RC}}+k)*e^{-\frac{t}{RC}}$$
$$u_{c}(t) = U+k*e^{-\frac{t}{RC}} $$
Dosadíme
$$u_{cp}=U+k+e^0 \to k=u_{cp} -U $$

Řešení:
## $$u_{c}(t)=U+(u_{cp}-U)*e^{-\frac{t}{RC}}$$
ZKOUŠKA

-> dosadíme u_c a u_c' do (**) 

$$u_{c}'=-\frac{1}{RC}*(u_{cp}-U)*e^{-\frac{t}{RC}}$$
### $$-\frac{1}{RC}*(u_{cp}-U)*e^{-\frac{t}{RC}}+\frac{U}{RC}+\frac{u_{cp}-U}{RC}*e^{-\frac{t}{RC}}=\frac{U}{RC}$$

> [!info]
> Tady jsem tak trochu nachvíli koukl jinam než na tabuli a když jsem se za pár minut podíval zpátky tak borec popsal dvě A4, TLDR: hodně toho tu chybí

