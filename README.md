## 🧠 Sobre o Projeto

A **Troca de telas** é um app educacional voltado principalmente para o aprendizado de:

- troca de telas no programa AndroidStudios
- MainActivity
- relação de botões em ambas das telas

---

- ## 🛠️ Tecnologias Utilizadas


| Categoria | Ferramenta |
|------------|-------------|
| IDE | Android Studio |
| Linguagem | Java |
| Layouts | XML |
| Versão mínima Android | API 21 (Android 5.0 Lollipop) |
| Estrutura de UI | ConstraintLayout / LinearLayout |
| Recursos gráficos | Drawable Resources |

---

## 📱 Estrutura do Projeto

```
app/
 ├── java/
 │    └── br/ulbra/trocadetelas/
 │         └── MainActivity.java
 ├── res/
 │    ├── layout/
 │    │     └── tela2.xml
 │    │     └── tela_principal.xml
 │    ├── drawable/
 │    │     ├── ic_launcher_background.xml
 │    │     ├── ic_launcher_foreground.xml 
 │    └── values/
 │          └── strings.xml
 │          └── themes.xml
 └── AndroidManifest.xml
```

---

## 🧰 Estrutura XML - tela principal

O layout principal (`activity_main.xml`) contém:
- 1 textView (para indicar que o usuário está na tela principal)
- 1 botão (para ir para a tela2)

---

## 🧰 Estrutura XML - tela2

O layout principal (`tela2.xml`) contém:
- 1 textView (para indicar que o usuário está na tela2)
- 1 botão (para ir para a tela principal)

---

## 👩‍💻 Autor / Equipe

**Nome:** *Igor Torres Dias*  
**Instituição:** *Curso Técnico em Informática – Colégio São Lucas*  
**Disciplina:** *Desenvolvimento Mobile Android*  
**Professor:** *Jeferson Leon*  

---

## 📚 Licença

Este projeto foi desenvolvido para fins **educacionais**.  
Você pode modificar, reutilizar e distribuir livremente o código, mantendo os devidos créditos.
