<html>
	<head>
		<meta charset="utf-8" />
		<link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<title>WEB PERTAMA</title>
		<link rel="stylesheet" href="style.css"/>
	</head>
	<body>
		<header>
			<div class="logo">
				<img src="assets/icon/partner.png" alt="logo" class="logo-img" />
				<h1 class="logo-title">RZF X</h1>
			</div>
			
			<nav>
				<ul>
					<li><a href="#jasa">JASA</a></li>
					<li><a href="mailto:razifakbarenzano12@gmail.com">KONTAK</a></li>
				</ul>
			</nav>
			<button class="btn-cta" onclick="redirInstagram()">Follow Saya</button>
		</header>
		<div class="container">
			<div class="intro">
				<p class="title">Hello, Razif Akbar here!</p>
				<p class="description">Technology Influencer From Village.</p>
				<img src="assets/foto/razif.png" class="img-foto"/>
			</div>
		</div>
		<div class="parallax">
			<div class="tentang">
				<p class="title">Saya Adalah Programmer</p>
				<p class="description">Ngoding aja dulu, jagonya belakangan.</p>
				<div class="mt-10">
					<button class="btn-cta" onclick="redirWhatsapp()">Mari Kerjasama</button>
				</div>
			</div>
			<div class="container">
					<div class="card" id="jasa">
						<div class="card-item">
							<img src="assets/icon/24-hours.png" alt="icon 1" class="icon"/>
							<p class="card-title">Pelayanan Nonstop</p>
							<p class="card-description">Servis nonston ketika anda membutuhkan bantuan.</p>
						</div>
						<div class="card-item">
							<img src="assets/icon/hot-deal.png" alt="icon 2"  class="icon"/>
							<p class="card-title">Jasa Paling Murah</p>
							<p class="card-description">Biaya jasa yang saya berikan pasti murah dan terjamin</p>
						</div>
						<div class="card-item">
							<img src="assets/icon/rating.png" alt="icon 3"  class="icon"/>
							<p class="card-title">684 Review</p>
							<p class="card-description">Mereka senang dalam bekerjasama dengan saya.</p>
						</div>
					</div>
			</div>
		</div>
		<footer>
			<p class="title">&copy; Razif Akbar Website 2022</p>
		</footer>
		
		<script>
			function redirInstagram() {
				window.location.href = "https://instagram.com/razifakbrr"
			}
			
			function redirWhatsapp() {
				window.location.href = "https://wa.me/+6281513983136"
			}
		</script>
	</body>
</html>
