<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile - Najwa Muthmainnah</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            /* Latar belakang bernuansa workstation/kantor */
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), 
                        url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            background-color: #ffffff;
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 320px;
            box-sizing: border-box;
        }

        .profile-container {
            position: relative;
            width: 150px;
            height: 150px;
            margin: 0 auto 25px auto;
        }

        /* Border lingkaran biru muda di luar foto */
        .profile-container::before {
            content: '';
            position: absolute;
            top: -6px;
            left: -6px;
            right: -6px;
            bottom: -6px;
            border: 4px solid #a3d3ed;
            border-radius: 50%;
        }

        .profile-img {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
        }

        .greeting {
            font-size: 13px;
            color: #555555;
            letter-spacing: 1.5px;
            margin-bottom: 12px;
            font-weight: 600;
        }

        h1 {
            color: #1a2a3a;
            font-size: 26px;
            font-family: 'Georgia', serif; /* Memberikan sentuhan elegan seperti di gambar */
            font-weight: normal;
            line-height: 1.2;
            margin: 0 0 20px 0;
        }

        .role {
            color: #666666;
            font-size: 12px;
            letter-spacing: 2px;
            font-weight: 600;
            margin: 0;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="profile-container">
            <!-- Ganti '22588.webp' dengan nama file foto Anda jika diletakkan di folder berbeda -->
            <img src="22588.webp" alt="Najwa Muthmainnah" class="profile-img">
        </div>
        
        <div class="greeting">HELLO, MY NAME IS</div>
        <h1>Najwa<br>Muthmainnah</h1>
        <div class="role">WEB DEVELOPER</div>
    </div>

</body>
</html>
