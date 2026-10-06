một ngôi trường mới, những người bạn mới
                    và vô số điều chưa từng trải qua.
                </p>
                <p>
                    Có thể sẽ có những ngày rất vui,
                    cũng sẽ có những ngày nhớ nhà,
                    mệt mỏi hoặc cảm thấy hơi cô đơn.
                </p>
                <p>
                    Nhưng mà <strong>đừng quên nha:</strong>
                    bả đã đủ giỏi để bước đến nơi đó rồi.
                    Cứ từ từ mà khám phá,
                    cứ thử những điều mới
                    và sống thật trọn vẹn với khoảng thời gian
                    đáng nhớ này.
                </p>
                <p>
                    Mong rằng Đài Loan sẽ đối xử thật dịu dàng
                    với bả. 🌷
                </p>
            </div>
            <button onclick="nextPage(3)">
                Còn một điều muốn nói... 💌
            </button>
        </div>
    </section>
    <!-- TRANG 3: KẾT -->
    <section class="page" id="page3">
        <div class="heart h1">💗</div>
        <div class="heart h2">✨</div>
        <div class="heart h3">🌸</div>
        <div class="heart h4">💕</div>
        <div class="card">
            <div class="taiwan">
                🇻🇳 ✈️ 🇹🇼
            </div>
            <h1>Chúc bả thật vui nhé! 💗</h1>
            <div class="final">
                <p>
                    Chúc Huỳnh Giao có một hành trình
                    thật đẹp ở Đài Loan.
                </p>
                <p>
                    Học thật tốt 📚<br>
                    Gặp thật nhiều người tốt 🫶<br>
                    Ăn thật nhiều món ngon 🧋<br>
                    Đi thật nhiều nơi đẹp 🌸<br>
                    Và tạo thật nhiều kỷ niệm đáng nhớ ✨
                </p>
                <p>
                    Dù sau này có ở cách nhau bao xa,
                    những kỷ niệm đẹp vẫn sẽ luôn ở đó. 💕
                </p>
                <div class="signature">
                    From someone who wishes you
                    all the best 💗
                </div>
            </div>
            <button onclick="nextPage(1)">
                Xem lại từ đầu 🌷
            </button>
        </div>
    </section>
    <script>
        function nextPage(pageNumber) {
            // Ẩn tất cả trang
            document.querySelectorAll(".page").forEach(page => {
                page.classList.remove("active");
            });
            // Hiện trang được chọn
            document.getElementById("page" + pageNumber)
                .classList.add("active");
        }
    </script>
</body>
</html>
