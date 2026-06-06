<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PELAYANAN TERPADU SATU PINTU</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#f4f6f9;
}

.header{
    background:linear-gradient(135deg,#0d8a4a,#0a5c31);
    color:white;
    padding:15px;
    text-align:center;
    box-shadow:0 3px 10px rgba(0,0,0,.2);
}

.header h1{
    font-size:28px;
}

.header p{
    font-size:14px;
}

.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
    padding:15px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 3px 10px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card-header{
    color:white;
    padding:12px;
    font-size:18px;
    font-weight:bold;
}

.emis{background:#2E7D32;}
.verval{background:#1565C0;}
.ujian{background:#EF6C00;}
.bos{background:#6A1B9A;}
.akreditasi{background:#C62828;}
.ppg{background:#00838F;}
.rapor{background:#5D4037;}
.pengembangan{background:#0277BD;}
.pai{background:#455A64;}

.menu{
    padding:10px;
}

.menu a{
    display:flex;
    align-items:center;
    gap:10px;
    text-decoration:none;
    color:#333;
    padding:8px 10px;
    border-radius:8px;
    margin-bottom:5px;
    transition:.2s;
}

.menu a:hover{
    background:#e8f5e9;
    color:#0d8a4a;
}

.menu i{
    width:20px;
    text-align:center;
    color:#0d8a4a;
}

.footer{
    text-align:center;
    padding:10px;
    color:#666;
    font-size:13px;
}
</style>
</head>

<body>

<div class="header">
    <h1>PELAYANAN TERPADU SATU PINTU</h1>
    <p>MTs Darul Ulum | Akses Cepat Aplikasi Madrasah</p>
</div>

<div class="dashboard">

<!-- PTSP -->
<div class="card">
<div class="card-header emis"><i class="fa-solid fa-database"></i> PTSP</div>
<div class="menu">
<a href="https://emis.kemenag.go.id/" target="_blank"><i class="fa-solid fa-server"></i> DAFTAR ULANG</a>
<a href="https://emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-laptop-code"></i> CETAK DAFTAR ULANG</a>
<a href="https://dev-emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-users"></i> PEMBAYARAN DPOP</a>
<a href="https://emis.kemenag.go.id/" target="_blank"><i class="fa-solid fa-server"></i> CETAK DPOP</a>
<a href="https://emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-user-graduate"></i> SIMPATIKA</a>
<a href="https://dev-emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-users"></i> EMIS PTK</a>
<a href="https://emis.kemenag.go.id/" target="_blank"><i class="fa-solid fa-server"></i> EMIS 4.0</a>
<a href="https://emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-user-graduate"></i> SIMPATIKA</a>
<a href="https://dev-emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-users"></i> EMIS PTK</a>
<a href="https://emis.kemenag.go.id/" target="_blank"><i class="fa-solid fa-server"></i> EMIS 4.0</a>
<a href="https://emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-user-graduate"></i> SIMPATIKA</a>
</div>
</div>

<!-- DATA -->
<div class="card">
<div class="card-header ppg"><i class="fa-solid fa-user-tie"></i> DATA</div>
<div class="menu">
<a href="https://ppg.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book-open"></i> PPG</a>
<a href="https://app.ppgkemenag.com/" target="_blank"><i class="fa-solid fa-laptop-code"></i> LMS PPG</a>
<a href="https://ukm.ppg.kemdikbud.go.id/" target="_blank"><i class="fa-solid fa-pen-ruler"></i> UKM PPG</a>
<a href="https://ppg.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book-open"></i> PPG</a>
<a href="https://app.ppgkemenag.com/" target="_blank"><i class="fa-solid fa-laptop-code"></i> LMS PPG</a>
<a href="https://ukm.ppg.kemdikbud.go.id/" target="_blank"><i class="fa-solid fa-pen-ruler"></i> UKM PPG</a>
<a href="https://ppg.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book-open"></i> PPG</a>
<a href="https://app.ppgkemenag.com/" target="_blank"><i class="fa-solid fa-laptop-code"></i> LMS PPG</a>
<a href="https://ukm.ppg.kemdikbud.go.id/" target="_blank"><i class="fa-solid fa-pen-ruler"></i> UKM PPG</a>
<a href="https://ppg.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book-open"></i> PPG</a>
<a href="https://app.ppgkemenag.com/" target="_blank"><i class="fa-solid fa-laptop-code"></i> LMS PPG</a>
</div>
</div>


<!-- PENDATAAN -->
<div class="card">
<div class="card-header verval"><i class="fa-solid fa-check-double"></i> PENDATAAN</div>
<div class="menu">
<a href="https://emis.kemenag.go.id/" target="_blank"><i class="fa-solid fa-server"></i> EMIS 4.0</a>
<a href="https://emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-user-graduate"></i> SIMPATIKA</a>
<a href="https://dev-emisgtk.kemenag.go.id/" target="_blank"><i class="fa-solid fa-users"></i> EMIS PTK</a>
<a href="https://sdm.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-id-card"></i> SDM Pusdatin</a>
<a href="https://pd.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-school"></i> PD Data</a>
<a href="https://nisn.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-magnifying-glass"></i> Cek NISN</a>
<a href="https://vervalpd.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-user-check"></i> Verval PD</a>
<a href="https://vervalsp.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-building"></i> Verval SP</a>
<a href="https://vervalptk.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-chalkboard-user"></i> Verval PTK</a>
<a href="https://vervalyayasan.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-landmark"></i> Verval Yayasan</a>
<a href="https://ats.data.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-user-xmark"></i> Verval ATS</a>
</div>
</div>

<!-- UJIAN&RAPORT -->
<div class="card">
<div class="card-header ujian"><i class="fa-solid fa-file-signature"></i> UJIAN & RAPORT</div>
<div class="menu">
<a href="https://pdum.kemenag.go.id/" target="_blank"><i class="fa-solid fa-file-pen"></i> PDUM</a>
<a href="https://anbk.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-laptop"></i> ANBK</a>
<a href="https://pusmendik.kemendikdasmen.go.id/an/simulasi_akm" target="_blank"><i class="fa-solid fa-play"></i> Simulasi ANBK</a>
<a href="https://dashboard.sulingjar.kemdikbud.go.id" target="_blank"><i class="fa-solid fa-chart-line"></i> Dashboard Sulingjar</a>
<a href="https://tka.kemendikdasmen.go.id/" target="_blank"><i class="fa-solid fa-graduation-cap"></i> TKA</a>
<a href="https://dashboardslb.kemendikdasmen.go.id/login" target="_blank"><i class="fa-solid fa-graduation-cap"></i> SULINGJAR</a>
<a href="https://shtka.kemendikdasmen.go.id/verifikasi-shtka" target="_blank"><i class="fa-solid fa-graduation-cap"></i> SHTKA</a>
<a href="https://rdm.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book"></i> RDM PUSAT</a>
<a href="https://mtsdarululumwringinputih.sch.id/" target="_blank"><i class="fa-solid fa-book"></i> RDM MTsDU</a>
<a href="https://ijazah.pendidikan.go.id/" target="_blank"><i class="fa-solid fa-scroll"></i> Portal Ijazah</a>
<a href="https://ijazah.data.kemendikdasmen.go.id/manajemen/#/sign-in" target="_blank"><i class="fa-solid fa-book"></i> MENEJEMEN IJAZAH</a>
</div>
</div>

<!-- BANTUAN&BOS -->
<div class="card">
<div class="card-header bos"><i class="fa-solid fa-money-bill-wave"></i> BOS & BANTUAN</div>
<div class="menu">
<a href="https://edm-fe.erkam-v2.kemenag.go.id/login" target="_blank"><i class="fa-solid fa-clipboard-list"></i> EDM</a>
<a href="https://frontend.erkam-v2.kemenag.go.id/login" target="_blank"><i class="fa-solid fa-wallet"></i> E-RKAM</a>
<a href="https://bos.kemenag.go.id/" target="_blank"><i class="fa-solid fa-coins"></i> Portal BOS</a>
<a href="https://pip.kemenag.go.id/login" target="_blank"><i class="fa-solid fa-hand-holding-dollar"></i> PIP Madrasah</a>
<a href="https://appmadrasah.kemenag.go.id/simsarpras/" target="_blank"><i class="fa-solid fa-hand-holding-dollar"></i> SIMSARPRAS</a>
<a href="https://ban-pdm.id/" target="_blank"><i class="fa-solid fa-medal"></i> BAN PDM</a>
<a href="https://apps.ban-pdm.id/sispena3/login" target="_blank"><i class="fa-solid fa-certificate"></i> Sispena</a>
<a href="https://pintar.kemenag.go.id/" target="_blank"><i class="fa-solid fa-brain"></i> Pintar Kemenag</a>
<a href="https://omi.kemenag.go.id/" target="_blank"><i class="fa-solid fa-star"></i> OMI</a>
<a href="https://ksm.kemenag.go.id/" target="_blank"><i class="fa-solid fa-trophy"></i> KSM</a>
<a href="https://ppg.kemenag.go.id/" target="_blank"><i class="fa-solid fa-book-open"></i> PPG</a>
</div>
</div>

</div>

<div class="footer">
© 2026 MTs DARUL ULUM WRINGINPUTIH | Link Penting Madrasah
</div>

</body>
</html>
