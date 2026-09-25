<div align="center">

<img src="https://raw.githubusercontent.com/Sama-ndari/kirundi-contribution-app/main/static/icon.png" alt="Ijwi ry'Ikirundi AI" width="120" style="border-radius: 50%;" />

# Ijwi ry'Ikirundi AI

**Ikirundi cacu, Ijwi ryacu!**  
*Notre langue, notre voix.*

Infrastructure IA open-source pour le Kirundi — parole, texte et traduction.

[![Contribuer](https://img.shields.io/badge/Contribuer-Application_Web-2ea44f?style=for-the-badge)](https://sama-ndari.github.io/kirundi-contribution-app/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Organisation-ffcc00?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Ijwi-ry-Ikirundi-AI)
[![Licence données CC BY 4.0](https://img.shields.io/badge/Données-CC_BY_4.0-lightgrey?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)

</div>

---

## Mission

**Ijwi ry'Ikirundi AI** est une initiative communautaire qui construit les premières ressources Kirundi ouvertes et à grande échelle pour l’IA moderne.

Nous produisons les données et modèles nécessaires pour :

| Capacité | Objectif |
| --- | --- |
| **ASR** — Speech-to-Text | Comprendre le Kirundi parlé |
| **TTS** — Text-to-Speech | Synthétiser une voix naturelle en Kirundi |
| **MT** — Traduction automatique | Kirundi ↔ Français / Anglais |

Le Kirundi est parlé par des millions de personnes en Afrique de l’Est. Données et modèles ouverts placent la langue au même niveau dans le monde numérique.

---

## Écosystème

Trois piliers connectés :

| Pilier | Dépôt | Rôle |
| --- | --- | --- |
| **Dataset** | [`Kirundi_Dataset`](https://github.com/Ijwi-ry-Ikirundi-AI/Kirundi_Dataset) | Corpus texte + audio (`metadata.csv`, clips, pipelines) |
| **App de contribution** | [`kirundi-contribution-app`](https://github.com/Sama-ndari/kirundi-contribution-app) | Traductions et phrases neuves par la communauté |
| **Modèle de traduction** | [`nllb-kirundi-multi`](https://huggingface.co/Ijwi-ry-Ikirundi-AI/nllb-kirundi-multi) | NLLB-200 (600M) fine-tuné pour KR ↔ FR / EN |

**Hugging Face** héberge le dataset et le modèle publiés :  
→ [Ijwi-ry-Ikirundi-AI](https://huggingface.co/Ijwi-ry-Ikirundi-AI)

---

## État actuel

| Ressource | Échelle |
| --- | --- |
| Phrases texte / parallèles | ~4 700+ |
| Phrases gold (KR + FR + EN) | ~2 900+ |
| Clips audio | ~100+ (en croissance) |
| Modèle MT | NLLB-200-distilled-600M · BLEU V1 ≈ 9,9 |

Objectifs : **10k+** phrases validées · **20h+** de parole · MT plus fort à chaque release de données.

---

## Comment contribuer

Aucune compétence technique requise pour la plupart des contributions.

1. Ouvrir l’app → [Contribuer](https://samandari.dev/kirundi-contribution-app/)
2. Choisir un niveau :
   - **Facile** — Kirundi → Français
   - **Moyen** — Français → Kirundi
   - **Difficile** — Ajouter des paires de phrases originales
3. Développeurs : issues / PR sur [`Kirundi_Dataset`](https://github.com/Ijwi-ry-Ikirundi-AI/Kirundi_Dataset) (texte sur GitHub ; audio via le remote Hugging Face du dataset)

---

## Licence

- **Code** — MIT (voir chaque dépôt)
- **Données** — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (attribution requise)
- **Modèle** — Apache-2.0 sur Hugging Face

Construit au Burundi, pour les locuteurs du Kirundi et la communauté open-source.
