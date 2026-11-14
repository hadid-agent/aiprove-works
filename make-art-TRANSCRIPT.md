# AIProve Make-Art Poster — Transcript (Bounty: make-art-aiprove)

## Konsep
Poster vertikal bergaya halaman depan koran (front page) untuk memberi AIProve sebuah "wajah":

- Masthead serif hitam besar: **AIPROVE**
- Ilustrasi utama: maskot yang SAMA persis dengan bounty mascot — **Prompt**, burung hantu kecil gemuk dari kertas koran krem (kolom teks cetak + halftone di badan bulatnya), mata besar hitam berpupil kursor terminal hijau `>`, paruh berbentuk `>`, syal dari potongan kolom koran monospace, outline tinta hitam letterpress.
- Di poster, Prompt berdiri gagah melambai sambil memegang terminal retro mungil berlayar `>_`.
- Subjudul monospace persis: **FREE TO ENTER · GRADED IN THE OPEN · PAID IN STOCK**
- Bingkai garis kolom koran tipis, tinta hitam di kertas krem, tekstur halftone — broadsheet-meets-terminal.

Karakter sengaja dibuat identik dengan `mascot.png` agar kedua bounty terasa satu keluarga visual.

## Prompt iterasi 1
> Create a vertical portrait poster designed as a classic newspaper front page, broadsheet-meets-terminal style: black ink on cream paper, bold serif typography, halftone print texture, letterpress, thin newspaper column rules and borders, with monospace terminal accents in glowing green.
>
> At the very top, a huge masthead in bold black serif capital letters, exactly spelled: AIPROVE
> Below it a thin black rule line.
>
> Main illustration in the center, large: THE EXACT SAME mascot character — a small chubby owl made of folded cream newspaper paper with visible black printed text columns and halftone dots on its round body, tiny folded paper wings, large round eyes where the pupils are glowing green terminal block cursors, tiny black ink beak shaped like a > prompt symbol, wearing a narrow scarf made of a newspaper column strip with tiny monospace text lines, small paper feet, thick black ink outlines, terminal green accent only for the eyes. The owl stands proudly holding a small terminal and waving, heroic front-page illustration pose.
>
> Below the illustration, in clean monospace typewriter font, exactly this subtitle in capital letters, exactly spelled: FREE TO ENTER · GRADED IN THE OPEN · PAID IN STOCK
>
> Keep all other text minimal, fake tiny newspaper column lines as texture only, no other readable words. Vertical poster composition, cream background, high craft, original work.

Tool: `media.generate_image`, output PNG vertikal.

**Hasil iterasi 1:** Teks sempurna (AIPROVE benar eja; subjudul persis), TETAPI maskot berubah jadi burung hantu origami bersudut/geometris — menyimpang dari karakter bulat di sheet mascot. Ditolak demi konsistensi karakter.

## Prompt iterasi 2 — FINAL (dengan gambar referensi)
Iterasi 2 memakai `mascot.png` sebagai gambar referensi yang dilampirkan ke prompt, dengan instruksi eksplisit memakai karakter itu persis:

> Use the owl character from the reference image exactly as the main character: same small chubby round newspaper owl, same round body covered in newspaper text columns, same large black round eyes with glowing green > pupils, same newspaper-column scarf, same style. Do not change it into origami or geometric style — keep its soft round chubby letterpress look identical to the reference.
>
> Create a vertical portrait poster designed as a classic newspaper front page, broadsheet-meets-terminal style: black ink on cream paper, bold serif typography, halftone print texture, letterpress, thin newspaper borders.
>
> At the very top, huge masthead in bold black serif capital letters, exactly spelled: AIPROVE
> Below it a thin black rule line.
>
> In the center, large illustration of that exact same chubby newspaper owl mascot from the reference, standing proudly, waving one wing, holding a tiny retro terminal showing >_ in green.
>
> Below the illustration, in clean monospace font, exactly this subtitle in capital letters, exactly spelled: FREE TO ENTER · GRADED IN THE OPEN · PAID IN STOCK
>
> No other readable words, only tiny fake newspaper column lines as texture. Vertical poster, cream background, original work.

**Hasil iterasi 2: DITERIMA sebagai final (`make-art.png`).** Pemeriksaan visual:
- Masthead "AIPROVE" — ejaan benar, serif besar, terbaca jelas.
- Subjudul "FREE TO ENTER · GRADED IN THE OPEN · PAID IN STOCK" — ejaan benar & terbaca (tersusun dalam dua baris di bagian bawah, kata-katanya persis).
- Karakter kini sama dengan sheet mascot: bulat gemuk, badan koran, mata `>` hijau, syal kolom koran, melambai + memegang terminal `>_`.

## Iterasi ringkas
- Mascot sheet: 1x generate, langsung final.
- Poster: 2x generate (1 ditolak karena karakter menyimpang jadi origami, 1 final dengan referensi gambar).

## Kejujuran proses
Karya orisinal buatan sesi ini dari konsep & prompt di atas, bukan menjiplak karya orang lain. Teks kecil di kolom koran adalah tekstur dekoratif hasil generasi, bukan teks berhak cipta yang disalin.
