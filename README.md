# Form-Cuti-Kerja
Formulir Cuti Kerja
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Pengajuan Cuti</title>
    <style>
        /* Tambahkan sedikit styling CSS di sini agar lebih rapi */
        body { font-family: Arial, sans-serif; padding: 20px; }
        form { max-width: 600px; margin: auto; padding: 20px; border: 1px solid #ccc; border-radius: 5px; }
        label, input, textarea, select { display: block; margin-bottom: 10px; width: 100%; }
        input[type="submit"] { background-color: #28a745; color: white; padding: 10px 15px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <form action="#" method="POST" id="cutiForm">
        <h2>Pengajuan Cuti Karyawan</h2>

        <label for="nama">Nama Karyawan:</label>
        <input type="text" id="nama" name="Nama" required>

        <label for="nik">NIK/ID Karyawan:</label>
        <input type="text" id="nik" name="NIK_ID" required>

        <label for="jenisCuti">Jenis Cuti:</label>
        <select id="jenisCuti" name="Jenis_Cuti" required>
            <option value="">-- Pilih Jenis Cuti --</option>
            <option value="Cuti Tahunan">Cuti Tahunan</option>
            <option value="Cuti Sakit">Cuti Sakit</option>
            <option value="Cuti Khusus">Cuti Khusus (Melahirkan/Pernikahan, dll)</option>
        </select>

        <label for="tanggalMulai">Tanggal Mulai Cuti:</label>
        <input type="date" id="tanggalMulai" name="Tanggal_Mulai" required>

        <label for="tanggalSelesai">Tanggal Selesai Cuti:</label>
        <input type="date" id="tanggalSelesai" name="Tanggal_Selesai" required>

        <label for="alasan">Alasan Cuti:</label>
        <textarea id="alasan" name="Alasan" rows="4" required></textarea>

        <input type="submit" value="Kirim Pengajuan Cuti">
    </form>
</body>
</html>
