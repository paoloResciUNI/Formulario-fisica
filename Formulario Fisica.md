# Formulario di Matematica e Fisica (fino alla Dinamica)

## Matematica – Ripasso Essenziale

### Derivate utili

- $ (x^n)' = n x^{n-1} $
- $ (e^x)' = e^x $
- $ (\ln x)' = 1/x $
- $ (\sin x)' = \cos x $
- $ (\cos x)' = -\sin x $
- $ (k f(x))' = k f'(x) $
- Prodotto: $ (fg)' = f'g + fg' $
- Quoziente: $ (f/g)' = (f'g - fg')/g^2 $

### Integrali fondamentali

- $ \int x^n dx = x^{n+1}/(n+1) + C $, $ n \neq -1 $
- $ \int 1/x\ dx = \ln|x| + C $
- $ \int e^x dx = e^x + C $
- $ \int \sin x dx = -\cos x + C $
- $ \int \cos x dx = \sin x + C $

### Vettori

- Modulo: $ |\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2} $
- Prodotto scalare: $ \vec{a} \cdot \vec{b} = ab \cos \theta $
- Prodotto vettoriale: $ |\vec{a} \times \vec{b}| = ab \sin \theta $

### Trigonometria

	| in terms of       | $\sin \theta$         | $\csc \theta$         | $\cos \theta$         | $\sec \theta$         | $\tan \theta$         | $\cot \theta$         |
|-------------------|------------------------|------------------------|------------------------|------------------------|------------------------|------------------------|
| $\sin \theta =$  | $\sin \theta$         | $\frac{1}{\csc \theta}$ | $\pm\sqrt{1 - \cos^2 \theta}$ | $\pm\frac{\sqrt{\sec^2 \theta - 1}}{\sec \theta}$ | $\pm\frac{\tan \theta}{\sqrt{1 + \tan^2 \theta}}$ | $\pm\frac{1}{\sqrt{1 + \cot^2 \theta}}$ |
| $\csc \theta =$  | $\frac{1}{\sin \theta}$ | $\csc \theta$         | $\pm\frac{1}{\sqrt{1 - \cos^2 \theta}}$ | $\pm\frac{\sec \theta}{\sqrt{\sec^2 \theta - 1}}$ | $\pm\frac{\sqrt{1 + \tan^2 \theta}}{\tan \theta}$ | $\pm\sqrt{1 + \cot^2 \theta}$ |
| $\cos \theta =$  | $\pm\sqrt{1 - \sin^2 \theta}$ | $\pm\frac{\sqrt{\csc^2 \theta - 1}}{\csc \theta}$ | $\cos \theta$         | $\frac{1}{\sec \theta}$ | $\pm\frac{1}{\sqrt{1 + \tan^2 \theta}}$ | $\pm\frac{\cot \theta}{\sqrt{1 + \cot^2 \theta}}$ |
| $\sec \theta =$  | $\pm\frac{1}{\sqrt{1 - \sin^2 \theta}}$ | $\pm\frac{\csc \theta}{\sqrt{\csc^2 \theta - 1}}$ | $\frac{1}{\cos \theta}$ | $\sec \theta$         | $\pm\sqrt{1 + \tan^2 \theta}$ | $\pm\frac{\sqrt{1 + \cot^2 \theta}}{\cot \theta}$ |
| $\tan \theta =$  | $\pm\frac{\sin \theta}{\sqrt{1 - \sin^2 \theta}}$ | $\pm\frac{1}{\sqrt{\csc^2 \theta - 1}}$ | $\pm\frac{\sqrt{1 - \cos^2 \theta}}{\cos \theta}$ | $\pm\sqrt{\sec^2 \theta - 1}$ | $\tan \theta$         | $\frac{1}{\cot \theta}$ |
| $\cot \theta =$  | $\pm\frac{\sqrt{1 - \sin^2 \theta}}{\sin \theta}$ | $\pm\sqrt{\csc^2 \theta - 1}$ | $\pm\frac{\cos \theta}{\sqrt{1 - \cos^2 \theta}}$ | $\pm\frac{1}{\sqrt{\sec^2 \theta - 1}}$ | $\frac{1}{\tan \theta}$ | $\cot \theta$ |

------

# Fisica – Formulario

## Cinematica

**Accelerazione di gravità**: $\vec g = 9,81m/s^2$

### Moto rettilineo uniforme (MRU)

- Legge oraria: $ x(t) = x_0 + v·t $

### Moto rettilineo uniformemente accelerato (MRUA)

- Legge oraria: $ x(t) = x_0 + v_0 t + \frac12 a t^2 $
- Velocità: $ v(t) = v_0 + at $
- Equazione utile: $ v^2 = v_0^2 + 2a(x - x_0) $

### Moto Parabolico

È la combinazione di un moto rettilineo uniforme in orizzontale e un moto rettilineo uniformemente accelerato in verticale. 

**Equazione del moto**:
$$
\begin{cases}x(t) = v_0·\cos\theta·t \\ y(t) = v_0·\sin\theta·t - \frac 1 2 gt^2\end{cases}
$$
**Equazione della gittata**:


$$
y(x) = x\tan\theta- {g \over 2(v_0\cos\theta)^2}x^2
$$

#### Gittata massima

$$
x_{max}={v_0^2\sin(2\theta)\over g}
$$

Da notare che la gittata dipende strettamente dall'angolo $\theta$. La gittata massima assoluta si ha quando $\theta = 45°$.

#### Massima altezza 

- Tempo di massima altezza:
  $$
  t_{max}={v_0\sin\theta\over g}
  $$

- Ascissa di massima altezza (quando il punto cambia direzione sull'asse delle ordinate):
  $$
  
  $$
  

### Moto circolare

- Velocità angolare: $ \omega = \frac{d\theta}{dt} $
- Frequenza: $ f = 1/T $
- Velocità tangenziale: $ v = \omega r $
- Accelerazione centripeta: $ a_c = v^2/r = \omega^2 r $

------

## Dinamica

### Prima legge della dinamica

- Un corpo mantiene lo stato di quiete o moto rettilineo uniforme se la risultante delle forze è nulla.

### Seconda legge della dinamica

- $ \vec{F}_{\text{tot}} = m \vec{a} $

### Terza legge della dinamica

- A ogni azione corrisponde una reazione uguale e contraria.

### Forze fondamentali

- Peso: $ \vec{P} = m \vec{g} $
- Forza elastica (Hooke): $ \vec{F} = -k \vec{x} $
- Attrito radente dinamico: $ F_a = \mu_d N $
- Attrito radente statico: $ F_{a,\text{max}} = \mu_s N $
- Reazione vincolare: perpendicolare alla superficie

### Moto su piano inclinato

- Componenti del peso:
  - $ P_\parallel = mg \sin \theta $
  - $ P_\perp = mg \cos \theta $

### Lavoro ed Energia

- Lavoro di una forza costante: $ L = F s \cos \theta $
- Energia cinetica: $ K = \frac12 mv^2 $
- Energia potenziale gravitazionale: $ U = mgh $
- Teorema dell'energia cinetica: $ L_{\text{tot}} = K_f - K_i $

### Quantità di moto

- $ \vec{p} = m \vec{v} $
- Impulso: $ \vec{J} = \vec{F} \Delta t $
- Relazione impulso-quantità di moto: $ \vec{J} = \Delta \vec{p} $

------

## Moto armonico

- Legge oraria: $ x(t) = A \cos(\omega t + \phi) $
- Velocità: $ v(t) = -A \omega \sin(\omega t + \phi) $
- Accelerazione: $ a(t) = -A \omega^2 \cos(\omega t + \phi) = -\omega^2 x(t) $
- $ \omega = \sqrt{k/m} $

------

Se vuoi posso aggiungere schemi, esempi o versioni più compatte della pagina!
