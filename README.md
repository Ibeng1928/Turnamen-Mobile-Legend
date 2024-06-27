# Turnamen-Mobile-Legend
supportifitas
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Turnamen Mobile Legends</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Turnamen Mobile Legends</h1>
    </header>

    <main>
        <section id="registration">
            <h2>Pendaftaran Tim</h2>
            <form id="registration-form">
                <label for="team-name">Nama Tim:</label>
                <input type="text" id="team-name" required>

                <label for="team-leader">Nama Kapten:</label>
                <input type="text" id="team-leader" required>

                <label for="team-members">Anggota Tim (pisahkan dengan koma):</label>
                <input type="text" id="team-members" required>

                <button type="submit">Daftar</button>
            </form>
        </section>

        <section id="teams">
            <h2>Daftar Tim</h2>
            <table id="teams-table">
                <thead>
                    <tr>
                        <th>Nama Tim</th>
                        <th>Nama Kapten</th>
                        <th>Anggota Tim</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- Daftar tim akan muncul di sini -->
                </tbody>
            </table>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
