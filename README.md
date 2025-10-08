# 🎵 Procedural Music Generation for *Tomb Raider* — OpenMusic Project

## 👥 Team Members
- **David Hurtado**
- **Juan Troncoso**

---

## 🕹️ Project Description

This project consists of an **algorithmic composition** created in **OpenMusic (OM)** for the video game *Tomb Raider*.  
The goal was to design a **musical environment** that fits a **calm and epic landscape** atmosphere within the game world.  
All the musical material was **generated procedurally** using OpenMusic’s programming tools—without importing or using any pre-recorded audio (no WAV, MIDI, or MP3 files).

---

## 🎶 Concept and Justification

The composition was designed to accompany **exploration and landscape scenes** in *Tomb Raider*, where the player experiences both **serenity and grandeur**.  
To reflect this feeling, the algorithm generates **slow harmonic progressions** combined with **melodic layers** that evolve over time.

We used the following principles:

- **Randomness and variability**: Random number generators define note durations and pitch variations to ensure freshness and avoid repetition.  
- **Controlled structure**: Cycles and lists maintain rhythmic and harmonic consistency.  
- **Type-defined parameters**: All main arguments and variables have specific types (e.g., integer for duration, list for pitch collections).  
- **Dynamic repetition**: The `repeat-n` objects were used to create motifs that repeat a controlled number of times.  
- **Combination and sequence**: Modules such as `x-append` and `mktree` were used to connect and organize musical segments into a coherent structure.

---

## 🧠 Technical Implementation

The OpenMusic patch includes:

- **Pitch collections** defined by numerical lists representing intervals and chords.  
- **Random functions** controlling pitch and rhythm variation.  
- **`repeat-n`** modules for structured repetition of motifs.  
- **`x-append`** objects to concatenate musical phrases sequentially.  
- **`mktree`** to build hierarchical structures and combine musical elements.

The result is a two-minute piece rendered directly from OpenMusic’s sound synthesis.

---



