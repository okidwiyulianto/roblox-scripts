# 🌟 Roblox Studio Script Collection
## ✨ Kumpulan Script Keren untuk Membuat Game Roblox Lebih Menarik!

Selamat datang di repositori script Roblox Studio-ku! 🎮 Di sini, kamu akan menemukan berbagai skrip Lua yang bisa mempercantik game Roblox-mu. Cocok untuk pemula sampai yang sudah mahir!

## 📂 Contoh Daftar Script
### 1. 🏃‍♂️ Auto-Run Script
Fungsi: Membuat karakter berlari otomatis saat game dimulai.<br>
Kegunaan: Perfect untuk game balap atau endless runner!
```lua
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
character.Humanoid.WalkSpeed = 25 -- Kecepatan lari (default 16)
```

### 2. 💥 Damage System
Fungsi: Memberi damage ke pemain saat menyentuh part tertentu.<br>
Kegunaan: Bagus untuk game battle atau obstacle!
```lua
local part = script.Parent
part.Touched:Connect(function(hit)
    local humanoid = hit.Parent:FindFirstChild("Humanoid")
    if humanoid then
        humanoid:TakeDamage(10) -- Damage yang diberikan
    end
end)
```

### 3. 🌈 Color-Changing Part
Fungsi: Membuat part berubah warna setiap detik.<br>
Kegunaan: Cocok untuk efek visual atau puzzle game!
```lua
local part = script.Parent
while true do
    part.Color = Color3.new(math.random(), math.random(), math.random())
    wait(1) -- Waktu perubahan warna (dalam detik)
end
```

### 4. 🎮 GUI Click Teleport
Fungsi: Teleport pemain saat mengklik tombol di GUI.<br>
Kegunaan: Berguna untuk game dengan banyak lokasi!
```lua
local button = script.Parent
button.MouseButton1Click:Connect(function()
    game.Players.LocalPlayer.Character:MoveTo(Vector3.new(0, 10, 0)) -- Posisi teleport
end)
```

## 🚀 Cara Pakai
1. Copy script yang kamu mau.
2. Paste di Roblox Studio (via Script Editor).
3. Atur variabel sesuai kebutuhan (misal: damage, warna, dll).
4. Test & enjoy! 🎉

## 💡 Ide Kreatif
* Gabungkan Damage System + Color-Changing Part untuk membuat trap yang mematikan dan colorful!
* Pakai Auto-Run + GUI Teleport untuk buat game speedrun yang seru!

## 🤝 Mau Kontribusi?
Aku terbuka untuk script keren lainnya!
1. Fork repo ini
2. Tambah script baru
3. Buat Pull Request
4. Aku akan review secepatnya! 💖

## 📬 Kontak
* Email: [admin@okidwiyulianto.com]
* Roblox Profile: [Ninjaku5758]

### Kata-kata motivasi: 
> "Coding itu seperti main game, tapi lebih seru karena kamu yang buat rules-nya!"

---

⭐ Jangan lupa kasih bintang ya kalau scriptnya berguna!<br>
🎀 Happy Coding! 😎

(Repo ini selalu di-update tiap ada script baru! Cek terus ya~)