# Ayah Loop

Play a list of Quran verses from any surahs, in order, on repeat. Built for memorising while driving.

Two tabs:

- **Quran**: verses recited by a chosen reciter.
- **Hadith**: the first 10 of Imam an-Nawawi's 40 hadith (with narrator and source) and 31 hadith from the first chapters of the HGWC 1st-year muthoon, read aloud by the phone's own Arabic text-to-speech voice. Filter by topic, set speed, repeats and pause, and optionally pause at punctuation or read without tashkeel.

## Quran tab

- Enter verses as `2:255`, ranges as `18:1-5`, or global ayah numbers like `231`.
- Filter by subject (Aqeedah, Fiqh, Quran, Seerah) from the HGWC 1st-year muthoon, or play all.
- Choose a reciter and how many times each ayah plays.
- English and Tamil interface.
- Audio streams per ayah from [everyayah.com](https://everyayah.com).

## Hadith tab

- Uses the browser's Web Speech API, so no audio files or server are needed.
- Needs an Arabic voice on the device (iPhone: Spoken Content → Voices → Arabic; Android: Google text-to-speech → Arabic).
- Speech stops when the screen locks, so the page keeps the screen awake while playing.
