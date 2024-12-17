<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drillegal Yetkili Başvuru Formu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin: 10px 0 5px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        button {
            background-color: #007bff;
            color: #fff;
            padding: 10px;
            width: 100%;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .notice {
            color: red;
            font-size: 14px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Drillegal Yetkili Başvuru Formu</h1>
        <form id="applicationForm">
            <!-- Kişisel Bilgiler -->
            <label for="name">Adınız Soyadınız:</label>
            <input type="text" id="name" placeholder="Adınızı ve soyadınızı girin" required>

            <label for="age">Yaşınız:</label>
            <input type="number" id="age" placeholder="Yaşınızı girin" min="10" required>

            <label for="discord">Discord Kullanıcı Adınız:</label>
            <input type="text" id="discord" placeholder="Örn: KullanıcıAdı#0000" required>

            <!-- Deneyim -->
            <label for="experience">Daha önce yetkili oldunuz mu? (Evet / Hayır):</label>
            <input type="text" id="experience" placeholder="Yetkili olup olmadığınızı belirtin" required>

            <label for="reason">Yetkili Olma Nedeniniz:</label>
            <textarea id="reason" placeholder="Yetkili olma nedeninizi yazınız..." rows="4" required></textarea>

            <!-- Onay Kutusu -->
            <label>
                <input type="checkbox" id="agree" required> Verdiğim bilgilerin doğru olduğunu onaylıyorum.
            </label>

            <!-- Gönder Butonu -->
            <button type="button" onclick="sendToDiscord()">Başvuruyu Gönder</button>
        </form>
        <div class="notice" id="status"></div>
    </div>

    <script>
        function sendToDiscord() {
            const name = document.getElementById("name").value;
            const age = document.getElementById("age").value;
            const discordUser = document.getElementById("discord").value;
            const experience = document.getElementById("experience").value;
            const reason = document.getElementById("reason").value;
            const agree = document.getElementById("agree").checked;

            if (!agree) {
                document.getElementById("status").innerText = "Lütfen bilgilerin doğru olduğunu onaylayın!";
                return;
            }

            const webhookURL = "https://discord.com/api/webhooks/1318569145415106561/U2Kkwl8Ssngf_2oXsgJcPnTigQjuqo1t6vIxp8JGr5bj20Lwxylja6UzxYYgZ_2QPXW8"; // Discord Webhook URL'nizi buraya yapıştırın.

            const payload = {
                embeds: [{
                    title: "📝 Yeni Yetkili Başvurusu",
                    color: 7506394,
                    fields: [
                        { name: "👤 Ad Soyad", value: name, inline: true },
                        { name: "🔢 Yaş", value: age, inline: true },
                        { name: "🆔 Discord Kullanıcı Adı", value: discordUser, inline: false },
                        { name: "🔎 Deneyim", value: experience, inline: false },
                        { name: "📝 Yetkili Olma Nedeni", value: reason, inline: false }
                    ],
                    footer: {
                        text: "Drillegal Başvuru Sistemi",
                        icon_url: "https://cdn-icons-png.flaticon.com/512/25/25231.png"
                    },
                    timestamp: new Date()
                }]
            };

            fetch(webhookURL, {
                method: "POST",
                headers: { "Content-Type": "application/json" },
                body: JSON.stringify(payload)
            })
            .then(response => {
                if (response.ok) {
                    document.getElementById("status").innerText = "Başvurunuz başarıyla gönderildi!";
                    document.getElementById("status").style.color = "green";
                    document.getElementById("applicationForm").reset();
                } else {
                    document.getElementById("status").innerText = "Bir hata oluştu. Lütfen tekrar deneyin.";
                    document.getElementById("status").style.color = "red";
                }
            })
            .catch(error => {
                console.error("Hata:", error);
                document.getElementById("status").innerText = "Bir hata oluştu. Lütfen tekrar deneyin.";
                document.getElementById("status").style.color = "red";
            });
        }
    </script>
</body>
</html>
