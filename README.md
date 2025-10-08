# 🎵 Procedural Music Generation for *Tomb Raider* — OpenMusic Project

## 👥 Team Members

* **David Hurtado**
* **Juan Troncoso**

---

## 🕹️ Project Description

This project consists of an **algorithmic composition** created in **OpenMusic (OM)** for the video game *Tomb Raider*.
The goal was to design a **musical environment** that fits a **calm and epic landscape** atmosphere within the game world.
All the musical material was **generated procedurally** using OpenMusic’s programming tools—without importing or using any pre-recorded audio (no WAV, MIDI, or MP3 files).

🎥 **Video demonstration:** [Watch on YouTube](https://www.youtube.com/watch?v=vkIiq0yjMLk)

---

## 🎶 Concept and Justification

The composition was designed to accompany **exploration and landscape scenes** in *Tomb Raider*, where the player experiences both **serenity and grandeur**.
To reflect this feeling, the algorithm generates **slow harmonic progressions** and **melodic layers** that evolve naturally over time.

The structure was created using **controlled musical processes** to ensure coherence while maintaining an organic flow between sections.

---

## 🧠 Technical Implementation

### 🔧 Tools and Modules Used

The OpenMusic patch was built using the following components:

* `OM+`
* `Poly`
* `Note`
* `Chord-sq`
* `x-append`
* `concat`
* `Voices`
* `MkTree`

### ⚙️ Implementation Details

* **Tempo:** 88 BPM (set in `Voices`).
* **Pitch construction:** Pitches were defined through numerical lists representing intervals and chords.
* **`concat`:** Used to sequentially add notes to the `Chord-sq` object, replacing random processes or `repeat-n` patterns.
* **`x-append`:** Combined multiple musical phrases into larger segments.
* **`OM+`:** Applied a pitch shift of **+200 semitones** to transpose the scale slightly upward, achieving a brighter and more distinctive tone.
* **`Strings Assembly`:** Used as the instrumental layer to provide an **epic orchestral texture**.
* **SoundFont (.sf2):** A string-based soundfont was loaded to give the piece a realistic and cinematic sound quality.
* **`MkTree`:** Helped organize and structure the musical hierarchy across sections.

---

## Result

The final output is a **two-minute procedural composition** that captures the **epic serenity** of *Tomb Raider’s* landscapes.
All sound and structure were **generated natively in OpenMusic**, blending harmonic stability with a cinematic orchestral tone.

---
