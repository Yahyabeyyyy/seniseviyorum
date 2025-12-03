<!DOCTYPE html>
Giriş
    <h2>Şifreyi Gir</h2>

    <input type="password" id="pass" placeholder="Şifre">
    <button onclick="check()">Gönder</button>

    <div class="hint">İpucu: istanbulda, benim ben olduğum yer</div>

    <div class="message" id="msg">Seni sen olduğun için seviyorum ❤️</div>

    <script>
        function check() {
            const pw = document.getElementById("pass").value;
            const realPass = "karaköy";

            if (pw.toLowerCase() === realPass) {
                document.getElementById("msg").style.display = "block";
            } else {
                alert("Yanlış şifre kankim 👀");
            }
        }
    </script>
