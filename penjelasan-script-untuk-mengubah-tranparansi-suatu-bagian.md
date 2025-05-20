# Penjelasan Kode Transparansi Roblox

Mari kita breakdown kode berikut:

````lua
game.Workspace.Button1.Transparency = 0.5
````

## Analogi Sederhana 👓

Bayangkan sebuah kaca:
- Nilai 0 = Kaca yang benar-benar buram (tidak transparan sama sekali)
- Nilai 0.5 = Kaca setengah bening (bisa melihat samar-samar ke dalam)
- Nilai 1 = Kaca yang benar-benar bening (transparan total/tidak terlihat)

## Penjelasan Detail 📝

Kode ini terdiri dari beberapa komponen:
1. `game.Workspace` → Area kerja dalam game Roblox
2. `Button1` → Nama objek yang akan diubah transparansinya
3. `Transparency` → Properti yang mengatur tingkat transparansi
4. `0.5` → Nilai transparansi (50% transparan)

## Visualisasi Tingkat Transparansi 🔍

```
Tampak Solid  <───────────────●───────────────> Tidak Terlihat
              0             0.5              1
```

## Efek yang Terjadi 🎮

- Objek "Button1" akan menjadi setengah transparan
- Pemain masih bisa melihat objek tersebut
- Benda-benda di belakang Button1 akan terlihat samar-samar

**Catatan**: Nilai transparansi dapat diatur antara 0 hingga 1, di mana:
- 0 = 0% transparan (sepenuhnya terlihat)
- 0.5 = 50% transparan (setengah transparan)
- 1 = 100% transparan (sepenuhnya tidak terlihat)