# ⚡ Otimização & Distant Horizons

O **Legião** utiliza tecnologias de renderização para trabalhar melhor com o Distant Horizons. O segredo não é força bruta, é configuração inteligente.

## 🛠️ Configurando o Distant Horizons (DH)
Mantenha o jogo leve "perto" de você para o DH cuidar do "longe".

| Configuração | Valor Recomendado | Motivo |
| :--- | :--- | :--- |
| **Render Distance (Vanilla)** | `8` a `10` Chunks | Libera CPU para gerar o mundo distante. |
| **Simulation Distance** | `8` Chunks | Mantém máquinas rodando sem pesar o servidor. |
| **DH LOD Render Distance** | `64` a `96` Chunks | Acima de 128 causa instabilidade em PCs médios. |
| **DH CPU Load** | `Balanced` | Evita conflito com a geração de terreno (C2ME). |

!!! warning "Atenção: Geração de Mundo"
    Se você notar buracos no mundo ao voar rápido, é porque o servidor/PC ainda está gerando aquele terreno pela primeira vez.
    **Solução:** Tenha paciência ou use a pré-geração abaixo.

## 🌍 Pré-Geração (Elimine o Lag)
Para uma experiência 100% lisa, gere o mapa antes de explorar.
1.  Entre no jogo e pause.
2.  Digite `/chunky center`
3.  Digite `/chunky radius 2000`
4.  Digite `/chunky start`
5.  Vá tomar um café. O PC vai trabalhar pesado por 10-15 min.

---

# ⚡ Optimization & Distant Horizons

**Legião** utilizes a lot of rendering technologies for best performance with DH. The secret is not brute force, but smart configuration.

## 🛠️ Configuring Distant Horizons (DH)
Keep the game lightweight "near" you so DH can handle the "far" distance.

| Setting | Recommended Value | Reason |
| :--- | :--- | :--- |
| **Render Distance (Vanilla)** | `8` to `10` Chunks | Frees up CPU to generate the distant world. |
| **Simulation Distance** | `8` Chunks | Keeps machines running without overloading the server. |
| **DH LOD Render Distance** | `64` to `96` Chunks | Above 128 chunks causes instability on mid-tier PCs. |
| **DH CPU Load** | `Balanced` | Prevents conflicts with C2ME terrain generation. |

!!! warning "Warning: World Generation"
    If you see holes in the world while flying fast, it means the server/PC is generating that terrain for the first time.
    **Solution:** Be patient or use the pre-generation command below.

## 🌍 Pre-Generation (Eliminate Lag)
For a 100% smooth experience, generate the map before exploring.
1.  Enter the game and pause.
2.  Type `/chunky center`
3.  Type `/chunky radius 2000`
4.  Type `/chunky start`
5.  Go grab a coffee. Your PC will work hard for 10-15 minutes.