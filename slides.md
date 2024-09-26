---
theme: apple-basic
title: Mob Prog FR
info: |
  ## Mob Programming FR
  Un lieu pour que les devs échangent et partagent autour du développement en équipe.
  En kata ou sous forme de discussions.

  Pour vous inscrire [https://www.meetup.com/paris-mob-programming/](https://www.meetup.com/paris-mob-programming/)
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: 'Cabin Sketch'
  serif: 'Love Ya Like A Sister'
  mono: 'Fira Code'
class: text-center
---

# Redécouvrir la coopération

Mob Programming

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://www.meetup.com/paris-mob-programming" target="_blank" alt="Meetup" title="Register in Meetup"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <img class="slidev-icon" style="filter: grayscale(1); max-width: 30px;" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Meetup_Logo.png" alt="Meetup logo"/>
  </a>
</div>

<img class="slidev-icon" style="border-radius: 50px; max-width: 70%;" src="/cover.jpg" alt="MobProgFr logo"/>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)

# Celles qui me semblé adaptées dans notre contexte :
# « Chacun-e est garant-e » ou « co responsabilité », « souveraineté » (aka je sors du mob ou « passe » au besoin), « bienveillance », « pour et pas contre », et « discussions fertiles »
-->

---
layout: intro
---

# Marjorie Aubert
<br/>

<div grid="~ cols-2 gap-4">
    <div>
        <ul>
            <li>Développeuse web fullstack</li>
            <li>Mobbeuse à temps plein</li>
        </ul>
    </div>
    <div>
        <img src="/marjorie.jpg" alt="Portrait de Marjorie" style="border-radius: 50px; max-width: 100%; max-height: 80%;" />
    </div>
</div>

---
layout: intro
---

# Manon Carbonnel
<br/>

<div grid="~ cols-2 gap-4">
    <div>
        <ul>
            <li>Développeuse et intégratrice web</li>
            <li>Facilitatrice Agile</li>
        </ul>
    </div>
    <div>
        <img src="/manon.jpg" alt="Portrait de Manon" style="border-radius: 50px; max-width: 100%; max-height: 80%;" />
    </div>
</div>

---
transition: slide-up
---

# C'est quoi le mob programming ?

|     |     |
| --- | --- |
| ✋ Vous avez déjà entendu parler de la pratique  | <Counter :count="0" /> |
| <v-click>✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<br/>
<br/>

<v-click>

Le développement en équipe (mob ou ensemble programming ou Software Teaming) c'est rassembler

<span v-mark.red="3">toutes les personnes</span> nécessaires
au succès d'<span v-mark.red="3">une tâche</span>
autour d'<span v-mark.red="3">un seul poste de travail</span>.

</v-click>

---

# Vos attentes

```md {monaco}
Pourquoi êtes-vous ici ?

- 
- 
- 

Vous avez envie de repartir avec :

- 
- 
- 

```
---
layout: quote
class: text-center
transition: slide-up
---

"Pour qu'une idée arrive dans le code, elle doit passer par le cerveau de quelqu'un d'autre."

*Llewellyn Falco*


---
layout: image
image:  /baba-is-you.avif
transition: slide-up
---


---
layout: image-right
image:  /mob-andrea-zuill.png
transition: slide-up
---

# Roles

---

# Driver ou traducteur-ice

Personne au clavier

- Ne décide pas
- Implémente du mieux qu'iel peut
- Pose des questions pour clarifier

ℹ️ Aucune initiative.

---

# Navigator ou co-pilote

Extrait la connaissance de l'équipe

- Explique l'intention au driver
- Au plus haut niveau possible
- Jusqu'à l'explication des touches

ℹ️ Sélectionne une idée du groupe.

<v-click>
<br/>

Par exemple :

```md {monaco}
1 - « Peux-tu écrire un test pour le cas Buzz ? »
2 - « Écris un test qui vérifie que quand on appelle la fonction avec le nombre 5 on retourne "Buzz" »
3 - « Tu peux dupliquer le bloc de code entre la ligne 17 et 23, et changer les valeurs ligne 18 et 22 »
```
</v-click>

---

# Mobber ou équipier-ère

- Proposer des idées
- Soutenez les idées des autres
- Lâchez prise
- Parlez au bon moment

ℹ️ Cherche comment aider, ou écoute attentivement.

<!-- 
Droits et devoirs

- Vous devez lever la main pour parler, seule la navigateurice peut vous donner la parole
- Vous avez le droit de poser des questions jusqu'à ce que vous compreniez ce qui se passe
- Vous souhaitez faire une pause, avez besoin de temps pour réfléchir, n'hésitez pas à verbaliser vos besoins. 

C'est le rôle le plus important. C'est vous le moteur de l'équipe. On favorise les décisions rapides pour dynamiser le mob. Alors poussez fort derrière les idées, les bonnes comme les mauvaises. C'est mieux pour l'équipe d'aller rapidement dans un mur que de démonter les idées en débattant longuement. On ne cherche pas le code parfait, juste le code fait ensemble.
-->

---
layout: quote
class: text-center
transition: slide-up
---

"Le but n’est pas de faire de l’art, c’est d’être dans cet état merveilleux qui rend l’art inévitable."

*Robert Henri*

---
transition: slide-up
layout: image-right
image: /psychological-safety-daniel-tuttle-DezqNIFG8jk-unsplash.jpg
---

# Sécurité psychologique
<br/>

Partez du principe que nous sommes toustes très compétents et compétentes.

- Droit à l’erreur
- Partager ses échecs
- Favoriser la parole des personnes moins privilégiées
- Esprit de soutien et entraide
- Écoute active
- Laisser son ego de côté
- Évite l'aide infligée

<!--
Exemple : Je suis un·e dev expérimenté·e avec une super idée. Il vaut mieux laisser un·e junior proposer quelque chose.
il vaut mieux un long silence clôt par un ou une dev junior, qu'une équipe qui ne donne sa place qu'aux devs seniors

Aidez l'équipe à se débloquer, google, chatgpt, doc officielle, dégainez tout
Partez quand vous voulez, faites des pauses quand vous voulez. (Règle des deux pieds)
Partagez lors de fréquentes rétrospectives
-->

---

# TDD

Parce que c'est le plus simple pour travailler en équipe on va aussi travailler en développement guidé par les tests.

|                                                |                        |
|------------------------------------------------|------------------------|
| ✋ Vous avez déjà entendu parler de la pratique | <Counter :count="0" /> |
| <v-click> ✋ Vous avez déjà pratiqué </v-click> | <Counter :count="0" /> |

<v-click>
<br/>

3 phases du cycle
1. Rouge (test simple qui échoue)
2. Green (solution la plus facile)
3. Refactor (plus propre si nécessaire)

</v-click>

---

# Disclaimer

- On ne finira l'exercice de code
- On ne codera pas comme vous l'auriez fait seul·e

<v-click>Mais <span v-mark.red="1">c'est pas grave</span>, avancer ensemble et s'amuser c'est plus important.</v-click>

---
transition: slide-up
---

# Bilan de vos attentes

```md {monaco}
Vous avez validé :

- 
- 
- 

Vous auriez aimé repartir avec :

- 
- 
- 

```

---
layout: center
class: text-center
---

# Bonus

Des petits liens cool

---
layout: center
class: text-center
---

<div grid="~ cols-2 gap-20">
    <div>
      <h2>Ensemble Toolbox</h2>
      <h3>Facilitez vos sessions de travail en équipe</h3>
      <br/>
      <Youtube id="c_oW0yJWveQ" width="100%" height="250px" />
    </div>
    <div>
      <h2>Software teaming</h2>
      <h3>Onboarding, Remote, productivité, 4ans dans la vie d'une équipe</h3>
      <br/>
      <Youtube id="IL9z_HminTo" width="100%" height="250px" />
    </div>
</div>

---
layout: center
class: text-center
---

# MobTime

Gérer le chrono et la rotation des rôles

[https://mobtime.hadrienmp.fr/](https://mobtime.hadrienmp.fr/)

---
layout: image-right
image:  /qrcode_openfeedback.io.png
---

# Merci !

<br/>

## Feedback ici 👉



